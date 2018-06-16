# golang-crud-example

## Requirements
* Install Golang

## How to start the project
1. Git Clone this project
2. run: `go build`
3. run: `./restapi.exe`
4. it will run on `localhost:8000`
5. try request below this

### Get All Books
GET Method: `/api/books`

### Get Single Book
GET Method: `/api/books/{id}`

### Create Book
POST Method: `/api/books`
```
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

### Update Book
PUT Method: `/api/books/{id}`
```
{
    "isbn": "700000000",
    "title": "Book Two Updated",
    "author": {
        "firstname": "Marked",
        "lastname": "Smitho"
    }
}
```

### Delete Book
DELETE Method: `/api/books/{id}`
