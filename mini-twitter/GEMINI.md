# Project Overview

This project is a simple "Mini-Twitter" web application built with React and Vite. It allows users to view a list of posts, see details of a single post with comments, and create new posts and comments. The application is designed to interact with a mock API for data, but the API fetching logic is not yet implemented. This suggests it's likely a coding assignment or workshop.

## Building and Running

### Development Server

To run the development server:

```bash
npm run dev
```

This will start a local server, and you can view the application in your browser at the address provided.

### Building for Production

To build the application for production:

```bash
npm run build
```

This will create a `dist` folder with the optimized production build.

### Linting

To run the linter and check for code quality issues:

```bash
npm run lint
```

## Development Conventions

The project uses standard React conventions and functional components with hooks. The code is organized into components, and API interactions are separated into an `api.js` file. The API functions in `src/api/api.js` are currently placeholders and need to be implemented to fetch data from the mock server.
