# chatbot-rappi

## Requirements

- Python 3.12

## Setup

**1. Create the virtual environment**

```bash
python3.12 -m venv .venv
```

**2. Activate it**

```bash
source .venv/bin/activate
```

> To deactivate later: `deactivate`

**3. Install dependencies**

```bash
pip install --upgrade pip
pip install -r requirements/dev.txt
```

## Code quality

Run the linter:

```bash
ruff check src/
```

Auto-fix issues:

```bash
ruff check --fix src/
```

Format code:

```bash
ruff format src/
```
