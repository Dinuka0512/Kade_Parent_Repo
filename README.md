# KADE - E-Commerce Platform

This repository is the parent repository for the KADE E-Commerce Platform.

It provides access to the frontend application, backend microservices platform, service discovery, API gateway, and individual backend microservices.

## Repositories

### Frontend

- [KADE Frontend](https://github.com/Dinuka0512/kade_frontend)

### Backend - Microservices Platform

- [API Gateway](https://github.com/Dinuka0512/kade_api_gateway)
- [Eureka Server](https://github.com/Dinuka0512/kade_eureka_server)

### Backend - Microservices

- [User Service](https://github.com/Dinuka0512/kade_user_service)
- [Product Service](https://github.com/Dinuka0512/kade_product_service)
- [Order Service](https://github.com/Dinuka0512/kade_order_service)

## System Architecture

```text
                         KADE E-Commerce Platform
                                  |
                    +-------------+-------------+
                    |                           |
                Frontend                    Backend
                    |                           |
                Next.js                  API Gateway
                                                |
                                          Eureka Server
                                                |
                         +----------------------+----------------------+
                         |                      |                      |
                    User Service         Product Service         Order Service
                         |                      |                      |
                      Database              Database               Database
