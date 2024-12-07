# Use the official OpenJDK image
FROM openjdk:11-jdk-slim

# Set the working directory inside the container
WORKDIR /usr/src/app

# Copy the Java application code into the container
COPY HelloWorld.java .

# Compile the Java application
RUN javac HelloWorld.java

# Run the Java application
CMD ["java", "HelloWorld"]
