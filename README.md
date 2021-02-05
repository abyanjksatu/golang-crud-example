# golang-crud-example

## Requirements
* Install Golang. open: https://golang.org/doc/install

## How to start the project
1. Git Clone this project. run: `git clone https://github.com/kecci/golang-crud-example.git`
2. run: `go run main.go`
3. it will run on `localhost:8000`
4. try request below this

### Get All Books
GET Method: `/api/books`
```
// Response:
[
{
	"id":1,
	"isbn":"5000000",
	"title":"Book Three",
	"author":
	{
		"firstname":"budi", 
		"lastname":"man"
	}
},
{
	"id":1,
	"isbn":"5000000",
	"title":"Book Three",
	"author":
	{
		"firstname":"budi", 
		"lastname":"man"
	}
}
]
```

### Get Single Book
GET Method: `/api/books/{id}`
```
// Response:
{
	"id":1,
	"isbn":"5000000",
	"title":"Book Three",
	"author":
	{
		"firstname":"budi", 
		"lastname":"man"
	}
}
```

### Create Book
POST Method: `/api/books`
```
// Request:
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
// Request:
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
```
// Response:
{
	"id":1,
	"isbn":"5000000",
	"title":"Book Three",
	"author":
	{
		"firstname":"budi", 
		"lastname":"man"
	}
}
```
