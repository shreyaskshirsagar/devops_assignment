# Using python runtime lightweight version
FROM python:3.10-slim

# Set the working directory
WORKDIR /app

# Copy local files to the container
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

COPY . .

# Make port 5000 available to outside this container
EXPOSE 5000

# Run the application
CMD ["python", "app.py"]
