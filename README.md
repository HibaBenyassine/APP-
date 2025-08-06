# Leave Management Application

This is a web application for managing leave requests, built using Angular for the frontend and Node.js with Express.js for the backend.

## Project Structure

```
leave-management-app
├── backend
│   ├── src
│   │   ├── app.js
│   │   ├── controllers
│   │   │   └── leaveController.js
│   │   ├── routes
│   │   │   └── leaveRoutes.js
│   │   └── models
│   │       └── leave.js
│   ├── package.json
│   └── README.md
├── frontend
│   ├── src
│   │   ├── app
│   │   │   ├── app.component.ts
│   │   │   ├── app.module.ts
│   │   │   └── leave
│   │   │       ├── leave-list.component.ts
│   │   │       └── leave-request.component.ts
│   │   ├── assets
│   │   └── environments
│   │       ├── environment.ts
│   │       └── environment.prod.ts
│   ├── angular.json
│   ├── package.json
│   ├── tsconfig.json
│   └── README.md
└── README.md
```

## Technologies Used

- **Frontend**: Angular
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (assumed)

## Setup Instructions

### Backend

1. Navigate to the `backend` directory.
2. Install dependencies:
   ```
   npm install
   ```
3. Start the server:
   ```
   npm start
   ```

### Frontend

1. Navigate to the `frontend` directory.
2. Install dependencies:
   ```
   npm install
   ```
3. Start the Angular application:
   ```
   ng serve
   ```

## API Endpoints

- `GET /api/leaves` - Retrieve all leave requests
- `POST /api/leaves` - Create a new leave request
- `PUT /api/leaves/:id` - Update an existing leave request
- `DELETE /api/leaves/:id` - Delete a leave request

## Contributing

Feel free to fork the repository and submit pull requests for any improvements or bug fixes.