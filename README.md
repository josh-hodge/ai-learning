# AI Learning Monorepo

This repository is organized as a monorepo using npm workspaces. Each AI project lives in its own directory under `projects/`.

## Projects

- **cat-chat**: The first AI project, containing the initial codebase.

## Structure

```
ai-learning/
  projects/
    cat-chat/
      package.json
      package-lock.json
      server.js
      public/
        index.html
      README.md
  README.md (this file)
```

## Getting Started

1. Navigate to the project you want to work on, e.g. `projects/cat-chat`.
2. Install dependencies from the root with:
   ```sh
   npm install
   ```
3. Run project-specific scripts from the project directory.

---

Add new projects under `projects/` as needed.
