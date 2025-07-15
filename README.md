# Connect Chat App

A simple real-time chat application built with Node.js, Express, and Socket.io. Users can send and receive messages instantly in a shared chat room via a web interface.

## Features

- Real-time messaging using WebSockets (Socket.io)
- Minimal, clean frontend interface
- Easy to run locally

## Prerequisites

- [Node.js](https://nodejs.org/) (v12 or higher recommended)
- [npm](https://www.npmjs.com/)

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Connect_chat.git
   cd Connect_chat
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the development server:**
   ```bash
   npm run dev
   ```
   This uses `nodemon` for automatic restarts on file changes.

   Or, to run without `nodemon`:
   ```bash
   npm run serve
   ```

4. **Open your browser and visit:**
   ```
   http://localhost:8000
   ```

## Project Structure

```
Connect_chat/
  ├── index.html
  ├── server.js
  ├── package.json
  ├── public/
  │   ├── client.js
  │   ├── style.css
  │   └── connect.png
  └── ...
```

- `server.js`: Main server file (Express + Socket.io)
- `index.html`: Main HTML file served at root
- `public/`: Static assets (JS, CSS, images)

## Customization

- To change the port, set the `PORT` environment variable before running the server:
  ```bash
  PORT=3000 npm run dev
  ```


