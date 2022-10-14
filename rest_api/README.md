# JMeter

## REST APIs

Endpoint: http://orangevalleycaa.org/api/videos

#### Sending a POST

1. *Thread Group* > *Sampler* > *HTTP Request*:
- duplicate it and add GET and POST to their names
- change the method to *POST* in POST request
- fill the *Protocol*, *Server Name*, *Path* fields
- add some parameters in *POST* request 
![POST Parameters](/rest_api/screenshots/post_params.jpg "parameter")

2. Add a *View Results Tree* listener and run the test
![POST result](/rest_api/screenshots/post_result.jpg "test run")

#### Sending a PUT

1. Preparing request:
- duplicate the *POST* request and rename it to *PUT*