# http
GET - to retrieve resource representation/information only – and not modify it in any way. As GET requests do not change the resource’s state, these are said to be safe methods.
POST - to create new subordinate resources, e.g., a file is subordinate to a directory containing it or a row is subordinate to a database table. Also, responses to this method are not cacheable unless the response includes appropriate Cache-Control or Expires header fields.
PUT - to update an existing resource (if the resource does not exist, then API may decide to create a new resource or not).
DELETE - delete the resources (identified by the Request-URI)

200 - success status response code indicates that the request has succeeded. A 200 response is cacheable by default.
400 - Bad Request response status code indicates that the server cannot or will not process the request due to something that is perceived to be a client error (for example, malformed request syntax, invalid request message framing, or deceptive request routing).
500 - Internal Server Error server error response code indicates that the server encountered an unexpected condition that prevented it from fulfilling the request.
