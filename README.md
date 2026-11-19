# MachineLearningForSignalProcessing
My code repository for Machine Learning for Signal Processing

## Setup

This project uses [uv](https://docs.astral.sh/uv/) for Python and dependency management.

```bash
uv sync                 # creates .venv with Python 3.12 and installs everything from uv.lock
uv add <package>        # add a new dependency (instead of pip install)
uv run python file.py   # run a script inside the environment
```

In VS Code, open `CheatSheet.ipynb` and select the `.venv` kernel.
