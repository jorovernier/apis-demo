# APIs Demo

This is a finished version of the APIs demo. Use this for all your referencing needs!

#
In Postman, the following request URLs will allow you to interact with the Houseware Mockend API.

### GET
All Items
```
http://localhost:4000/api/inventory
```
Individual Item
```
http://localhost:4000/api/inventory/antique_chair
```

### POST
```
http://localhost:4000/api/inventory/
```
Body Object
```
{
  "id": "happychair",
  "category": "Chair",
  "name": "happy chair"
}
```

### PATCH
```
http://localhost:4000/api/inventory/happychair
```
Property to Edit (Body Object)
```
{
  "sellPrice": 5000
}
```

### DELETE
```
http://localhost:4000/api/inventory/happychair
```