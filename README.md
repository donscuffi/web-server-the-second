GET localhost:8080/health

###
GET localhost:8080/people

###
POST http://localhost:8080/people
Content-Type: application/json

{
  "name": "anyname",
  "age": 50
}
