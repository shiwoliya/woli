# woli

This repository contains the `woli` project.

## Getting Started

Clone the repository and create a local environment file:

```powershell
Copy-Item .env.example .env
```

Update `.env` with your local configuration before running the project.

## Project Notes

- Keep secrets in `.env`; do not commit them.
- Use `.env.example` to document required environment variables.
- Keep generated files, caches, and dependency folders out of Git.
