# Simple Web Server in Go

This project is a basic HTTP web server built using Go (Golang). It serves static HTML files and handles simple form submissions 


## Features

- Serves static HTML files (from the `/static` folder).
- Handles form submissions via the `/form` route.
- Responds to GET requests at `/hello` with a simple message.

## How to Run

1. **Clone the repository:**

```bash
git clone https://github.com/sharadhih/Web-Server-Using-Go.git
cd Web-Server-Using-Go
```

2. **Build and run the server**

```bash
go run main.go
```

3. **Access the web server**

-- http://localhost:8080/ - to view static HTML files (index.html).

-- Submit forms - http://localhost:8080/form.html