# Tutorial API - Open Source for CRUD operation

## API 

| Method | End Point | Params | Description
| --- | --- | --- |
| POST | api/tutorials | {"title" : "String","description":"String"} | Create new tutorial |
| GET | api/tutorials |  | Get all tutorial |
| GET | api/tutorials/:Id |  | Get single record of tutorial |
| PUT | api/tutorials/:Id | {"title" : "String","description":"String", "published" : boolean,} | Update tutorial record using Id |
