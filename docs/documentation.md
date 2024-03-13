# iNotebook App Documentation

## Project Architecture

The iNotebook app follows a client-server architecture using the MERN stack (MongoDB, Express.js, React.js, Node.js). The frontend is built with React.js, and the backend is built with Node.js and Express.js. MongoDB is used as the database to store notes.


## File Structure

iNotebook-app/
│
├── client/ # Frontend React app
│ ├── public/
│ ├── src/
│ │ ├── components/ # React components
│ │ ├── pages/ # React pages (Home, About)
│ │ ├── App.js # Main component
│ │ └── ...
│ ├── package.json
│ └── ...
│
├── server/ # Backend Node.js/Express app
│ ├── controllers/ # Route controllers
│ ├── models/ # MongoDB models
│ ├── routes/ # API routes
│ ├── app.js # Express app setup
│ └── ...
│
├── docs/ # Documentation
│ └── documentation.md # Project documentation
│
├── package.json # Main project configuration
└── ...


## Important Design Decisions

- **Authentication:** User authentication is implemented using JWT (JSON Web Tokens) to secure user login and sign up processes.
- **State Management:** Redux is used for state management in the frontend to manage notes and user authentication state.
- **Database:** MongoDB is used as the database to store notes due to its flexibility and scalability.

## Contributing

Contributions to the iNotebook app are welcome! To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them to your branch.
4. Push your branch to your fork.
5. Create a pull request (PR) against the main repository's `develop` branch.

Please adhere to the following coding standards and guidelines:

- Follow the Airbnb JavaScript style guide (https://github.com/airbnb/javascript).
- Write clear and concise commit messages.
- Test your changes thoroughly before submitting a PR.

## Getting Started

To run the iNotebook app locally, follow these steps:

1. Clone the repository.
2. Navigate to the `client` directory and run `npm install` to install frontend dependencies.
3. Navigate to the `server` directory and run `npm install` to install backend dependencies.
4.  Run `npm start` in the `client` directory to start the frontend server.
5.  Run `npm start` in the `server` directory to start the backend server.

The app should now be running locally on `http://localhost:3000`.

