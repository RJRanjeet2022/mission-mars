# Hello World Node.js

A minimal Hello World HTTP server using Node.js.

## Clone 🔁

Clone the repository and change into the project folder:

```bash
git clone <repository-url>
cd hello-world-node
```

> Replace `<repository-url>` with your repository's URL (e.g., `https://github.com/user/repo.git`).

## Install dependencies 📦

This project has no external runtime dependencies, but install scripts from `package.json` if present:

```bash
npm install
```

## Run the application ▶️

Start the server:

```bash
npm start
# or
node index.js
```

Open your browser at: `http://localhost:3000` or use curl:

```bash
curl http://localhost:3000
# Response: Hello, World!
```

If you need to run on a different port, set the `PORT` environment variable before starting:

```bash
# Linux/macOS
PORT=4000 npm start

# Windows (PowerShell)
$env:PORT=4000; npm start
```

## Tests 🧪

No automated tests are included. For a manual check, use `curl` or visit the URL in a browser.

## Troubleshooting ⚠️

- If `npm start` fails, ensure Node.js and npm are installed (`node -v`, `npm -v`).
- If the port is already in use, change the `PORT` environment variable as shown above.

## License-

MIT
