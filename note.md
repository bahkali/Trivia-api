## API

application programming interface hide implimentation,
standardization of accessing the application.

## Client-Server communication:

```
Client -> banker -> Vault
Client -> Server -> Database
```

client send request to server, after parsing the request the
server execute the command to the database and return the response
to the client where it will be rendered.

## Internet Protocols(IPs)

send data from one to another
computer across interet

you have TCP, FTP

## Hypertext Transmission Protocol(http)

used for transmiting text and hyperlinks

- connectionless only open connection when request and close
- Stateless - mean that the success of one request doesn't effect the other.
- Media Independant - any data can be sent as long as client and server know the type

http contents:
URIs - knows as address point to specific
messages
Status codes (of the request status, 200, 404)

Http Request (Method, Path, Http version , Headers, Body)

## RESTful APIs

Representational State Transfer

- Uniform interface for every resource there is a corresponding
- Stateless each request is stand alone - Cacheable and Layered system for efficiency

Flask Basics
Flask Endpoints, Curl( For testing locally ),
Jsonify (Format the data)

To run psql from commandline you need:

1. install postgres
2. include the path of postgres to the environment variable
3. now you can type

```
 psql -U postgres -h localhost -d mydb
 psql -U postgres -h localhost -d mydb -f test.sql
```
