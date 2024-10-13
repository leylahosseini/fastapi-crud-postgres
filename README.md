# fastapi-crud-postgres


## GET ALL
curl -X GET "http://localhost:8000/items/"  

## GET ONE
curl -X GET "http://localhost:8000/items/{item_id}"

## POST
curl -X POST "http://localhost:8000/items/"   -H "Content-Type: application/json"  -d '{"name": "example_name","description": "example_description"}'

## DELETE
curl -X DEELTE "http://localhost:8000/items/{item_id}"  


## PUT
curl -X PUT  "http://localhost:8000/items/{item_id}"  -H "Content-Type: application/json"  -d '{"name": "example_name","description": "example_description"}'
