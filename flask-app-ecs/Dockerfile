# Base image (OS)

FROM python:3.7

# Working directory

WORKDIR /app

# Copy src to container 

COPY . .

# Run the build command

RUN pip install -r requirements.txt

# Expose the port 80

EXPOSE 80

# Serve the app or Run the app to keep it running

CMD ["python", "run.py"]



