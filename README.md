# Rest Endpoints


### For employer login

### To get login page
```
GET accounts/login 
```
### To verify employer credentials

```
POST accounts/login
{
username:"username",
password:"password"
}
```

### To generate new form links with accessToken by the employer
```
GET /generateLink  
Authorization : Bearer accesstoken 
```



### To serve home page for employer/show error to the user
```
GET /index?accessToken="tokenString"
```

### To verify accessToken
```
POST /verify
{
accessToken:"tokenString"
}
```

### Graphql endpoint for query and mutation by client
```
POST /graphql
Authorization: Bearer token
```




*Graphql Schema is in schema.graphql file*



