# Documenting Project Features and Functionalities

Backend development involves creating of server-side logic, database management and API integration that powers a web application.

[Feature Foundations](https://drive.google.com/file/d/1kpyz7KFWNWrclAtOr9W5mDqk3JcmmpZ2/view?usp=drive_link)

Project requirements
The Airbnb-Clone project is categorized into 3 main functionalities.

1. Core Functionalities
2. Technical functionalities
3. Non-functional functionalities

## Core Functionalities

### User Management

1. User registration - Sign in/up & secure authentication methods.
2. User login and Authentication - (email & password login, OAuth options).
3. Profile management - profile updates, eg photo & cotntacts

### Property Listings Management

1. Add Listings - (Host can creat property listings i.e **attributes**)
2. Edit/Delete Listings - Hsost can update or remove property listings.

### Search and Filtering

Implement search functionalities do users can find properties by attributes (Location, Price range, Number of guest). Also, include pagination

### Booking Management

1. Booking Creation
2. Booking cancellation
3. Booking status

### Payment Integration

1. Implement secure payment gateways (upfront payment and automated payout after successful booking)
2. Support for multiple currencies

### Reviews and ratings

1. Guests can review and rate properties
2. Host can respond to reviews
3. Ensure reviews are linked to bookings to prevent abuse

### Notification System

1. Implement email and in-app notification (for Booking confirmations, cancellations and Payments).

### Admin dashboard

1. Create and admin interface for monitoring Users, Listings, Bookings, Payments.

## Technical Requirements

### Database Management

1. Relational database (PostgreSQL or MySQL).
2. Tables - Users (host and guest), Properties, Bookings, Payments, Reviews.

### API Development

1. RESTFUL APIs (GET, POST, PUT/PATCH, DELETE)
2. GrapghQL - complex data fetching scenearios

### Authentication and Authorization

1. JWT  - Secure user authentication
2. RBAC - Role Based Access Control (Host, guest, admins).

### File Storage (Scenario based)

1. User profile photos and property images are stored in cloud stoage solutions eg AWS. Implement using **file storage**.

### Third-Party Services

1. Email notifications - eg SendGrid or Mailgun

### Error Handling and Logging.

1. Global error handling for APIs

## Non Functional Requirements

### Scalability

1. Modular architecture, ensuring app scales easily with inceased traffic
2. Horizontal scaling using load balancers.

### Security

1. Encrypt sensitive data (password, payment info)
2. Firewalls and rate limiting to prevent threats

### Performance Optimization

1. Caching tools (Redis) to improve responses for frequently accessed data
Optimize database queries to reduce server load.

### Testing

1. Unit and integration tests (pytest).
2. Automated API testing for ensured endpoints functionalities
