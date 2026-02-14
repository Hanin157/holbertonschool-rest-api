Basics of HTTP and HTTPS

1. Differences Between HTTP and HTTPS

HTTP (Hypertext Transfer Protocol) is the standard protocol used for communication between a client and a web server. It transfers data in plain text, which means the information can be intercepted and read by attackers.

HTTPS (Hypertext Transfer Protocol Secure) is the secure version of HTTP. It uses SSL/TLS encryption to protect the data transmitted between the client and the server. This encryption ensures confidentiality, integrity, and authentication.

Main differences:
 • HTTP does not encrypt data.
 • HTTPS encrypts data using SSL/TLS.
 • HTTP is vulnerable to interception and data tampering.
 • HTTPS protects sensitive information such as passwords and credit card data.
 • HTTP typically uses port 80.
 • HTTPS typically uses port 443.

⸻

2. Structure of an HTTP Request and Response

HTTP Request Structure

An HTTP request is composed of:
 • Request Line (Method + Path + HTTP Version)
 • Headers
 • Optional Body

Example:

GET /index.html HTTP/1.1
Host: example.com
User-Agent: Mozilla/5.0

HTTP Response Structure

An HTTP response is composed of:
 • Status Line (HTTP Version + Status Code + Message)
 • Headers
 • Body

Example:

HTTP/1.1 200 OK
Content-Type: text/html
<html>Response Content</html>
3. Common HTTP Methods

GET
Description: Retrieves data from a server.
Use case: Fetching a webpage or retrieving data from an API.

POST
Description: Sends data to the server to create a resource.
Use case: Submitting a registration form.

PUT
Description: Updates an existing resource.
Use case: Updating user profile information.

DELETE
Description: Deletes a resource.
Use case: Removing a user account.

⸻

4. Common HTTP Status Codes

200 OK
Description: The request was successful.
Scenario: A webpage loads correctly.

201 Created
Description: A resource was successfully created.
Scenario: A new user account is created.

301 Moved Permanently
Description: The resource has been permanently redirected.
Scenario: A website redirects to a new URL.

400 Bad Request
Description: The request is invalid.
Scenario: Missing required form data.

404 Not Found
Description: The requested resource was not found.
Scenario: Accessing a non-existing page.

500 Internal Server Error
Description: The server encountered an unexpected condition.
Scenario: A server-side application error.
