
# Scalable E-Commerce Cart in Go

## Project Overview
**Title**: Scalable E-Commerce Cart in Go

**Objective**: Build a scalable and secure e-commerce cart system to handle up to 100 requests per second.

## Features
1. **User Authentication**
   - Secure login and signup.
   - JWT-based authentication.

2. **Product Management**
   - Search and list products.
   - Product details retrieval.

3. **Cart Management**
   - Add to cart.
   - List items in cart.
   - Update and remove cart items.

4. **Checkout**
   - Buy instantly and process payments.

[//]: # (   - Order tracking.)

5. **User Notifications**
   - Add and manage email addresses.

[//]: # (   - Send notifications and marketing emails.)

## Technology Stack
- **Backend**: Go (with Gin/Echo framework)

[//]: # (- **Frontend**: React/Vue/Angular)
- **Database**: MySQL

[//]: # (- **Cache**: Redis/Memcached)

[//]: # (- **Message Queue**: RabbitMQ/Kafka)

[//]: # (- **Load Balancer**: NGINX/HAProxy/AWS ELB)

[//]: # (- **CDN**: Cloudflare/AWS CloudFront)

## Infrastructure Requirements
- **Server Instances**: 2-4 Go web server instances.
- **Database**: 1 primary DB with 2 read replicas.

[//]: # (- **Cache**: Redis/Memcached instance.)

[//]: # (- **Load Balancer**: NGINX/HAProxy/AWS ELB.)

[//]: # (- **Message Queue**: RabbitMQ/Kafka instance.)

[//]: # (- **CDN**: Cloudflare/AWS CloudFront.)

## Scalability Plan
- **Horizontal Scaling**: Add more server instances as needed.
- **Database Scaling**: Add read replicas for load distribution.

[//]: # (- **Caching**: Implement caching for frequently accessed data.)

## Security Measures
- **Authentication**: JWT for secure user sessions.
- **Input Validation**: Prevent SQL injection and other attacks.

