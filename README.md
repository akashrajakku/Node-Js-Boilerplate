# Node.js Boilerplate

This is a base Node.js project template designed to help developers quickly set up and maintain a well-structured application. The template follows best coding practices and project management recommendations, ensuring clean and maintainable code.

## Project Structure

```
/project-root
  ├── src/
  │   ├── config/
  │   ├── routes/
  │   ├── middlewares/
  │   ├── controllers/
  │   ├── repo/
  │   ├── services/
  │   ├── utils/
  ├── .env
  ├── .gitignore
  ├── package.json
  ├── README.md
  ├── server.js
```

### Inside `src/` Folder

- **`config/`**: Contains all configurations and setup of libraries or modules. For example:

  - Setting up `dotenv` for environment variables.
  - Configuring a logging library.
  - Defining `server-config.js`.

- **`routes/`**: Registers application routes and connects them to controllers and middleware.

- **`middlewares/`**: Holds middleware functions to process requests before reaching controllers. Examples:

  - Request validation.
  - Authentication and authorization.

- **`controllers/`**: The entry point for incoming API requests. Controllers handle request processing and pass the data to the business logic layer.

- **`repo/`**: Handles database interactions, including raw queries or ORM-based queries.

- **`services/`**: Contains business logic and interacts with repositories for data retrieval and processing.

- **`utils/`**: Holds utility functions, helper methods, and custom error classes.

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:

- Node.js (latest LTS recommended)
- npm or yarn

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/akashrajakku/Node-Js-Boilerplate
   cd Node-Js-Boilerplate
   ```

2. Install dependencies:

   ```sh
   npm install
   ```

3. Set up environment variables:

   - Create a `.env` file in the root directory.
   - Add necessary variables (refer to `server-config.js` for required configurations).

4. Start the server:

   ```sh
   npm run start
   ```

### Running in Development Mode

Use Nodemon for live reloading:

```sh
npm run dev
```

## Contribution

Feel free to modify and enhance this boilerplate to fit your project needs. Contributions are welcome!

