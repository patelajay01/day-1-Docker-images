# Base Image
# Lightweight official Python image
FROM python:3.10

# Set working directory inside container
WORKDIR /app

# Copy only requirements first
COPY requirements.txt .

# Install Python dependencies
RUN pip install  -r requirements.txt

# Copy application source code
COPY . .

# Expose application port
EXPOSE 5000

# Run the application
CMD ["python", "app.py"]
