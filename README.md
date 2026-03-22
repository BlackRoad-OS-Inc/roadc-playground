# RoadC Playground

Browser-based REPL for the RoadC programming language. Write code, run it, see output — no install needed.

## What It Does

An interactive web editor where you write RoadC code and execute it instantly. Syntax highlighting, 7 built-in examples (one per sentence pattern), and clear error messages.

## Features

- **Live editor** — write RoadC with syntax highlighting
- **Instant execution** — run in your browser, see output immediately
- **7 examples** — one for each English sentence pattern (SV through SVOC)
- **Error feedback** — clear messages when something goes wrong
- **No install** — runs entirely in the browser

## Built-in Examples

| # | Pattern | Demonstrates |
|---|---------|-------------|
| 1 | SV | Basic output (`show "hello"`) |
| 2 | SVC | Variables and assignment |
| 3 | SVA | Adverbial operations |
| 4 | SVO | Object manipulation |
| 5 | SVOO | Dual-object operations |
| 6 | SVOA | Object-adverbial patterns |
| 7 | SVOC | Object-complement transforms |

## Stack

- **Frontend**: HTML/CSS/JS with CodeMirror editor
- **Backend**: FastAPI (Python)
- **Execution**: RoadC interpreter in a sandboxed environment
- **Highlighting**: Custom RoadC grammar definition

## Run Locally

```bash
pip install -r requirements.txt
python server.py
# Open http://localhost:8000
```

## Deploy

```bash
npm install
npm run deploy     # Deploy to production
```

## How It Works

1. You write RoadC code in the browser editor
2. Code is sent to the FastAPI backend
3. The RoadC interpreter executes it in a sandbox
4. Output streams back to the browser

Pairs with [RoadC](https://github.com/BlackRoad-OS-Inc/roadc) — the language specification, compiler, and interpreter.

## License

Proprietary. Copyright (c) 2024-2026 BlackRoad OS, Inc. All rights reserved.

---

*Remember the Road. Pave Tomorrow.*
