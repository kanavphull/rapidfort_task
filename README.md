# File Upload App Documentation

This documentation provides an overview of the File Upload App, explaining its functionality and how to run it using Docker.

### Table of Contents
- Introduction
- Functionality
- Running the App
- Prerequisites
- Building and Running with Docker
- Using the App
- Troubleshooting
- Conclusion
### Introduction
The File Upload App is a simple web application built using Flask, a Python web framework. It allows users to upload files to the server and view details about the uploaded files, including their size and extension. The app consists of a backend written in Python and a frontend built with HTML and JavaScript.

### Running the App
##### Prerequisites

Before running the app, ensure you have the following installed:
- Docker

##### Building and Running with Docker

-Build the Docker image using the following command:
```
docker build -t file-upload-app .
```

Replace file-upload-app with the desired image name.
- Run the Docker container using the following command:
```
docker run -p 5000:80 file-upload-app
```

This maps port 5000 on your local machine to port 80 on the container.
### Using the App
Open a web browser and go to http://localhost:5000/.
You'll see a page with a file upload form. Choose a file.
After uploading, the app will display the file details, including the filename, size, and extension, on the same page.
