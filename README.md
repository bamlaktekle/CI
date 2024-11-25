# Bank Account Example - Starter Python repo for testing and CI

This Python project is a starter repo that is used for teaching unit testing, code coverage, and CI using a simple `BankAccount` class. The project includes methods for depositing, withdrawing, and transferring funds with basic validation rules. We will implement unit tests using [unittest](https://docs.python.org/3/library/unittest.html), and we will measure code coverage with [coverage](https://coverage.readthedocs.io/en/7.6.4/).

## Prerequisites

- **Python 3.6** or later
- **pip** (Python’s package installer)

## Getting Started

1. **Clone the Repository**: Clone the project to your local machine.
    ```bash
    git clone <repository-url>
    cd <your-project-directory>
    ```

2. **Create a virtual environment and install requirements**:

```
python3 -m venv .venv
source ./.venv/bin/activate
pip install -r requirements.txt
```

3. Run the unit tests

```bash
python -m unittest
```

4. Generate a coverage report

```
coverage run -m unittest
coverage html
```

The first command will generate the coverage report in your terminal. The second will generate an html file in `htmlcov/index.html` which you can view in your browser.

## Tasks

See [tasks](/tasks) folder for the different tasks you can try out with this repo.
