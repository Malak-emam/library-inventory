# Use the official Python image from the Docker Hub
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the requirements.txt file from the library_inventory directory and install the dependencies
COPY library_inventory/requirements.txt requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Install pytest as well
RUN pip install --no-cache-dir pytest

# Copy the rest of the application code from the library_inventory directory to the working directory
COPY library_inventory/ .

# Expose the port the app runs on
EXPOSE 5000

# Set the environment variable for Flask
ENV FLASK_APP=app.py
ENV FLASK_RUN_HOST=0.0.0.0

# Command to run the application by default
CMD ["flask", "run"]

# Optionally, you can add a test command if needed
# ENTRYPOINT ["pytest"]
