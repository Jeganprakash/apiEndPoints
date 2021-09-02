# Rest Endpoints

```
POST accounts/login
{
username:"username",
password:"password"
}
```

to generate new links with accessToken
```
GET /generateLink  
Authorization : Bearer accesstoken 
```

To serve react files to new Employee
```
GET /index/accessToken="tokenString"
```


graphql endpoint for query and mutation by client

```
POST /graphql
Authorization: Bearer token
```





