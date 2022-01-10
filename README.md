## Spring Boot Microservice 2 - Transaction Service
This service is second of three micro-service.

### Endpoints

#### 1- Save Transaction
```
POST /api/transaction     HTTP/1.1
Host: localhost:4444
Authorization: Basic basic64(username:password)
Content-Type: application/json
Content-Length: 37

{
"userId":1,
"productId":1
}
```

#### 2- Get Transaction
```
GET /api/transaction/1     HTTP/1.1
Host: localhost:4444
: 
Authorization: Basic basic64(username:password)
```

#### 3- Delete Transaction
```
DELETE /api/transaction/1     HTTP/1.1
Host: localhost:4444
: 
Authorization: Basic basic64(username:password)
```