# Base image (OS)

FROM openjdk:17-jdk-alpine

# Working directory for the app

WORKDIR /app

# Copy the code from your host to your container (Working dir)

COPY src/Main.java /app/Main.java

COPY quotes.txt quotes.txt

# Run the commands to install libs or to compile code

RUN javac Main.java

# Expose the app

EXPOSE 8000

# Serve the app to keep it running

CMD ["java", "Main"]




