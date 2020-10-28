# ***Read 07***

![api](https://www.seobility.net/en/wiki/images/f/f1/Rest-API.png)

## What is REST API?
REST suggests to create an object of the data requested by the client and send the values of the object in response to the user. For example, if the user is requesting for a movie in Bangalore at a certain place and time, then you can create an object on the server-side.

So, over here, you have an object and you are sending the state of an object. This is why REST is known as Representational State Transfer.

If I have to define REST, then,  Representational State Transfer a.k.a REST is an architectural style as well as an approach for communications purpose that is often used in various web services development.

The architectural style of REST helps in leveraging the lesser use of bandwidth to make an application more suitable for the internet. It is often regarded as the “language of the internet” and is completely based on the resources.

![pa](https://static.fortytwo.com/assets/wp-content/uploads/2015/09/api_diagram_2FA_Request.png)

## Principles of REST API

Well, there are six ground principles laid down by Dr. Fielding who was the one to define the REST API design in 2000. Below are the six guiding principles of REST:

Stateless
The requests sent from a client to a server will contain all the required information to make the server understand the requests sent from the client. This can be either a part of URL,  query-string parameters, body, or even headers. The URL is used to uniquely identify the resource and the body holds the state of the requesting resource. Once the server processes the request, a response is sent to the client through body, status or headers

Client-Server
The client-server architecture enables a uniform interface and separates clients from the servers.  This enhances the portability across multiple platforms as well as the scalability of the server components.

Uniform Interface
To obtain the uniformity throughout the application, REST has the following four interface constraints:

Course Curriculum
Web Development Certification Training
Instructor-led Live SessionsReal-life Case StudiesAssignmentsLifetime Access
Resource identification
Resource Manipulation using representations
Self-descriptive messages
Hypermedia as the engine of application state
Cacheable
In order to provide a better performance, the applications are often made cacheable. This is done by labeling the response from the server as cacheable or non-cacheable either implicitly or explicitly. If the response is defined as cacheable, then the client cache can reuse the response data for equivalent responses in the future.

Layered system
The layered system architecture allows an application to be more stable by limiting component behavior.  This type of architecture helps in enhancing the application’s security as components in each layer cannot interact beyond the next immediate layer they are in. Also, it enables load balancing and provides shared caches for promoting scalability.

Code on demand

This is an optional constraint and is used the least. It permits a clients code or applets to be downloaded and to be used within the application. In essence, it simplifies the clients by creating a smart application which doesn’t rely on its own code structure.


![rest](https://miro.medium.com/max/680/1*XYWxcn3PSfDIjxUnaKVR4Q.jpeg)

### ***Thank you*** 😁😊