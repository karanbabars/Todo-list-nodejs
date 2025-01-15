# Todo-list-nodejs
containerize an application
mkdir folder
cd folder
git clone url
cd TOdo-list-nodejs

used to build a Docker image from a Dockerfile and assign it a name (getting-started).
docker build -t getting-started .

running 
docker run -d -p 127.0.0.1:3000:3000 getting-started

** Dockerfile creates a lightweight container for a Node.js application that:**

1. Uses the stable Node.js version on Alpine Linux.
2. Copies the application files into the container.
3. Installs production dependencies.
4. Runs the app using node src/index.js.
5. Exposes port 3000 for external access.
