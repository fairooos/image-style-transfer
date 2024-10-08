# Image Style Transfer

This project implements an image style transfer application using a neural network model. It consists of a web frontend built with Svelte and a backend API powered by FastAPI and Celery.

## Prerequisites

- Docker
- Docker Compose

## Getting Started

1. Clone the repository:
   ```
   git clone <repository-url>
   cd image-style-transfer
   ```

2. Build and start the Docker containers:
   ```
   docker-compose up --build
   ```

3. Access the web application:
   Open your browser and navigate to `http://localhost:3000`

## Usage

1. Upload a content image and a style image using the provided input fields.
2. Click the "Generate" button to start the style transfer process.
3. Monitor the progress bar to track the generation process.
4. Once complete, the generated image will be displayed.
5. Use the "Download" button to save the generated image.

## Technologies Used

- Frontend: Svelte, TypeScript, Tailwind CSS, Skeleton UI
- Backend: FastAPI, Celery, Redis
- Machine Learning: PyTorch, torchvision