# Personalized Event Search and Recommendation System

demo link: 
[demo](http://ec2-3-129-148-239.us-east-2.compute.amazonaws.com/Jupiter)

The home page:
![image](https://github.com/McRose1/Jupiter/blob/master/images/Home.png)

## Logic Graph of this project 
![image](/images/logicGraph.png)


## RESTful Design Pattern
- Using HTTP methods to indicate what kind of operation a client want to take 
- Using HTTP url to indicate which service and data a client want to use and what kind of data they request 
- Every request is separated, there is no support doing one post request in several post requests, or doing a delete in a pair of get and post requests

## Why Using RESTful?
- Operations are directly based on HTTP methods, so that server don't need to parse extra thing
- URL clearly indicates which resource a client want, easy for client side users to understand
- Server is running in stateless mode, improve scalability 



## This project is based on TicketMaster API
![image](/images/tmAPI.png)
