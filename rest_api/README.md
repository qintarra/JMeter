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
- change the method to *PUT*
- add a parameter

![PUT Request](/rest_api/screenshots/put_param.jpg "parameter")

2. Run a request and check *Response data* and *Request Body*

![PUT result](/rest_api/screenshots/put_request_body.jpg "put request")

**This is largely dependent on how your database structure. So you would make sure to speak to your developers about this if you didn't understand it or needed some assistance**

#### Sending a DELETE

- duplicate the *POST* request and rename it to *DELETE*
- change the method to *DELETE*
- choose a parameter to delete
- run a request

![DELETE result](/rest_api/screenshots/delete.jpg "delete request")  

**In a real-world situation you would need to be very specific about what you wanted to delete.**