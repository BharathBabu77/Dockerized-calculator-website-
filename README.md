# Dockerized-calculator-website-

Title: Simple Calculator Website Dockerized

Description:
This project demonstrates the creation of a simple static website featuring a basic calculator interface. The website is Dockerized for easy deployment. Follow the steps below to set up and run the project.

Project Structure:
Directory Structure
 
  simple-calculator-website/
  ├── Dockerfile
  ├── index.html
 

Instructions

1. **Clone the Repository:**
  
   git clone https://github.com/your-username/simple-calculator-website.git
   cd simple-calculator-website
   ```

2. **Create a Docker Image:**
  
   docker build -t simple-calculator-website .
   ```

3. **Run the Docker Container:**
  
   docker run -d -p 8080:80 simple-calculator-website
   ```

4. **Access the Website:**
   Open your web browser and visit [http://localhost:8080](http://localhost:8080) to view the simple calculator website.

**Project Contents:**

- **Dockerfile:**
  ```
  # Use a base image
  FROM nginx:latest
  
  # Copy the website content to the container
  COPY index.html /usr/share/nginx/html
  ```

- **index.html:**
  ```html
  <!--HTML, CSS, and JavaScript code for the simple calculator -->
  ```

