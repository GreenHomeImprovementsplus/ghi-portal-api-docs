## Verify
After sign up use this to verify the email. Works to all user types.

`POST /auth/verify`

Body
```yaml
{
	"email": "user@email.com",
	"otp": "1234"
}
```