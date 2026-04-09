# API Demo

## Instructions  
javac ApidemoApplication.java
java ApidemoApplication

## Routes  
GET `/api/products` - Get all products  
GET `/api/products/1` - Get product by ID
POST `/api/products/` - Add a product

```
{
    "name" : "HD Monitor",
    "price" : 445.50,
    "stock_count" : 10,
    "description" : "4K HD 45 inch Monitor."
}
```
