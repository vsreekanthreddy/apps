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
