# Reservation System API

This is a reservation system API built using Express.js and Firebase.

## Getting Started

### Installation
You can install the required dependencies using npm. Run the following command:
npm install express firebase firebase-admin body-parser cors nodemon dotenv

### Usage
The API provides endpoints for managing clients and reservations. You can interact with the API using tools like Postman or curl.

Client Endpoints:

POST /api/client: Create a new client.
GET /api/clients: Get a list of all clients.
GET /api/client/:id: Get details of a specific client.
PUT /api/client/:id: Update a client's information.
DELETE /api/client/:id: Delete a client.
Reservation Endpoints:

POST /api/reservation: Create a new reservation.
GET /api/reservations: Get a list of all reservations.
GET /api/reservation/:id: Get details of a specific reservation.
PUT /api/reservation/:id: Update a reservation's information.
DELETE /api/reservation/:id: Delete a reservation.

### Contributing
Contributions are welcome! If you have any improvements or bug fixes, please feel free to open an issue or submit a pull request.