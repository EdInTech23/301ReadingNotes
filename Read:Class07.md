# Readings: Web Server Deployment
Below you will find reading material and additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

# Reading
## What is NGINX?

### What are some common use cases for NGINX?
Web Server: Serving static content efficiently
Reverse Proxy: Distributing requests to backend server
Load Balancer: Balancing traffic across multiple servers
SSL/TLS Termination: Handling encryption and decryption for HTTPS
Caching: Improving performance by caching static content
API Gateway: Managing and securing access to backend APIs
Security: Implementing access control, rate limiting, and WAF features
Content Delivery Network (CDN): Improving content delivery speed
WebSocket Support: Handling real-time bidirectional communication
Microservices Architecture: Managing traffic between microservices

### How does NGINX handle tasks that could slow down the web server?
NGINX handles performance-draining tasks like SSL encryption and content rendering before they reach the main web server, acting as a buffer and speeding things up.

### Describe, as if to a non-technical friend how to actually pronounce “NGINX”, and why an org might chooose to use it.
Imagine engine crashes into X and become one word. That's "NginX"! It's like a supercharged engine for websites, making them faster and smoother.
