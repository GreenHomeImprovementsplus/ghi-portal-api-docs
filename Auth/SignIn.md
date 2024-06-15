## Sign In

### Web

`POST /auth/signin`

Body
```yaml
{
	"email": "user@email.com",
	"password": "1234"
}
```

### Mobile

`POST /auth/signin2`

Body
```yaml
{
	"email": "user@email.com",
	"password": "1234"
}
```

*Save the refresh token in secure storage and for the access token save it in memory for better security*