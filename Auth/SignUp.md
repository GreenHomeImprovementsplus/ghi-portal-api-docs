## Sign Up

### Consultant

`POST /auth/signup`

Body
```yaml
{
	"email": "user@email.com",
	"password": "1234",
	"firstName": "John",
	"lastName": "Doe",
	"phoneNumber": "(123) 4567-8902",
	"streetAddress": "Rizal St.",
	"steAptAddress": "12",
	"cityAddress": "Iligan City",
	"stateAddress": "Lanao",
	"zipAddress": "9200",
	"consultantType": [
		{
			"projectId": "662d09306ecb3ccf7a7fdf5a",
			"status": 0
		}
	]
}
```

### Champion

`POST /auth/champion/signup`

Body
```yaml
{
	"imgUrl": "https://website.com/avatar/image.jpg",
	"email": "user@email.com",
	"password": "1234",
	"firstName": "John",
	"lastName": "Doe",
	"phoneNumber": "(123) 4567-8902",
	"streetAddress": "Rizal St.",
	"steAptAddress": "12",
	"cityAddress": "Iligan City",
	"stateAddress": "Lanao",
	"zipAddress": "9200"
}
```

### Upload Avatar

`POST /cloud-storage/upload/avatar`

Body

	Multipart Form

	Name: file
	Value: image.jpg