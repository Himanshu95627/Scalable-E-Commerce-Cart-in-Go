Project Overview
Title: Scalable E-Commerce Cart in Go

Objective: Build a scalable and secure e-commerce cart system to handle up to 100 requests per second.

Features
User Authentication

Secure login and signup.
JWT-based authentication.
Product Management

Search and list products.
Product details retrieval.
Cart Management

Add to cart.
List items in cart.
Update and remove cart items.
Checkout

Buy instantly and process payments.
Order tracking.
User Notifications

Add and manage email addresses.
Send notifications and marketing emails.
Technology Stack
Backend: Go (with Gin/Echo framework)
Frontend: React/Vue/Angular
Database: PostgreSQL/MySQL
Cache: Redis/Memcached
Message Queue: RabbitMQ/Kafka
Load Balancer: NGINX/HAProxy/AWS ELB
CDN: Cloudflare/AWS CloudFront
Infrastructure Requirements
Server Instances: 2-4 Go web server instances.
Database: 1 primary DB with 2 read replicas.
Cache: Redis/Memcached instance.
Load Balancer: NGINX/HAProxy/AWS ELB.
Message Queue: RabbitMQ/Kafka instance.
CDN: Cloudflare/AWS CloudFront.
Scalability Plan
Horizontal Scaling: Add more server instances as needed.
Database Scaling: Add read replicas for load distribution.
Caching: Implement caching for frequently accessed data.
Load Balancer: Distribute incoming traffic efficiently.
CDN: Serve static assets globally for faster access.
Security Measures
Authentication: JWT for secure user sessions.
Data Encryption: SSL/TLS for data in transit.
Input Validation: Prevent SQL injection and other attacks.
Access Control: Role-based access control for APIs.
