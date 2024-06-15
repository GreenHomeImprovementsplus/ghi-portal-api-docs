## Refresh
Used to get new access token when it expires.
### Web

`GET /auth/refresh`

Body
```yaml
{
	"refreshToken": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InByb2plY3RzQGdyZWVuaG9tZWltcHJvdmVtZW50c3BsdXMuY29tIiwiaWF0IjoxNzE4NDY4OTkxLCJleHAiOjE3MTkwNzM3OTF9.BsPjyh475hmKGlWrqeBy5w9-HvEua6B0Qe3uUeCgHMk"
}
```

### Mobile

`POST /auth/refresh2`

Body
```yaml
{
	"refreshToken": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InByb2plY3RzQGdyZWVuaG9tZWltcHJvdmVtZW50c3BsdXMuY29tIiwiaWF0IjoxNzE4NDY4OTkxLCJleHAiOjE3MTkwNzM3OTF9.BsPjyh475hmKGlWrqeBy5w9-HvEua6B0Qe3uUeCgHMk"
}
```

*Access token should be save only in memory*