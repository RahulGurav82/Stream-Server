# Stream-Server

A Node.js server that receives screen captures from clients and provides MJPEG streams.

## Setup

1. Install dependencies:
```bash
npm install
```

2. Start the server:
```bash
npm start
```

## Features

- TCP server on port 4000 for receiving screen captures
- MJPEG stream available at `http://localhost:8080/stream/{labId}/{pcNumber}`
- Automatic creation of screenshots directory
- Real-time screen capture updates
