# Mean Stack



## Overview



The MEAN stack is a full-stack JavaScript framework for building web applications. It consists of:



- **MongoDB**: NoSQL database

- **Express.js**: Web application framework

- **Angular**: Front-end framework

- **Node.js**: JavaScript runtime environment



## Getting Started



### Prerequisites



- Node.js (v14 or higher)

- npm (v6 or higher)

- MongoDB (v4 or higher)

- Angular CLI



### Installation



1. Clone this repository

2. Install server dependencies: `cd server && npm install`

3. Install client dependencies: `cd client && npm install`



### Running the Application



1. Start MongoDB: `mongod`

2. Start the server: `cd server && npm start`

3. Start the client: `cd client && ng serve`



## Project Structure



```

project/

├── client/          # Angular frontend

├── server/          # Express backend

│   ├── models/      # MongoDB models

│   ├── routes/      # API routes

│   └── config/      # Configuration files

└── README.md

```



## API Documentation



The API is available at `http://localhost:3000/api`



## License



MIT

