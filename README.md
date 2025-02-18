# React + Vite CI/CD

This project demonstrates how to implement Continuous Integration (CI) and Continuous Deployment (CD) for a React-based application using Vite.

## Project Overview

- **Framework:** React + Vite
- **Hosting:** AWS S3 (for static site storage)
- **Compute:** AWS EC2 (t3.medium, 20GB SSD storage) for running CI/CD pipeline
- **Version Control:** Git & GitLab CI/CD

## Features

- **Fast Development:** Uses Vite for quick build times.
- **Automated Deployment:** Jenkins CI/CD pipeline for automatic builds and deployment to AWS S3.
- **Scalable Hosting:** S3 for static file storage ensures high availability.

## Prerequisites

- AWS account with access to S3 and EC2.
- Git and Jenkins CI/CD setup.
- Node.js and npm installed on the development machine.

## Setup & Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/deepanshub9/reactjs-app.git

   cd reactjs-app
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm run dev
   ```
4. Build the project:
   ```sh
   npm run build
   ```

## Deployment Workflow

1. **Commit changes** to the Github repository.
2. **Jenkins CI/CD pipeline** triggers:
   - Runs tests and builds the project.
   - Deploys the static files to AWS S3.
3. **Application is live** on S3 with automatic updates.

## Future Enhancements

- Add AWS CloudFront for CDN caching.
- Implement monitoring with AWS CloudWatch.
- Use Terraform for automated infrastructure provisioning.

## Any Questions

- **Deepanshu** - deepanshub.096@gmail.com
