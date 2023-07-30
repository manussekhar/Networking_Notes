1. Stateless: HTTP is a stateless protocol, which means that each request-response cycle is independent and does not retain information from previous interactions. This means that the server treats each request as an isolated event and doesn't remember past requests from the same client.
    
2. Request-Response Model: The communication between the client and server occurs through a request-response model. The client sends an HTTP request to the server, and the server responds with an HTTP response containing the requested data or an error message.
    
3. Methods: HTTP supports various request methods, each serving a specific purpose. The most common methods are:
    
    - GET: Requests data from the server, typically used for retrieving web pages or resources.
    - POST: Submits data to be processed by the server, often used for form submissions and data uploads.
    - PUT: Uploads a resource to the server, typically used for updating existing resources.
    - DELETE: Requests the server to remove a resource.
    - HEAD: Requests only the headers of a resource without the actual content, useful for checking the resource's metadata.
4. Status Codes: HTTP responses include status codes that indicate the outcome of the request. Some common status codes include 200 (OK), 404 (Not Found), 500 (Internal Server Error), and many others, each representing a different condition.
    
5. URL (Uniform Resource Locator): HTTP requests are made to specific resources identified by URLs. A URL includes the protocol (HTTP or HTTPS), the domain name or IP address of the server, the port number, and the path to the resource.