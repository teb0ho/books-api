# Mongo steps

Follow these steps with mongo db server installed on your machine or with a remote mongo db connection.

1. `mongo`
2. `use BookstoreDb`
3. `db.createCollection('Books')`
4. `db.Books.insertMany([{'Name':'Design Patterns','Price':54.93,'Category':'Computers','Author':'Ralph Johnson'}, {'Name':'Clean Code','Price':43.15,'Category':'Computers','Author':'Robert C. Martin'}])`
