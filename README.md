# FastAPI, ML model deployment on AWS

## Project Overview
The project involves the development of a pill-counting application aimed at reducing manual errors and enhancing operational efficiency in pharmaceutical workflows.

## Technologies Used
- **YOLO (You Only Look Once)**: Pre-trained machine learning model for object detection.
- **AWS S3**: Cloud-based image storage solution.
- **FastAPI**: Web framework for building the application interface.
- **Docker**: Containerization for consistent deployment.
- **AWS Elastic Container Registry (ECR)**: Secure storage for Docker images.
- **AWS Lambda**: Serverless compute service for auto-scaling and efficient workload management.

## Key Implementations
1. **Pill-Counting Application**:
   - Utilized a pre-trained YOLO model for precise pill detection and counting.
   - Integrated AWS S3 to store captured images securely.
   - Built a user-friendly web interface using FastAPI for easy interaction with the system.

2. **Efficient Deployment on AWS**:
   - Deployed the application using AWS infrastructure.
   - Leveraged AWS Elastic Container Registry (ECR) to store Docker images securely.
   - Implemented AWS Lambda for auto-scaling on-demand, ensuring smooth handling of traffic spikes and variable workloads.
