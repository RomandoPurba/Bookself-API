# Bookself-API

### POST
- URL = <b>/books</b>
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
- URL = <b>/books</b>
- Response Body =>
  - id
  - name
  - publisher
 
- URL = <b>/books?name={name book}</b>
- Response Body =>
  - Menampilkan semua buku yang mengandung nama yang anda cari secara <i>non case sensitive</i>

- URL = <b>/books?reading={value}</b>
- Response Body =>
  - value = 1 => Menampilkan buku yang sudah dibaca
  - value = 0 => menampilkan buku yg belum dibaca

- URL = <b>/books?finished={value}</b>
- Response Body =>
  - value = 1 => Menampilkan buku yang sudah selesai dibaca
  - value = 0 => menampilkan buku yg belum selesai dibaca

- URL = <b>/books/{id buku}</b>
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
- URL = <b>/books/{id books}</b>
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
- URL = <b>/books/{id books}</b>
