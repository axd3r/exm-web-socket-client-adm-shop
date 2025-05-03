# WebSocket Chat Client – Admin Shop Demo

This is a simple WebSocket client demo built with **TypeScript**, **Vite**, and **Socket.IO**. It connects to a Socket.IO server and enables real-time messaging and client status updates. It's intended as a front-end companion for learning or testing WebSocket communication.

## 🚀 Features

- Connect to a WebSocket server using a JWT
- Real-time client list updates
- Send and receive chat messages instantly
- Shows online/offline server status

## 📦 Technologies

- [Vite](https://vitejs.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Socket.IO Client](https://socket.io/)

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/axd3r/exm-web-socket-client-adm-shop.git

# Navigate into the project directory
cd exm-web-socket-client-adm-shop.git

# Install dependencies
pnpm install
```

## ▶️ Running the Project

```bash
# Start the development server
pnpm run dev
```

Then open your browser at `http://localhost:5173` (or the port Vite assigns).

## 📋 Usage

1. Enter a valid **JWT** in the input field.
2. Click the **Connect** button to establish a WebSocket connection.
3. The **Server Status** will update to "connected" or "disconnected".
4. The list of connected clients will appear in real time.
5. Use the input at the bottom to send a chat message to the server.

## 📂 Project Structure

```
├── index.html
├── src/
│   ├── main.ts         # Entry point, sets up the UI and events
│   ├── socket-client.ts# Handles WebSocket connection and listeners
│   └── style.css       # Basic styling
├── package.json
├── tsconfig.json
└── vite.config.ts
```

## 🔗 Server
You’ll need a compatible Socket.IO server running on `http://localhost:3000` with a namespace (`/`) and support for JWT-based authentication via headers.
```bash
# Clone the repository
git clone https://github.com/axd3r/adm-shop.git

# Install dependencies
pnpm install
```

## ▶️ Running the Server backend

```bash
# Start the development server
pnpm run start:dev
```

If you need more info, use this URL: https://github.com/axd3r/adm-shop 