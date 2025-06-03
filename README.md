# portfolio-react-backend

This repository contains the backend API for my personal portfolio website, built with Node.js, Express, and MongoDB. It handles contact form submissions and sends notification emails.

## Project Overview

The backend API provides endpoints to:

- Receive and save contact form messages to MongoDB  
- Send email notifications when a new message is received  
- Handle CORS for frontend requests
- Deployed on Render

## Technologies Used

- Node.js  
- Express.js  
- MongoDB with Mongoose  
- Nodemailer for sending emails  
- dotenv for environment variable management  
- cors middleware  

## Getting Started

### Prerequisites

- Node.js and npm installed  
- MongoDB Atlas cluster (or local MongoDB)  
- Gmail account for sending emails (or SMTP credentials)

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/portfolio-react-backend.git
   cd portfolio-react-backend
