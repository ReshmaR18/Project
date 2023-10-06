# Use a base image suitable for your Java application on Windows
FROM openjdk:11-windowsservercore

# Create a directory to store the agent JAR file
RUN mkdir C:\springblog\datadog

# Copy the dd-java-agent.jar file into the container
COPY dd-java-agent.jar C:\springblog\datadog\dd-java-agent.jar

# Set environment variables if needed
# ENV YOUR_ENV_VARIABLE=value

# Define the entry point for your application
CMD ["java", "-jar", "C:\\springblog\\datadog\\dd-java-agent.jar"]
