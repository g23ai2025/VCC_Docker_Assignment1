## **Docker_Assignment:**

  Step1 : Deploy a sample web application using docker containers by creating docker images from scratch. Existing docker container images are not allowed.
  Step2 : Create a readme file with full explanation of the process followed, describe the app functionality, include details of author

## **Account Opening Website**
Welcome to the Account Opening Web Application! This application allows users to effortlessly open an account by providing essential details such as their name, phone number, email address, and gender. Below, you'll find comprehensive details and instructions for using this application effectively.
The application is built using Python (Flask framework) and Docker for containerization.

## **Prerequisites:**
Make sure you have the following installed on your system:
  - Docker
  - Python 3.x
  - MongoDB 
  
## Getting Started
**Clone this Repository**
`git clone https://github.com/g23ai2025/VCC_Docker_Assignment1.git`


## Docker Installation
Step 1:**For Docker installation in VM** :

          sudo apt install docker.io
          
          sudo systemctl enable docker
          
          sudo systemctl status docker
          
          sudo systemctl start docker
          
Step 2: **Container creation**:

        sudo docker build -t account_opening .
        
When we run the above command , output will be in the form of an image.

Step 3: **Run the docker image** :

        sudo docker run -p 5000:5000 account_opening
        
Step 4:
      Open the browser and launch the web application using IP address.

## Sample screens

**Screen 1:**



![image](https://github.com/user-attachments/assets/f02f094d-7ac1-498b-aa3e-9d905f10974b)

**Screen 2:**


![image](https://github.com/user-attachments/assets/6fc77523-a02e-425b-8983-c9c2f723b1d7)


## Usage

1. Provide Name , phone, email and gender  in the form and click on submit button.
2. On click of "Submit", employee will be prompted with a message "Thankyou for opening account."

## Author
- [G23AI2025](https://github.com/g23ai2025/VCC_Docker_Assignment1)
  
