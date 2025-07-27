# Git Statistics

A Python package for generating Git repository statistics and reports.  This project provides tools to analyze Git repositories, extract commit data, and generate various statistics and reports.

## Features

- Analyze commit history
- Generate commit statistics
- Visualize repository activity

## Getting Started

### 1. Clone the repository

```sh
git clone https://github.com/Steve0verton/git-stats.git
cd git-stats
```

### 2. Set up the Python environment

It is recommended to use a virtual environment:

```sh
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install all required dependencies

```sh
pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Run Jupyter Notebooks

To launch the Jupyter Notebook interface and run notebooks in the `notebooks/` directory:

```sh
jupyter notebook
```

Open the desired notebook file from the browser interface and run the cells.

#### Optional: Running Notebooks in Visual Studio Code

Jupyter notebooks can also be run directly within VS Code:

- Open the project folder in VS Code.
- Install the "Jupyter" extension if prompted.
- Open any `.ipynb` file.
- Select the Python interpreter from the command palette if needed, use the .venv/ directory that was setup previously.
- Run and edit notebook cells interactively within the editor.

## Contributing

Contributions are encouraged. Please review the `CONTRIBUTING.md` file for guidelines on coding standards, commit message conventions, and pull request requirements.

## License

This project is licensed under the Apache 2.0 License. See the `LICENSE` file for details.
