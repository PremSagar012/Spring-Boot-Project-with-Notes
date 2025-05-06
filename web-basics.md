How the Web Works
Overview
The web operates on a client-server model where clients request resources from servers, and servers respond with data. This process relies on protocols, APIs, and systems like DNS to deliver content efficiently.
Key Concepts
Client-Server Model

Client: A device or application (e.g., web browser, email client) that requests services or resources from a server.
Server: A device or application that hosts resources (e.g., websites, APIs) and responds to client requests.
Examples:
Web Browsing: A browser (client) requests a webpage from a web server.
Email: An email client (e.g., Outlook) retrieves messages from a mail server.



URL (Uniform Resource Locator)

A URL is the address used to locate resources on the web (e.g., https://example.com).
Components:
Protocol (e.g., https)
Domain (e.g., example.com)
Path (e.g., /page)


Domain Name System (DNS):
Translates human-readable domain names (e.g., example.com) into IP addresses (e.g., 192.0.2.1) and vice versa.



APIs (Application Programming Interface)

Definition: A set of rules and protocols allowing different software applications to communicate.
Types of APIs:
Private: Internal use within an organization.
Public: Available to external developers (e.g., Google Maps API).
Partner: Shared between specific business partners.


Common API Request Types:
GET: Retrieve data.
POST: Send data to create a resource.
PUT: Update an existing resource.
DELETE: Remove a resource.



REST API

Definition: Representational State Transfer (REST) is an architectural style for designing networked applications.
Characteristics:
Uses HTTP methods (GET, POST, PUT, DELETE) to perform operations.
Returns data in formats like JSON or XML.
Stateless: Each request is independent.


RESTful Web Services: Web services built following REST principles.

HTTP vs. HTTPS

HTTP (HyperText Transfer Protocol):
A protocol for transmitting data over the internet.
Unencrypted, less secure.


HTTPS (HyperText Transfer Protocol Secure):
HTTP with encryption (SSL/TLS).
Ensures secure data transfer, widely used for websites.



HTTP Status Codes

Definition: Codes returned by servers to indicate the result of a client’s request.
Classification:
1xx (Informational): Request received, processing.
2xx (Successful): Request successfully completed.
3xx (Redirection): Further action needed to complete the request.
4xx (Client Error): Client-side issue (e.g., bad request).
5xx (Server Error): Server-side issue (e.g., internal error).


Common Status Codes:


Code
Meaning
Description



200
OK
Request successful.


201
Created
Resource created successfully.


204
No Content
Request successful, no content returned.


301
Moved Permanently
Resource moved to a new URL.


400
Bad Request
Invalid request syntax.


401
Unauthorized
Authentication required.


403
Forbidden
Access denied.


404
Not Found
Resource not found.


500
Internal Server Error
Server encountered an error.




Key Takeaways

The web relies on client-server communication, facilitated by URLs and DNS.
APIs, especially RESTful ones, enable seamless application interactions using HTTP methods and JSON/XML.
HTTPS ensures secure data transfer, and status codes provide clear feedback on request outcomes.


