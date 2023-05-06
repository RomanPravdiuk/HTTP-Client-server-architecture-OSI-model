# HTTP, Client server architecture, OSI-model

#### HTTP:

| Термин | Описание |
| :----------------- | :------------------ |
| HTTP | Hypertext Transfer Protocol, an application layer protocol for exchanging data between two links in a network |
| Протокол |	A set of rules and conventions for exchanging data between two or more devices on a network |
| HTTP methods | Methods that define the type of request used to exchange data between two links in the system: GET, POST, PUT, PATCH, DELETE, OPTIONS |
| OPTIONS	| A method used to request information about available HTTP methods on the server |
| HTTP body	| Data that is sent via the HTTP protocol |
| Request body |	Request body containing data sent to the server |
| Response body |	The body of the response containing the data returned by the server |
| Типы данных |	JSON, XML, form-data, text |
| HTTP response statuses |	Response codes that indicate the status of the request: 1xx (informational), 2xx (success), 3xx (redirection), 4xx (client error), 5xx (server error) |
| 502 Bad Gateway	| The error that occurs when the server cannot receive a response from the other server to which it is accessing |
| 504 Gateway Timeout |	Error that occurs when the server cannot receive a response from another server at the set time |
| HTTP headers |	Information transmitted in the headers of the request or response |
| Authorization	| Header used to transfer the authorization token from the client to the server |
| Cookie / Set-Cookie	| Header used to transfer cookie information between the client and the server |
| Content-Type |	The header used to specify the type of content that is sent or received via HTTP |
| Content-Encoding |	Header used to specify the compression algorithm used to compress the message body |
| User-Agent	| The header used to convey information about the browser or device that sends the request |
| Connection |	Header used to specify the connection parameters between the client and the server |


![Http-versions](https://github.com/AlexeyLobanov1/HTTP-Client-server-architecture-OSI-model/blob/main/Http-versions.jpg)

## Client server architecture:

![The simplest, client-server.](https://github.com/AlexeyLobanov1/HTTP-Client-server-architecture-OSI-model/blob/main/The%20simplest%2C%20client-server.jpg)

![A little more complicated, client - server - database](https://github.com/AlexeyLobanov1/HTTP-Client-server-architecture-OSI-model/blob/main/A%20little%20more%20complicated%2C%20client%20-%20server%20-%20database.jpg)

![Example of large application sites](https://github.com/AlexeyLobanov1/HTTP-Client-server-architecture-OSI-model/blob/main/Example%20of%20large%20application%20sites.jpg)

## OSI-model:

![osi-model](https://github.com/AlexeyLobanov1/HTTP-Client-server-architecture-OSI-model/blob/main/OSI.jpg)
