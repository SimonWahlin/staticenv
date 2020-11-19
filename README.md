# STATICENV

Simple nginx container that will respond with the content of an environement variable named CONTENT.

## Useage

I use this container to demo and troubleshoot ingress routing and load balancing scenarios for containers. 
By injecting an environment called CONTENT that contains different values for each container, 
I can easy see which container that ends up serving my request.

Exampele value for content:

Container "green"
```
<html><body bgcolor="green"><h1 style="color:white;">GREEN</h1></body></html>
```

Container "blue"
```
<html><body bgcolor="blue"><h1 style="color:white;">BLUE</h1></body></html>
```
