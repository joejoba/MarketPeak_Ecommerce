# CAPSTONE PROJECT - INTRODUCTION TO CLOUD COMPUTING

# MarketPeak_Ecommerce

This project exhibited basic knowledge of cloud computing(AWS), with an e-commerce website deployed on EC2.
A dummy template consisting of HTML, CSS and Javascript was used for development and Git for version control. Below are the steps I took:

## STEP 1: Git Initialisation

Using the terminal, I created a directory on my local machine termed "MarketPeak_Ecommerce". 
Navigated to the folder, initialised git for version control as seen in the image below.

![alt text](<images/Screenshot 2025-01-11 at 16.25.31.png>)

## STEP 2: Website Template and Version Control

I downloaded a dummy template to populate as the structure of the ecommerce website, which was staged and pushed onto a repository on Github. 
I launched an EC2 instance on Amazon Linux AMI, connected to this instance via SSH for administration. 
In order to clone the github repository onto the AWS instance, I had to authenticate with Github via SSH using `ssh-keygen`command to generate a keypair as seen in the image below.

![alt text](<images/Screenshot 2025-01-13 at 00.12.32.png>)

The newly generated SSH key is added to my Github account for authentication and access. With this step completed, I was able to clone the github repository URL on the instance.

![alt text](<images/Screenshot 2025-01-13 at 00.31.57.png>)

## STEP 3: Web Server Installation

To display the website content over the internet, I installed Apache(httpd) web server on the ec2 instance to host the website. Altered the httpd default web directory to serve the MarketPeak Ecommerce website content.
Below is the deployed website accessible on the web browser.

![alt text](<images/Screenshot 2025-01-13 at 00.54.23.png>)