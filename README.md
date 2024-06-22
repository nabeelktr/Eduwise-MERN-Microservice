# Eduwise

Eduwise is a comprehensive e-learning platform designed to provide advanced video processing, real-time interaction, and a scalable architecture. It integrates AI-driven subtitles, live sessions, microservices, and automated CI/CD for a seamless learning experience.

## Features

- **Transcoding Flexibility**: Converts videos into multiple formats using FFmpeg with HLS for adaptive streaming.
- **AI-Powered Subtitles**: Uses OpenAI Whisper for automatic and accurate subtitle generation.
- **Interactive Live Sessions**: Facilitates real-time broadcasts with chat integration using Socket.IO and Stream SDK.
- **Real-time Feedback & Updates**: Enables course video reviews, comments, and notifications with cron jobs.
- **Microservices Architecture**: Built scalable microservices with RabbitMQ and gRPC for efficient communication.
- **Automated CI/CD**: Streamlined development with GitHub Actions for continuous integration and deployment.
- **Scalable Infrastructure**: Utilizes Docker, EC2, S3, and CloudFront for scalable, secure cloud solutions with Nginx.

## Technologies Used

- **Backend**: MongoDB, Node.js, Express.js, gRPC, RabbitMQ, REST, Cron Jobs
- **Frontend**: Next.js, Tailwind CSS, RTK-Query
- **Video Processing**: FFmpeg, HLS
- **Real-time Communication**: Socket.IO, Stream SDK
- **Cloud Services**: AWS (Route53, EC2, S3, CloudFront)
- **Security**: JWT
- **Deployment**: Docker, Nginx
- **Payment Integration**: Stripe
- **Email Services**: NodeMailer

## Prerequisites

- Node.js >= 14.0.0
- npm >= 6.0.0
- MongoDB
- AWS Account
- Docker

## Getting Started

### Cloning the Repository

```bash
# Clone the repository
git clone https://github.com/your-username/eduwise

# Change directory
cd eduwise

# Install Dependencies
npm install

# Copy .env.example to .env and update it with your specific needs
cp .env.example .env

# Generate App Key (if applicable)
node generateKey.js

# Run Migrations (if applicable)
npm run migrate

# Seed Database (if applicable)
npm run seed

# Serve
npm run dev
