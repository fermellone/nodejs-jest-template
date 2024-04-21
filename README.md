# My Node Server

This is a Node.js server built with TypeScript.

## Project Structure

```
my-node-server
├── src
│   ├── server.ts
│   ├── controllers
│   │   └── index.ts
│   ├── routes
│   │   └── index.ts
│   └── types
│       └── index.ts
├── package.json
├── tsconfig.json
└── README.md
```

## Installation

1. Clone the repository.
2. Navigate to the project directory.
3. Run `npm install` to install the dependencies.

## Usage

1. Run `npm start` to start the server.
2. Open your browser and visit `http://localhost:3000` to access the server.

## Server Configuration

The server configuration can be found in the `src/server.ts` file. It sets up the server instance, middleware, and routes.

## Controllers

The controllers handle the logic for different routes. The `IndexController` in `src/controllers/index.ts` exports a method `getIndex` that handles the root route of the server.

## Routes

The routes are defined in the `src/routes/index.ts` file. The `setRoutes` function exports the routes and uses the `IndexController` to handle the root route.

## Types

The `src/types/index.ts` file exports interfaces `Request` and `Response` which extend the interfaces from the `express` library.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).