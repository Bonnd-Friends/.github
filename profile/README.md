# Bonnd - Friends Social Media Application

Welcome to Bonnd, a social media application designed to connect friends and foster meaningful connections. Bonnd is built using the MERN stack (MongoDB, Express.js, React.js, and Node.js) and is organized into three separate repositories: Backend, Image Backend, and Frontend.
## System Design
![image](https://github.com/Rcoem-Friends/.github/assets/97899868/a4931fa5-452b-486a-a118-f571a4700597)

## Schema Tables
![image](https://github.com/Rcoem-Friends/.github/assets/97899868/bc3be2f9-c807-464c-97b7-5d05b76f2c2f)

## Flow of the Project

```mermaid
graph TD
  A(Homepage) --> B(Login)
  B -->|Login with Email| C(Login Options)
  B -->|Login with OTP| C(Login Options)
  C -->|Register| D(Registration)
  C -->|Successful Login| E(Main App Feed)
  E -->|Explore| F(Explore Page)
  E -->|View Profile| G(Profile Page)
  E -->|View Matches| H(Matches Page)
  G -->|Edit Profile| I(Edit Profile)
  G -->|Logout| J(Logout)
```

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


## Flow of the Project

### 1. Homepage

- The journey begins on the Homepage, where users can explore and learn more about Bonnd.
<img src="https://github.com/Rcoem-Friends/.github/assets/97899868/cdd3cfdb-b02b-4eba-aac9-6347dca94327" width="200" height="400"/>
<img src="https://github.com/Rcoem-Friends/.github/assets/97899868/528df546-705e-44ad-b0d9-866740d2a742" alt="Homepage" width="200" height="400"/>



### 2. Login

- Users can click on the "Login" button to access the login page.
  
<img src="https://github.com/Rcoem-Friends/.github/assets/97899868/4af63be7-5a4d-4d41-987e-aa40591d68b8" alt="Login" width="200" height="400"/>



### 3. Login Options

- The login page provides two options: "Login with Email" and "Login with OTP."
- Users can choose the preferred login method.

<img src="https://github.com/Rcoem-Friends/.github/assets/97899868/3af6ccdb-ce84-4889-9d7a-a5cbec6ab9dc" alt="Login with Email" width="200" height="400"/>
<img src="https://github.com/Rcoem-Friends/.github/assets/97899868/6fa5a966-1ced-4c03-96a7-5eb2c77740b7" alt="Login with OTP" width="200" height="400"/>
<img src="https://github.com/Rcoem-Friends/.github/assets/101471692/58b89b40-559b-4213-8803-f1ce1fc56ae9)" alt="Login with OTP With OTP" width="200" height="400"/>



### 4. Registration

- Users without an account can click on the "Register" link to create a new account.
<img src="https://github.com/Rcoem-Friends/.github/assets/97899868/e669e509-28e1-4a65-a518-f159470a274e" alt="Registration" width="200" height="400"/>


### 5. Main App Feed

- After successful login or registration, users are redirected to the main app feed page.
- The feed page showcases updates and activities from connected friends.
<img src="https://github.com/Rcoem-Friends/.github/assets/97899868/d5a61d1c-d905-4907-98a3-0918ceb395ef" alt="Explore" width="200" height="400"/>


### 6. Profile Page

- Users can navigate to the "Profile" page to view and edit their profile details.

<img src="https://github.com/Rcoem-Friends/.github/assets/97899868/937cc19f-878a-4e9b-acb8-7cd941a6aa16" alt="Profile" width="200" height="400"/>



### 7. Matches Page

- The "Matches" page displays potential connections and mutual matches.

<img src="https://github.com/Rcoem-Friends/.github/assets/97899868/fca85132-e422-498d-80c0-969e66ff8afe" alt="Matches" width="200" height="400"/>



### 8. Edit Profile

- Users can edit their profile by clicking on the "Edit Profile" option.

<img src="https://github.com/Rcoem-Friends/.github/assets/97899868/ce6a7131-614c-41f8-8aff-19c5fed26b1f" alt="Edit Profile" width="200" height="400"/>



### 9. Unknown Page

- Users can securely log out from the application.

<img src="https://github.com/Rcoem-Friends/.github/assets/97899868/89336cec-384d-4f29-83b6-fe3cb4a8b697" alt="404 Page" width="200" height="400"/>



## Setup

Follow the setup instructions in the previous section to get started with the Bonnd application.

## Contributing

We welcome contributions from the community. If you find a bug or have a suggestion, please open an issue. For code contributions, fork the repository, create a branch, and submit a pull request.

Happy connecting! 🌐🚀

