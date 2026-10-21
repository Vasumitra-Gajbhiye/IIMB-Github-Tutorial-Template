# [Project name]

**Team [number]:** [one-line description of what you're building]

## Team

See the [`members/`](members/) folder.

## Getting started

**On your laptop (VS Code):**

1. Clone this repo in VS Code: `Ctrl/Cmd + Shift + P` → **Git: Clone** → **Clone from GitHub**.
2. In the VS Code terminal, install the project's packages:

   ```
   uv sync
   ```

3. `Ctrl/Cmd + Shift + P` → **Python: Select Interpreter** → pick the `.venv` one.
4. Check it runs:

   ```
   uv run main.py
   ```

**In a Codespace:** on this page, **Code** → **Codespaces** → **Create codespace on main**.
Everything installs automatically. When it opens, run `uv run main.py` to check.

## Adding a package

```
uv add package-name
```

Then commit the changed `pyproject.toml` and `uv.lock`, so teammates get it with `uv sync`.

## How we work

*(Your team fills this in during the lecture.)*
