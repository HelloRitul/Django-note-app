# Deploying Django Apps by Nginx in AWS
# Introduction

Once we have completed the development part of a web app it should be hosted so that the public can access it from anywhere. We will see how to deploy and host a django application on AWS EC2 instance using Nginx as the webserver.
# AWS EC2

Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides resizable compute capacity in the cloud. We deploy and host our web apps on EC2 instance.
# NGINX

Nginx is an open-source web server that, since its success as a web server, is now also used as a reverse proxy , HTTP cache, and load balancer. We will use Nginx to server our webpages as needed .

![ng1](https://user-images.githubusercontent.com/69754757/227113445-5e5472eb-c63b-431a-97b2-faaa17917410.png)

![ng2](https://user-images.githubusercontent.com/69754757/227113523-88a754df-16b2-4ef4-a12a-b3e9f87b97ce.png)

# Prerequisites and Steps:
-> A Free Tier AWS Account

-> Create an EC2 Instance

-> Login To Instance

-> Config ubuntu server

->Install Nginx

->Install Docker

To start with AWS, you can create an AWS account to enjoy some free tier products that include the server on that we will deploy the Django project on. AWS likes to call these servers EC2 instances.

# 1. Create an EC2 Instance :
After Login AWS Free Tier(root), we gonna create EC2 Instance which is similar to a private ubuntu server/system. On the console click >> Services

https://docs.google.com/document/d/e/2PACX-1vTao6wjeWXaZItrLvN3vqMzBAzSs23CcaPHjeG4jknazXAS4cAByra7J-QIBFL9gab7deOZB1ZMG9sY/pub
