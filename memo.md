#6
to run Server use Http().bindAndHandle(...)

#8
marshal/unmarshal - use spray-json lib

#9
created simple get post api

#11 SKIPPED

#12
create HighLevel API with Routing tree (concatenate paths/methods with ~ operator)

#13
* to create complex paths use path("api" / "myEndpoint") for example. path("api/myEndpoint") = api%2FmyEndpoint
* use pathEndOrSingleSlash to localhost:8080 or localhost:8080/ 
* to get variable from get query use parameter('id)

#14
use extractRequest & extractLog to log whole incoming request

#15
more specific path in the Routing tree goes first