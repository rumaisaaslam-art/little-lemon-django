Little Lemon Restaurant API

API Endpoints:

GET /api/menu/          → List all menu items
POST /api/menu/         → Add a menu item (authenticated)
GET /api/bookings/      → List all bookings (authenticated)
POST /api/bookings/     → Create a new booking (authenticated)

User Authentication:

Register: POST /api/auth/users/
Login: POST /api/auth/token/login/
Logout: POST /api/auth/token/logout/
