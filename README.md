# EEG Signal Processing and Visualization Using Python

## Setup Instructions (using `uv`)

This project uses [uv](https://github.com/astral-sh/uv) for fast Python package management.

### Prerequisites

- Python 3.10 or newer
- [uv](https://github.com/astral-sh/uv) installed (`pip install uv`)

### Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/Istiaq-Fuad/EEG-Signal-Processing-and-Visualization-Using-Python.git
   cd EEG-Signal-Processing-and-Visualization-Using-Python
   ```

2. **Sync dependencies with uv:**

   ```sh
   uv sync
   ```

   This will create a virtual environment (if not present) and install all dependencies from `pyproject.toml` and `uv.lock`.

3. **Activate the virtual environment:**

   ```sh
   source .venv/bin/activate
   ```

4. **Run the notebook:**
   Open `Preprocessing-Single-subject-Data.ipynb` in VS Code or Jupyter and execute the cells.

### Data

Sample EEG data will be downloaded automatically when running the notebook.
