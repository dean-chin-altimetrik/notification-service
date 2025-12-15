# Notification Service

A microservice for sending notifications to customers via various channels.

## Features

- Email notifications
- SMS notifications
- Push notifications
- Notification templates
- Delivery tracking

## API Endpoints

- `POST /notifications/send` - Send a notification
- `GET /notifications/{id}` - Get notification status
- `GET /notifications` - List notifications
- `POST /notifications/templates` - Create notification template

## Technology Stack

- Python 3.9+
- FastAPI
- Redis
- SMTP/SMS gateways



