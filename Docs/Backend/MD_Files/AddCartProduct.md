## Add Product Into Cart API - Siddharth Kardile
```
POST /addToCart
```

## Request Headers
```
Content-Type : application/json
bearer <token>  

```
## Request Body
``` json 
{
  "productId" : "Long"
}

```
## Response
```
200 - Success
Body
{
  "message" : "String"
}

400 - Bad Request - user Not Found
401 - Unauthorized
404 - Not Found
500 - Internal Server Error
