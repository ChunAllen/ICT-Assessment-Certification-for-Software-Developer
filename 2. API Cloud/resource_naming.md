# Resource Naming


#### 1.1. Singleton and Collection Resources
A resource can be a singleton or a collection.

For example, “customers” is a collection resource and “customer” is a singleton resource (in a banking domain).

We can identify “customers” collection resource using the URI “/customers“. We can identify a single “customer” resource using the URI “/customers/{customerId}“.


```
/customers			//is a collection resource

/customers/{id}		// is a singleton resource
```

#### 1.2 Collection and Sub-collection Resources

For example, sub-collection resource “accounts” of a particular “customer” can be identified using the URN “/customers/{customerId}/accounts” (in a banking domain).

Similarly, a singleton resource “account” inside the sub-collection resource “accounts” can be identified as follows: “/customers/{customerId}/accounts/{accountId}“.

```
/customers						//is a collection resource

/customers/{id}/accounts		// is a sub-collection resource
```


### Best Practices
-  Use nouns to represent resources
```
/device-management/managed-devices 

/device-management/managed-devices/{device-id} 

/user-management/users

/user-management/users/{id}
```

- Use hyphens (-) to improve the readability of URIs
```
http://api.example.com/devicemanagement/manageddevices/
http://api.example.com/device-management/managed-devices 	/*This is much better version*/
```


- Do not use underscores ( _ )
```
http://api.example.com/inventory-management/managed-entities/{id}/install-script-location  //More readable

http://api.example.com/inventory-management/managedEntities/{id}/installScriptLocation  //Less readable
```

- Use Lowercase letters 
- Do not use file extensions
- Do not use verbs in URI
```
/device-management/managed-devices/{id}/scripts/{id}/execute	//DON't DO THIS!

/device-management/managed-devices/{id}/scripts/{id}/status		//POST request with action=execute
```