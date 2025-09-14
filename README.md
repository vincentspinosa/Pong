# Transcendence

A TypeScript-based Pong game with a Fastify HTTPS backend for secure frontend serving.

## 🎮 Frontend

The frontend is a TypeScript Pong game built with:
- TypeScript
- Webpack
- Tailwind CSS
- HTML5 Canvas

## 🔒 Backend

A Fastify-based HTTPS server that serves the frontend with:
- HTTPS-only connections
- Static file serving
- CORS support
- Health monitoring
- SPA routing support

## 🚀 Start the project

To start the project, go to the root of the project and run:

make

This command will:
1. Check prerequisites (Docker, Docker Compose)
2. Build the Front-End
3. Build the Docker container
4. Start the application

## 🌐 Access

Once running, access your application at:
- **Frontend**: https://localhost:3000
- **Health Check**: https://localhost:3000/health

## ⚠️ SSL Certificate Warning

During development, you'll see a browser security warning due to self-signed certificates. This is normal and expected. To proceed:

1. Click "Advanced" in the warning
2. Click "Proceed to localhost (unsafe)"
3. Your game will load securely over HTTPS

