# IBM Tools for Data Science Coursework

This repository preserves Jupyter notebooks created for IBM data-science coursework and peer-review assignments in 2023. It is a **learning/coursework archive**, not a production data-science package, reusable library or maintained application.

## Repository contents

| Notebook | Purpose |
|---|---|
| [`DataScienceEcosystem.ipynb`](DataScienceEcosystem.ipynb) | Introductory notebook covering common data-science languages, libraries and tools, plus simple Python arithmetic/Markdown exercises. |
| [`Final Assignment (1).ipynb`](Final%20Assignment%20%281%29.ipynb) | Larger final-assignment notebook preserved in its submitted coursework form. |

`DataScienceEcosystem.ipynb` includes the exercise prompts as well as the completed Markdown/code cells, so some text is intentionally instructional rather than polished reference documentation.

## Viewing the notebooks

GitHub can render `.ipynb` files directly in the browser. For interactive execution, open the repository in a Jupyter-compatible environment such as JupyterLab, Jupyter Notebook or VS Code with the Jupyter extension.

A minimal local setup is:

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install jupyter
jupyter lab
```

Additional packages may be required by an individual notebook. Install only the dependencies needed by that notebook rather than treating this repository as a single packaged Python project.

## Historical status

- The default branch is `ArchMain` and is retained as the coursework history.
- Notebook outputs and package/runtime metadata reflect the environment used when the assignments were completed; they should not be read as current recommendations for data-science tooling.
- File names and notebook structure are preserved to avoid changing the submitted artifacts unnecessarily.

## Maintenance policy

This repository should receive only light documentation or preservation fixes unless the coursework itself needs to be revisited. New production analytics, reusable notebooks or maintained Python code should live in a separate project with explicit dependencies, tests and its own lifecycle documentation.
