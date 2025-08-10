# API Documentation

## Authentication

All API requests require authentication using Bearer tokens:

```bash
curl -H "Authorization: Bearer your-token" https://api.mycompany.com/v1/users
```

## Endpoints

### Users
- `GET /v1/users` - List all users
- `POST /v1/users` - Create a new user
- `GET /v1/users/{id}` - Get user by ID
- `PUT /v1/users/{id}` - Update user
- `DELETE /v1/users/{id}` - Delete user

### Configuration
- `GET /v1/config` - Get current configuration
- `POST /v1/config` - Update configuration (admin only)

## Rate Limits

- 1000 requests per hour for authenticated users
- 100 requests per hour for unauthenticated requests

Last updated: 2025-08-10T05:25:19.178Z
