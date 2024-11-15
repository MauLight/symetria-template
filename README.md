# SYMETRIA boilerplate (React + Router + Tailwind)

This boilerplate offers a starting point for Symetria projects.

How to use:

1. Run `npm i`
2. Run `npm run dev` (default port= 3000)

**Important:**
Formatting should be handled by eslint, please add this settings to your VS Code settings JSON file:

> "eslint.format.enable": true,
> "editor.codeActionsOnSave": {
> "source.addMissingImports.ts": "explicit",
> "source.fixAll.eslint": "always"
> },
> "eslint.validate": ["javascript"],

(\*) To change port go to vite.config.ts and specify a new port under server/port.
