# Rest Endpoints

```
POST accounts/login
{
username:"username",
password:"password"
}
```

### To generate new links with accessToken
```
GET /generateLink  
Authorization : Bearer accesstoken 
```



### To serve react files to new Employee
```
GET /index?accessToken="tokenString"
```




### Graphql endpoint for query and mutation by client

```
POST /graphql
Authorization: Bearer token
```





