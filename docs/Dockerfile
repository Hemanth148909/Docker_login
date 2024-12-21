# Use a basic Python image
FROM python:3.9-slim

# Set the working directory inside the container
WORKDIR /app

# Copy your application files (replace with your actual file names)
COPY . /app

# Install any necessary Python dependencies (if you have a requirements.txt)
RUN pip install --no-cache-dir -r requirements.txt

# Command to run your application (replace with your app's entry point)
CMD ["python", "app.py"]
