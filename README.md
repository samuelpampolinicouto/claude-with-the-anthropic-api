# Project Overview

This project will be used for study Claude API

# Setup

- Project clean initialization
    `uv init --bare`
- Install the dependencies
    `uv add --dev ipykernel jupyter`

[Documentation](https://docs.astral.sh/uv/guides/integration/jupyter/#installing-packages-without-a-kernel) for more details.

# Source

All the code for these exercises will live in the `src` directory. You can create as many files as you like in there, and they will be automatically included in the project.

# Run the project

It is important to run at least once the command: `%pip install anthropic python-dotenv` to install the dependencies in the Jupyter Notebook environment.
This command is present on this first Notebook: `src/01-setup.ipynb`

## Executing Jupyter Notebook
To run the project, you can use the following command:

```bash
uv run jupyter notebook
```

or run the jupyter lab

```bash
uv run jupyter lab
```

This will start a Jupyter Notebook server, and you can open your browser to `http://localhost:8888` to access it. You can create new notebooks and start coding!

## Visual Studio Adhoc execution

You can execute on Visual Studio directly on the notebook, or you can run the notebook from the terminal using the command above.