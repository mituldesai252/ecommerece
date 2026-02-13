# AWS Ecommerce Project 🛒

## 📌 Project Overview
This project demonstrates how to deploy a simple ecommerce website using AWS EC2 and Docker.

## 🏗 Architecture

User → Internet → EC2 → Docker → Apache → PHP Application

## 📁 Project Structure

/frontend - HTML frontend  
/backend - PHP backend  
/docker - Docker configuration  

## 🚀 Setup Steps

1. Launch EC2 instance
2. Install Docker
3. Build Docker image:
   docker build -t ecommerce-app .
4. Run container:
   docker run -d -p 80:80 ecommerce-app
5. Access using Public IP

## 🛠 Technologies Used
- AWS EC2
- Docker
- Apache
- PHP
