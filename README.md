# apps
🧪 Example 1: Dockerfile for a Simple Python App
app/
├── app.py
├── requirements.txt
└── Dockerfile
**Build & Run**
docker build -t my-python-app .
docker run -p 5000:5000 my-python-app
===========🛠 Example 2: Dockerfile for a Node.js App=======
node-app/
├── index.js
├── package.json
└── Dockerfile
**Build & Run**
docker build -t node-docker-app .
docker run -p 3000:3000 node-docker-app
===============================================================
FROM	      Specifies base image
LABEL	      Adds metadata
WORKDIR	    Sets working directory
COPY	      Copies files into image
ADD	        Like COPY but can unpack archives
RUN	        Runs a command at build time
CMD	        Default command when container runs
EXPOSE	    Exposes a port
ENV	        Set environment variables
ENTRYPOINT	Sets a fixed command (used with CMD)
