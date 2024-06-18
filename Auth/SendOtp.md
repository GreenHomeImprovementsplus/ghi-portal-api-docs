## Send OTP
You can use this to send or resend an OTP.

`/auth/send-otp`

### Sign Up

Body
```yaml
{
	"email": "user@email.com",
	"option": "signup"
}
```

### Forgot Password

Body
```yaml
{
	"email": "user@email.com",
	"option": "forgot-password"
}
```