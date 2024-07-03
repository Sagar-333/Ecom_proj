# Project Name

## Overview

This project is a full-stack application built with Node.js, Express, MongoDB, and React. It utilizes several npm packages for various functionalities such as authentication, file uploads, and state management. Tailwind CSS is used for styling the frontend.

## Prerequisites

Make sure you have Node.js and npm installed on your machine.

## Installation

1. **Initialize Backend:**

    ```bash
    npm init -y
    ```

2. **Install Backend Dependencies:**

    ```bash
    npm i nodemon multer mongoose jsonwebtoken express-formidable express-async-handler express dotenv cors cookie-parser concurrently bcryptjs
    ```

3. **Navigate to Frontend Directory:**

    ```bash
    cd frontend
    ```

4. **Initialize Frontend:**

    ```bash
    npm i
    ```

5. **Install Frontend Dependencies:**

    ```bash
    npm i slick-carousel react-slick react-toastify react-router react-router-dom react-redux react-icons apexcharts react-apexcharts moment axios @reduxjs/toolkit @paypal/react-paypal-js
    ```

6. **Install Tailwind CSS:**

    ```bash
    npm install -D tailwindcss
    ```

## Configuration

1. **Update `package.json` Scripts:**

    In the root folder's `package.json` file, update the `scripts` section to:

    ```json
    "scripts": {
        "backend": "nodemon backend/index.js",
        "frontend": "npm run dev --prefix frontend",
        "dev": "concurrently \"npm run frontend\" \"npm run backend\""
    }
    ```

2. **Create/Update `.env` File:**

    Ensure you have a `.env` file in the root directory with the necessary environment variables.

## Running the Application

1. **Start Backend:**

    ```bash
    npm run backend
    ```

2. **Start Frontend:**

    ```bash
    npm run frontend
    ```

3. **Development Mode:**

    To run both backend and frontend concurrently:

    ```bash
    npm run dev
    ```

## License

This project is licensed under the MIT License.

## Acknowledgments

- Thanks to all the contributors and package maintainers.
