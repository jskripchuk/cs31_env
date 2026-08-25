# CS-31 — Foundations for Artificial Intelligence

Tufts University · Fall 2026 · Course environment and weekly labs.

## Students

Read **[SETUP.md](SETUP.md)** and follow it before the Week 1 lab. It takes about 20 minutes.

Short version, once you have [uv](https://docs.astral.sh/uv/) installed:

```bash
cd cs31
uv sync --compile-bytecode
```

Then open the folder in VS Code and run `labs/setup_test/check_env.ipynb`.

## What is in here

```
cs31/
├── SETUP.md              ← start here
├── pyproject.toml        ← the list of libraries this course uses — do not touch
├── uv.lock               ← exact versions, so the whole class matches — do not touch
├── requirements.txt      ← same thing in pip format, for backup use — do not touch
├── .python-version       ← the Python version the course uses (3.13) — do not touch
├── .vscode/              ← editor settings, applied automatically — do not touch
└── labs/                 ← weekly lab notebooks
    └── setup_test/
        ├── check_env.ipynb  ← run this to confirm your setup works
        └── test.txt
```

Do not edit `pyproject.toml`, `uv.lock`, `requirements.txt`, `.python-version`, or `.vscode/`. These are automatically generated.
