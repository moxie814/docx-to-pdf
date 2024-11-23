# DOCX to PDF Converter Web Application

This is a web application that allows users to upload Microsoft Word documents (`.docx`), view file metadata, and download the converted file as a PDF. The project is built using Flask, `python-docx`, and `reportlab`. It is fully dockerized and includes deployment configurations for Kubernetes.

---

## Features

- **File Upload**: Upload `.docx` files through a user-friendly web interface.
- **Metadata Extraction**: View document metadata such as author, title, subject, and word count.
- **DOCX to PDF Conversion**: Convert uploaded Word documents to PDF format.
- **PDF Download**: Download the converted PDF file.
- **Dockerized Deployment**: Easily run the application using Docker.
- **Kubernetes Deployment**: Supports Kubernetes deployment with manifest files for scalability.

---

## Technologies Used

- **Backend**: Flask
- **PDF Conversion**: `reportlab`
- **DOCX Parsing**: `python-docx`
- **Containerization**: Docker and Docker Compose
- **Orchestration**: Kubernetes

---

## Installation and Setup

### Prerequisites
- Python 3.10+
- Docker and Docker Compose
- Git
- Kubernetes (Optional: for deployment)

---

### Clone the Repository
```bash
git clone https://github.com/yourusername/docx-to-pdf.git
cd docx-to-pdf




Here is a sample README.md file for your GitHub repository:


# DOCX to PDF Converter Web Application

This is a web application that allows users to upload Microsoft Word documents (`.docx`), view file metadata, and download the converted file as a PDF. The project is built using Flask, `python-docx`, and `reportlab`. It is fully dockerized and includes deployment configurations for Kubernetes.

---

## Features

- **File Upload**: Upload `.docx` files through a user-friendly web interface.
- **Metadata Extraction**: View document metadata such as author, title, subject, and word count.
- **DOCX to PDF Conversion**: Convert uploaded Word documents to PDF format.
- **PDF Download**: Download the converted PDF file.
- **Dockerized Deployment**: Easily run the application using Docker.
- **Kubernetes Deployment**: Supports Kubernetes deployment with manifest files for scalability.

---

## Technologies Used

- **Backend**: Flask
- **PDF Conversion**: `reportlab`
- **DOCX Parsing**: `python-docx`
- **Containerization**: Docker and Docker Compose
- **Orchestration**: Kubernetes

---

## Installation and Setup

### Prerequisites
- Python 3.10+
- Docker and Docker Compose
- Git
- Kubernetes (Optional: for deployment)

---

### Clone the Repository
```bash
git clone https://github.com/yourusername/docx-to-pdf.git
cd docx-to-pdf
Install Dependencies
Create a virtual environment:


bash

python -m venv venv
source venv/bin/activate    # For Linux/MacOS
venv\Scripts\activate       # For Windows
Install Python dependencies:


bash

pip install -r requirements.txt
Run Locally
Start the Flask server:


bash

python app.py
Open your browser and navigate to http://localhost:5000.

Docker Deployment
Build and Run the Container
Build the Docker image:


bash

docker build -t docx-to-pdf .

Run the container:


bash

docker run -p 5000:5000 docx-to-pdf
Access the application at http://localhost:5000.
Using Docker Compose
Start the application with Docker Compose:


bash

docker-compose up --build
Kubernetes Deployment
Prerequisites
Kubernetes cluster (e.g., Minikube or a cloud provider)
kubectl configured to connect to the cluster
Steps
Apply the deployment and service manifests:
bash
Copy code
kubectl apply -f kubernetes/deployment.yaml
kubectl apply -f kubernetes/service.yaml
Access the application via the service's external IP.
CI/CD with GitHub Actions
This repository includes a GitHub Actions workflow to automate Docker builds and push the image to Docker Hub.

Project Structure
php
Copy code
docx-to-pdf/
├── app.py                 # Main Flask application
├── requirements.txt       # Python dependencies
├── Dockerfile             # Docker image configuration
├── docker-compose.yml     # Docker Compose configuration
├── kubernetes/            # Kubernetes manifests
│   ├── deployment.yaml    # Deployment configuration
│   ├── service.yaml       # Service configuration
├── static/                # Static files (CSS, JavaScript)
└── templates/
    └── index.html         # HTML template for the web UI
Screenshots
Home Page
Upload .docx files and view metadata.

Download PDF
Download the converted PDF file.



Fork the repository.
Create a new branch for your feature/fix.
Commit your changes and push them to your fork.
Submit a pull request.
License
This project is licensed under the MIT License.



markdown
Copy code

### How to Customize:
1. Replace `yourusername` with your GitHub username.
2. Add links or replace placeholders (e.g., screenshots and email).
3. Include additional details if needed.








