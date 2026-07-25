# simple-node-app

A minimal Node.js HTTP server with no external dependencies.

## Requirements

- Node.js 18 or newer

## Run

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000). Health check: [http://localhost:3000/health](http://localhost:3000/health).

## Development

Auto-restart on file changes (Node 18+):

```bash
npm run dev
```

## Environment

| Variable | Default | Description        |
| -------- | ------- | ------------------ |
| `PORT`   | `3000`  | HTTP listen port   |
