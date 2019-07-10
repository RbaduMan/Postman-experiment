# Postman test experiment

## To run this example
Install newman
```
npm install -g newman
```
Run test
```
newman run Restful_Booker_Generate_Collection.postman_collection.json -d CustomersMock.json -e Test.postman_environment.json
```