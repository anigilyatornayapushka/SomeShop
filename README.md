# Online Store (Django Backend + Frontend)

A project on the topic of an online store was created as a way to renew knowledge of web development and have fun.
The goal is to create a fully functioning and convenient platform for online buying and selling.

## Planned Functionality

### Authentication and Users
- User-friendly registration
- JWT-authentication
- Password recovery via email
- Change password and user data
- User variations: buyer and seller

### Products and sellings
- View product catalog with filtering
- Search by product
- Shopping cart
- Placing an order
- Order history
- Reviews and product ratings

### Administration
- Admin-panel + API
- Order management
- User management
- Sales analytics

### Additional services
- Notifications
- Recomendations

## Technlogy stack

### Main technologies
- **Backend**: Django + Django REST Framework
- **Frontend**: Django Templates
- **Authentication**: Json Web Tokens
- **Database**: PostgreSQL
- **Message broker**: RabbitMQ
- **Caching**: Redis

## Microservices Architecture Blueprint

There will be several services:
1. **Core Service** - User management
2. **Product Service** - Selling services
3. **Email Service** - Users' email management
5. **Analytics Service** - analytics and recomendations

They connect with each other via Rest API and RabbitMQ

## License

The project is distributed under the license [MIT](LICENSE).

## How lo Launch

Instructions are not ready yet
