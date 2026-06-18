# Data Flow Diagrams

## Authentication
User -> [HTTPS Request] -> API Gateway -> Auth Service -> JWT Token -> User| [Validates credentials] | User Store (DB)

All data in transit is encrypted using TLS 1.2+.
All tokens expire after 24 hours and must be refreshed.
