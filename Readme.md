# Excalidraw Clone

An open-source, collaborative whiteboarding tool inspired by Excalidraw.

## Features

- Freehand drawing and shapes
- Multi-user real-time collaboration
- Export drawings as PNG/SVG
- Undo/Redo functionality
- Keyboard shortcuts
- Dark mode support

## Tech Stack

| Technology   | Purpose                 |
| ------------ | ----------------------- |
| React.js     | Frontend framework      |
| React Konva  | Canvas rendering        |
| Zustand      | State management        |
| WebRTC/Yjs   | Real-time collaboration |
| Tailwind CSS | Styling                 |
| Node.js      | Backend server          |
| Express.js   | API handling            |
| PostgreSQL   | Database                |
| Prisma       | ORM for database        |
| Socket.io    | Real-time communication |

## Folder Structure

```
excalidraw-clone/
├── public/                # Static assets
├── src/
│   ├── components/        # Reusable UI components
│   │   ├── Toolbar.tsx    # Drawing tools
│   │   ├── Sidebar.tsx    # Shape selection
│   │   ├── Canvas.tsx     # Drawing area
│   │   ├── Export.tsx     # Export functionality
│   │   ├── Settings.tsx   # Dark mode, preferences
│   ├── hooks/             # Custom React hooks
│   ├── pages/             # React Router pages (if using React Router)
│   │   ├── Home.tsx       # Home page
│   ├── store/             # Zustand state management
│   ├── utils/             # Helper functions
│   ├── server/            # Backend API and WebSocket
│   │   ├── index.ts       # Express server setup
│   │   ├── db.ts          # Prisma database connection
│   │   ├── socket.ts      # Socket.io real-time logic
├── prisma/                # Prisma schema and migrations
├── .env                   # Environment variables
├── package.json           # Dependencies
├── README.md              # Documentation
├── vite.config.ts         # Vite config (if using Vite instead of CRA)
```

## Getting Started

### Prerequisites

- Node.js (>=16)
- PostgreSQL

### Installation

```sh
git clone https://github.com/GSingh2432002/excalidraw-clone.git
cd excalidraw-clone
npm install
```

### Running the Development Server

```sh
npm run dev
```

### Setting Up the Database

```sh
npx prisma migrate dev
```

## Contribution

Feel free to open issues and PRs to improve the project!
