## Prerequisites

1. **Python Version**:
   - Ensure you have Python 3.8 or higher installed.

2. **JupyterLab**:
   - Install JupyterLab if not already installed:
     ```bash
     pip install jupyterlab
     ```

3. **LaTeX Distribution**:
   - Install a LaTeX distribution compatible with your operating system. Examples include:
     - **Ubuntu/Debian**: `sudo apt-get install texlive-full`
     - **MacOS**: Install MacTeX from [TUG](https://tug.org/mactex/)
     - **Windows**: Install MikTeX from [MikTeX](https://miktex.org/)

## Setting Up the Environment

1. Clone the repository or download the notebook to your working directory.
2. Create a virtual environment:
   ```bash
   python3 -m venv evaluation_env
   source evaluation_env/bin/activate  # For Linux/MacOS
   evaluation_env\Scripts\activate   # For Windows
   ```
3. Install required dependencies using `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

## Running the Notebook

1. Launch JupyterLab:
   ```bash
   jupyter lab
   ```
2. Open the `Evaluation.ipynb` notebook.
3. Run the cells sequentially to perform the analysis and generate reports.

## Installed Packages

Below is a list of Python packages required for this project:

- `jupyterlab`
- `matplotlib`
- `numpy`
- `pandas`
- `pyarrow`
- `textwrap`

## Troubleshooting

- **LaTeX Errors**:
  - Ensure that your LaTeX distribution is properly installed and accessible via the command line.
  - If compilation fails, check the `.log` files generated in the working directory for error details.

- **FileNotFoundError**:
  - Ensure the required directories exist or let the notebook create them by running the initialization cells.

