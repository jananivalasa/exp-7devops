# Use the official Python image as the base image
FROM python:3.9

# Set the working directory to /app/
WORKDIR /app/

# Copy the Python script into the container's working directory
COPY hello.py /app/

# Run the Python script when the container starts
CMD ["python", "hello.py"]