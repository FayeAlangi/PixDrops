# PixDrops

PixDrops is a fullstack social media web application, built using the MERN stack (MongoDB, Express.js, React, Node.js). This README provides an overview of the app's features, setup instructions, usage guidelines, and a video walkthrough of the app.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Running the Application](#running-the-application)
- [Usage](#usage)
- [Video Walkthrough](#videowalkthrough)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Registration/ Profile Creation**: Users can create an account by providing a unique username, email, password, personal information and a profile picture.
- **User Login**: Registered users can log in to their account using their username and password.
- **Post Pictures**: Users can upload and share pictures on their profile and feed.
- **Add/Remove Friends**: Users can add/remove friends by clicking the add/remove icon next to the users.
- **Feed**: Users can view a feed of pictures posted by their friends.
- **View Profile**: Users can click on their widget to see the profile info.

## Technologies Used

- **Frontend**
  - [Material UI](https://mui.com/material-ui/getting-started/overview/)
  - [Redux Toolkit](https://redux-toolkit.js.org/introduction/getting-started)
  - [React Router](https://reactrouter.com/en/v6.3.0/getting-started/overview)
  - [Redux Persist](https://github.com/rt2zz/redux-persist)
  - [React Dropzone](https://react-dropzone.js.org/)
  - [Google Fonts](https://fonts.google.com/)
  - [Formik](https://formik.org/docs/overview)
  - [Yup](https://github.com/jquense/yup)
  - [VSCode](https://code.visualstudio.com/download)
- **Backend**
  - [Node.js](https://nodejs.org/en/download/)
  - [Nodemon](https://github.com/remy/nodemon)
  - [Dotenv](https://github.com/motdotla/dotenv)
  - [MongoDB](https://www.mongodb.com/)
  - [Mongoose](https://github.com/Automattic/mongoose)
  - [JsonWebToken](https://github.com/auth0/node-jsonwebtoken)
  - [Multer](https://github.com/expressjs/multer)
  - [GridFS-Storage](https://github.com/devconcept/multer-gridfs-storage)
  - [Postman](https://www.postman.com/)

## Getting Started

### Prerequisites

Make sure you have the following installed on your system:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) account and cluster

### Running the Application

1. Clone the repository
   ```sh
   git clone https://github.com/FayeAlangi/PixDrops.git
   ```
2. Navigate to the project directory
   ```sh
   cd PixDrops
   ```
3. Install server dependencies
   ```sh
   cd server
   npm install
   ```
4. Install client dependencies
   ```sh
   cd ../client
   npm install
   ```
5. Set up environment variables

   - Create a `.env` file in the `backend` directory with the following contents:

   ```.env

   MONGO_URL=your_mongodb_uri
   PORT = 3001
   JWT_SECRET=<your secret token>
   ```

6. Start the development server
   ```sh
   cd ../server
   npm start
   ```
7. Start the application
   ```sh
   cd ../client
   npm start
   ```

## Usage

1. Frontend: `http://localhost:3000`
2. Backend API: `http://localhost:30001`

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src="Walkthrough.gif" width=400><br>

GIF created with LICEcap.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a pull request

## License

Copyright 2024 Faye Alangi

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
