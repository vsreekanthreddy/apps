# Use the official Python base image
FROM python:3.9-slim

# Set working directory inside container
WORKDIR /app

# Copy files to container
COPY . .

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Expose the app port
EXPOSE 5000

# Command to run the app
CMD ["python", "app.py"]
#docker build -t my-python-app .
#docker run -p 5000:5000 my-python-app
