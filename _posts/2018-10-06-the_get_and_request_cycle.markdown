---
layout: post
title:      "The Get and Request Cycle"
date:       2018-10-06 04:31:55 +0000
permalink:  the_get_and_request_cycle
---


HTTP stands for HyperText Transfer Protocol. This is a basis for data communication in the internet. The data communication starts with a request sent from a client and ends with the response received from a web server.

* A website URL starting with “http://” is entered in a web browser from a computer (client). 
* Browser sends a request sent to the web server that hosts the website.
* The server then returns a response as a HTML page or any other document format to the browser.

*Request–response is one of the basic methods computers use to communicate with servers.*  A computer sends a request for some data and the server responds to the request. Usually, there is a series of such interchanges until the complete message is sent; browsing a web page is an example of request–response communication. 

##### We refer to 'users' as using Browsers or **Clients**. 

Clients make requests.  
Servers make responses and send them back to the browser.  
Browsers render views of web pages based on data received by a servers response.  
Request–response can be seen as a telephone call, in which someone is called and they answer the call.

![](http://www.thesilentc.com/rqstrspnc.png)

The two most common HTTP methods for sending requests are:
* The GET request is used to request data from a specified resource.
* The POST request is used to send data to a server to create/update a resource.

When a URL is inputted, the browser sends a GET request to a web server. When a form is submitted on a website, a POST request is submitted, and the browser hands off the form data to be handled by the server.

POST requests send data to a server, which then send a response 
as a view rendered in HTML back in the browser.

##### Some other notes on GET requests:

* GET requests can be cached
* GET requests remain in the browser history
* GET requests can be bookmarked
* GET requests should never be used when dealing with sensitive data
* GET requests have length restrictions
* GET requests is only used to request data (not modify)

##### Some other notes on POST requests:

* POST requests are never cached
* POST requests do not remain in the browser history
* POST requests cannot be bookmarked
* POST requests have no restrictions on data length


