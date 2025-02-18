# HTTP-Server

## Project Overview 🚀 
This project is a lightweight HTTP server written in C, designed to handle basic web requests efficiently. It serves static files and processes HTTP GET requests, making it a useful foundation for understanding server-side networking in C. Additionally, it includes an integration with an external mdb-lookup-server for database lookups.

## Key Features 🔥 
- Fast and Lightweight: Written in C for optimal performance.
- GET Request Handling: Processes HTTP GET requests.
- Static File Serving: Serves files from a specified web root directory.
- Database Lookup Integration: Communicates with an external mdb-lookup-server.
- Basic HTTP Status Codes: Returns standard responses (200 OK, 404 Not Found, etc.).
- Socket Programming: Implements low-level networking using sockets.

## Why This Project? 📌 
- This project showcases fundamental server-side programming concepts, making it perfect for:
- Students and developers learning about networking in C.
- Those interested in building custom web servers.
- Anyone looking for a lightweight server for static content.

## How to Start 💡
### Clone the Repository to your local server: 
```
git clone <link to this repository>
```

### Compile the server: 
```
make
```

### Run the server: 
```
<server_port> <web_root> <mdb-lookup-host> <mdb-lookup-port>
```
- `server_port`: Port number to run the server (e.g., 8080)
- `web_root`: Directory for static files (e.g., ./www)
- `mdb-lookup-host`: Hostname of the database lookup server
- `mdb-lookup-port`: Port number of the database lookup server

### Access the server: 
```
http://localhost:8080
```

### Project Structure: 
```
HTTP-Server/
│── http-server.c       # Main server source code
│── Makefile            # Build script
│── www/                # Static files directory
```

