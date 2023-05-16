# Flask-Hello-World

Dockerized Python Flask App
This project is a simple Python Flask application that displays the text "Hello, World!". The application is dockerized and can be deployed to Kubernetes.

To run the application locally, you can use the following commands:
  # Clone the repository
  git clone https://github.com/[your-username]/dockerized-flask-app.git

  # Change directory to the project root
  cd dockerized-flask-app

  # Build the Docker image
  docker build -t [your-username]/dockerized-flask-app .

  # Run the Docker image
  docker run -p 5000:5000 [your-username]/dockerized-flask-app
  
The application will now be running on http://localhost:5000. You can access it in your browser.

The application will now be deployed to Kubernetes and can be accessed at http://[kubernetes-cluster-ip]:80.

# Dependencies
The following dependencies are required to run the application:

- Python 3.6 or later
- Flask
# License
This project is licensed under the MIT License.

# Contributing
If you would like to contribute to this project, please follow these steps:

#  Fork the repository.
- Create a branch for your changes.
- Make your changes and commit them.
- Push your changes to your branch.
- Open a pull request.
I look forward to your contributions!

    
