# Docker-Node-html_HelloWorld
Hello World page using a docker configuration and node backend


tested on xubuntu - 27/02/2024


Put your index.html file in the same directory as your server.js file with the content you want to display (e.g., "Hello, World!").

To build and run the Docker container:

Save both the Dockerfile, server.js, and index.html in the same directory.
Open a terminal or command prompt.
Navigate to the directory containing your files.
Run docker build -t my-node-app . to build the Docker image.
Run docker run -p 3000:3000 my-node-app to start a container based on the image you just built.
visit http://localhost:3000 in your web browser, and you should see your "Hello, World!" 



to stop:

docker ps

docker stop id


