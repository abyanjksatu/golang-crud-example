# golang-crud-example

## Get All Books
```
GET     "/api/books"
```

## Get Single Book
```
GET     "/api/books/{id}"
```

## Create Book
```
POST    "/api/books"
{
	"isbn":"5000000",
	"title":"Book Three",
	"author":
	{
		"firstname":"budi", 
		"lastname":"man"
	}
}
```

## Update Book
```
PUT     "/api/books/{id}"
{
    "isbn": "700000000",
    "title": "Book Two Updated",
    "author": {
        "firstname": "Marked",
        "lastname": "Smitho"
    }
}
```

## Delete Book
```
DELETE  "/api/books/{id}"
```
