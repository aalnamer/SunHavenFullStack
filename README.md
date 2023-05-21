# Sun Haven E-commerce Store

This repository contains the code for the Sun Haven E-commerce Store, which consists of two main components: the `ecommerce-backend` and `ecommerce-frontend`. The backend is built using Node.js, Express.js, and utilizes various tools such as the Stripe API for cart purchases, PostgreSQL (PSQL) for the database, and Render for backend deployment. The frontend is developed using React.js, Redux for state management, and Firebase for frontend deployment.

## Ecommerce Backend

The `ecommerce-backend` folder contains the code and configurations for the backend of the Sun Haven E-commerce Store. It is built using Node.js and Express.js, providing the necessary APIs and server-side functionality. The backend utilizes the following tools and services:

- Node.js: A JavaScript runtime environment used to execute server-side code.
- Express.js: A fast and minimal web application framework for Node.js.
- Stripe API: Used for handling cart purchases and payment processing.
- PostgreSQL (PSQL): A powerful, open-source relational database management system.
- Render: A deployment platform for hosting and scaling backend applications.

To set up the backend locally, follow these steps:

1. Clone the repository: `git clone https://github.com/aalnamer/SunHavenBackend/tree/b2388ef0efe571e36dfbf76f312404b95e819232`
2. Navigate to the `ecommerce-backend` folder: `cd ecommerce-backend`
3. Install dependencies: `npm install`
4. Set up the database: Ensure you have PostgreSQL installed and running. Create a new PostgreSQL database and update the database connection configuration in `config/database.js`.
5. Set up environment variables: Create a `.env` file in the root of the `ecommerce-backend` directory and define the required environment variables. For example:
   ```
   PORT=8080
   STRIPE_SECRET_KEY=your_stripe_secret_key
   DATABASE_URL=your_database_url
   ```
6. Start the server: `npm start`

## Ecommerce Frontend

The `ecommerce-frontend` folder contains the code and configurations for the frontend of the Sun Haven E-commerce Store. It is built using React.js and utilizes Redux for state management. The frontend also integrates with Firebase for deployment. To set up the frontend locally, follow these steps:

1. Navigate to the `ecommerce-frontend` folder: `cd ecommerce-frontend`
2. Install dependencies: `npm install`
3. Set up environment variables: Create a `.env` file in the root of the `ecommerce-frontend` directory and define the required environment variables. For example:
   ```
   REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
   REACT_APP_FIREBASE_PROJECT_ID=your_firebase_project_id
   ```
4. Start the development server: `npm start`

## Deployment

The Sun Haven E-commerce Store can be deployed using the following steps:

### Backend Deployment

The backend can be deployed using Render, a hosting and scaling platform. To deploy the backend:

1. Create an account on Render (https://render.com/) if you don't have one.
2. Create a new web service on Render and link it to your GitHub repository.
3. Configure the necessary environment variables on Render, such as `PORT`, `STRIPE_SECRET_KEY`, and `DATABASE_URL`.
4. Deploy the backend using the Render platform.

### Frontend Deployment

The frontend can be deployed using Firebase hosting. To deploy the frontend:

1. Create a Firebase project (https://firebase.google.com/) if you don't have one.
2. Install the Firebase CLI globally: `npm install -g firebase-tools`
3. Log in to Firebase CLI: `firebase login`
4. Initialize the Firebase project: `firebase init`
   - Select the Firebase features

you want to set up (e.g., hosting).

- Choose the Firebase project you created earlier.
- Set the public directory to the build folder (usually `build/`).
- Configure as a single-page application (SPA) if prompted.
- Deploy the frontend to Firebase hosting: `firebase deploy`

## Contributing

If you would like to contribute to the Sun Haven E-commerce Store, please follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name: `git checkout -b your-branch-name`
3. Make the necessary changes and additions.
4. Test your changes thoroughly.
5. Commit and push your changes to your forked repository.
6. Submit a pull request to the main repository.

## License

The Sun Haven E-commerce Store is released under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as per the terms of the license.

## Contact

If you have any questions, suggestions, or feedback, please contact me at [collaymen.alnamer@gmail.com](mailto:collaymen.alnamer@gmail.com).
