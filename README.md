# GraphQL - my first project


## Promise

- It is replacement for REST APIs
- more efficient way to design, create and consume APIs.
- strongly typed (in schema.graphql its necessary to provide a definition for complex type, also fields have a type)
- single endpoint, no versioning (no need send HTTP request DELETE, POST,UPDATE, PATCH with given URI to modify resource... or create. one endpoint, inside request body operation is specified and all data needed to perform operation defined)
- no over-fetching of data?

### Concepts


* queries — (READ) the way you’re going to get data from the server.
* mutations  = (Create, Update, Delete) the way you’re going to modify data on the server and get updated data back
* subscriptions — the way you’re going to maintain a real-time connection with the server.

### building blocks - conventions? 
* schema.graphql < here I am creating data models, not only for ENTITIES (stared in db) but also for queries, mutators. equivalents of data structure in json payload in REST api
* resolver?