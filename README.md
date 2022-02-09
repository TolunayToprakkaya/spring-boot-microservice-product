# Microservice Product

### Endpoints:

#### Save Product

````
POST /api/product HTTP/1.1
Host: localhost:3333
Authorization: Basic base64(username:password)
Content-Type: application/json
Cookie: JSESSIONID=A01F3038C29C468DECB2A1BF2139C3DE
Content-Length: 43

{
    "name": "Name",
    "price": 1.2
}
````

#### Get Products

````
GET /api/product HTTP/1.1
Host: localhost:3333
Authorization: Basic base64(username:password)
Cookie: JSESSIONID=A01F3038C29C468DECB2A1BF2139C3DE
````

#### Delete Product

````
DELETE /api/product/1 HTTP/1.1
Host: localhost:3333
Authorization: Basic base64(username:password)
Cookie: JSESSIONID=A01F3038C29C468DECB2A1BF2139C3DE
````