
# My TypeScript Application

This repository contains a TypeScript application with a CI/CD pipeline configured using GitHub Actions.

## Local Setup

To run this application locally, follow these steps:

1. Install dependencies:
   \`\`\`bash
   npm install
   \`\`\`
2. Build the application:
   \`\`\`bash
   npm run build
   \`\`\`
3. Start the application:
   \`\`\`bash
   npm start
   \`\`\`

## CI/CD Pipeline

The CI/CD pipeline is configured to run on every push to the 'develop' branch and includes steps for installing dependencies, linting, testing, building the application, and building a Docker image.

## Docker

To build and run the Docker container locally:

1. Build the Docker image:
   \`\`\`bash
   docker build -t my-typescript-app .
   \`\`\`
2. Run the container:
   \`\`\`bash
   docker run -p 3000:3000 my-typescript-app
   \`\`\`
