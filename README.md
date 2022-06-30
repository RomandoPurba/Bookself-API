# Bookself-API

### POST
- URL = /books
- Body Request =>
    - name = string,
    - year = number,
    - author = string,
    - summary = string,
    - publisher = string,
    - pageCount = number,
    - readPage = number,
    - reading = boolean
    

### GET
- URL = /books
- Response Body =>
  - id
  - name
  - publisher
  
  
  
- URL = /books/{id buku}
- Body Response =>
  - id
  - name
  - year
  - author
  - summary
  - publisher
  - pageCount
  - readPage
  - finished
  - reading
  - insertedAt
  - updatedAt
  
### PUT
- URL = /books/{id books}
- Body Request =>
   - name = string,
   - year = number,
   - author = string,
   - summary = string,
   - publisher = string,
   - pageCount = number,
   - readPage = number,
   - reading = boolean

### DELETE
- URL = /books/{id books}
