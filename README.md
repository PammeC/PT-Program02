# PT-Program02


# Simple Express.js Web Server

This is a simple web server built using the Express.js framework. When the server is started, it opens a web browser window and displays the message "¡Hello world, this is a JavaScript program :D !" on the page.

## Prerequisites

- Node.js (version 16 or higher)
- npm (Node Package Manager)

## Getting Started

1. Clone the repository:

   ```
   git clone https://github.com/your-username/your-repository.git
   ```

2. Change to the project directory:

   ```
   cd your-repository
   ```

3. Install the dependencies:

   ```
   npm install
   ```

4. Start the server:

   ```
   npm start
   ```

   This will start the server and automatically open a web browser window at `http://localhost:4000`.

## Running with Docker

Alternatively, you can run the application using Docker:

1. Build the Docker image:

   ```
   docker build -t my-express-app .
   ```

2. Run the Docker container:

   ```
   docker run -p 4000:4000 my-express-app
   ```

   This will start the container and map port 4000 of the container to port 4000 of the host machine. You can then access the application at `http://localhost:4000`.

### Deployment on different platforms

You can deploy this application on several hosting platforms, such as:

- Heroku
- Digital Ocean
- Railway
- Vercel
- Laravel Cloud
- Render

The application is currently deployed on Render and can be accessed at the following link:

[https://pt-program01.onrender.com](https://pt-program01.onrender.com)

## Files

- `Program04.mjs`: The main application file that sets up the Express.js server and opens the web browser window.
- `package.json`: The project's package file that lists the dependencies and scripts.
- `package-lock.json`: The automatically generated file that locks the dependency versions.
- `Dockerfile`: The Docker configuration file that builds the Docker image for the application.

