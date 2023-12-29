
# Bonnd

Bonnd application is a social networking app that employs a swiping mechanism to connect users based on their preferences.

## Installation

To run Bonnd you have to start 3 development server

- Frontend
- Backend
- Image Backend

### Frontend

To start Frontend Server run the following commands

```bash
git clone https://github.com/Rcoem-Friends/Frontend.git
cd Frontend
npm install
npm run dev
```


### Backend

Before running the backend server, ensure you have set up the required environment variables. Create a `.env` file in the root of the project with the following contents:

```env
# Example .env file

PORT = <Enter the port>
MONGODB_URL = <Enter your MONGODB_URL>

JWT_ACCESS_KEY = <Put your access key>


NODEMAILER_EMAIL = <Put your email id>
NODEMAILER_PASSWORD = <Put the app password for the email (16 alphabets remove space)>
```

To start Backend Server run the following commands

```bash
git clone https://github.com/Rcoem-Friends/Backend.git
cd Backend
npm install
nodemon app.js
```

### Image Backend

Before running the Image Backend server, ensure you have set up the required environment variables. Create a `.env` file in the root of the project with the following contents:

```env
MONGODB_URI=<Enter your MONGODB_URI>
PORT=<Enter your Port>
```

To start Image Backend Server run the following commands

```bash
git clone https://github.com/Rcoem-Friends/Image_Backend.git
cd Image_Backend
npm install
nodemon index.js
```
