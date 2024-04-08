# Project Name

JV Mart is an e-commerce platform where users can buy and sell products. This project is built using the MERN stack (MongoDB, Express.js, React.js, Node.js).

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/yourproject.git
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

## Usage

1. Create a `.env` file in the root directory and define the MongoDB URI:

   ```plaintext
   MONGODB_URI=your_mongodb_uri
   ```

2. Start the development server:

   ```bash
   npm run dev
   ```

3. Access the application:

`  
    - command line: `npm run dev`
   - Backend APIs: `http://localhost:PORT`
   - Frontend (React): `http://localhost:3000`

## Project Structure

```
.
├── config
│   └── db.js
├── controllers
│   ├── categoryController.js
│   ├── productController.js
│   └── userController.js
├── helpers
│   └── passwordHelpers.js
├── middleware
│   └── authMiddleware.js
├── models
│   ├── Category.js
│   ├── Product.js
│   └── User.js
├── routes
│   ├── categoryRoutes.js
│   ├── productRoutes.js
│   └── userRoutes.js
├── .env
├── package.json
├── server.js
└── frontend
    ├── public
    └── src
```

## Technologies Used

- Node.js
- Express.js
- MongoDB (mongoose)
- React.js
- Bootstrap (for frontend UI)

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/new-feature`).
6. Create a new Pull Request.

