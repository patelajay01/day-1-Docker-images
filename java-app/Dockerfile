# Base Image
# Official OpenJDK image
FROM openjdk:17-slim

# Set working directory
WORKDIR /app

# Copy Java source code
COPY . .

# Compile Java program
RUN javac app.java

# Run Java application
CMD ["java", "app"]
