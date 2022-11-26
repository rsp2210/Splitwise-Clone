# splitwiseClone

## Overview

Welcome to the splitwiseClone repository! This project aims to replicate several features of the original application while maintaining a polished and user-friendly experience.

## Features

The application encompasses the following key features, mirroring those found in the original platform:

- User Registration: New users can seamlessly sign up using a unique email address.
- User Authentication: Existing users can securely log in using their registered email and password.
- Thoughtful Validations: Comprehensive validations have been implemented to ensure data integrity.
- Dashboard Insights: Upon successful login, users are greeted with an intuitive dashboard presenting owed and owing amounts, as well as a list of relevant users.
- Group Dynamics: Users can explore and interact with groups they are part of or invited to, including accepting or rejecting invitations.
- Streamlined Navigation: Group homepages are easily accessible, and recent activities across user groups are conveniently viewable.
- Seamless Settlements: Users can efficiently settle debts with fellow users, whether owed or owing.
- Profile Customization: A user-friendly profile page offers options to edit personal details.
- Collaborative Comments: Group members can add and manage comments on shared bills, with comment deletion limited to the original contributor.

## Technologies Utilized

The splitwiseClone project leverages a powerful technology stack to deliver a sophisticated user experience. The technologies employed include:

- Frontend: React.js and Redux
- Backend: Node.js, GraphQL, MongoDB, and Kafka
- Testing: Mocha
- Authentication: Passport.js

## Deployment Steps

Follow these steps to deploy the application successfully:

### Front End

1. Clone the "client" folder from this repository to a machine with Node.js installed.
2. Open the terminal in the "client" folder.
3. Run `npm install` to install the required dependencies.
4. Update the `Config.js` file located in `client/src` with the backend server's IP address and port.
5. Execute `npm start` to initiate the front-end server.

### Backend

1. Clone the "server" folder from this repository to a machine with Node.js installed.
2. Open the terminal in the "server" folder.
3. Run `npm install` to install the necessary dependencies.
4. Update the `index.js` file within the server folder with the IP address and port of the frontend server.
5. Run `node index` to launch the backend server.

## Application Launch

To access the application, open a web browser and navigate to the IP address of the front-end server along with the designated port number (e.g., `127.0.0.1:3000`).

Thank you for your interest in splitwiseClone! I hope you enjoy using this meticulously crafted platform.