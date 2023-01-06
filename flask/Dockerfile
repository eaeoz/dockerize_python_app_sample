# Use the Python3.7.2 container image, check your version with 'python --version' command
FROM python:3.10.7

# Set the working directory to /app
WORKDIR /app

# Copy the current directory contents into the container at /app
ADD . /app

# Install the dependencies
RUN pip install -r requirements.txt

#run the command to start uWSGI
CMD ["uwsgi", "app.ini"]
