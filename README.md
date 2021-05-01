# Tutorial API - Open Source API for CRUD operation

## API End Point and Params
## BASE URL : https://salty-harbor-94993.herokuapp.com/

| Method | End Point | Params | 
| --- | --- | --- |
| POST | api/tutorials | {"title" : "String","description":"String"} |
| GET | api/tutorials |  | 
| GET | api/tutorials/:Id |  |
| PUT | api/tutorials/:Id | {"title" : "String","description":"String", "published" : boolean,} |
| GET | api/tutorials/published |  |
| GET | api/tutorials?title=String |  |
| DELETE | api/tutorials/:Id |  |
