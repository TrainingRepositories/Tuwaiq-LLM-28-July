
# Tuwaiq-LLM-28-July! 🚀

Welcome to the Tuwaiq-LLM-28-July project! This guide will help you set up your environment and run Jupyter Notebook seamlessly.

## Prerequisites

1. **Install Python**

   Ensure that Python is installed on your system. You can install Python using one of the following methods:

   - **Official Website**: [Download Python](https://www.python.org/downloads/)
   - **Homebrew (macOS)**:
     ```bash
     brew install python
     ```
   - **Chocolatey (Windows)**:
     ```bash
     choco install python
     ```

## Setup Instructions

### 1. Create a Virtual Environment

Creating a virtual environment ensures that your project's dependencies are isolated.

```bash
python -m venv .env
```

### 2. Activate the Virtual Environment

#### For macOS and Linux:

```bash
source .env/bin/activate
```

#### For Windows:

```bash
.env\Scripts\activate
```

### 3. Install Required Packages

Ensure that your virtual environment is activated, then install the required packages:

```bash
pip install -r requirements.in
```

## Running Jupyter Notebook

You have two options for running Jupyter Notebook:

### Option 1: Standard Method

1. **Activate the Virtual Environment** (if not already activated):

   ```bash
   source .env/bin/activate  # macOS/Linux
   .env\Scripts\activate     # Windows
   ```

2. **Launch Jupyter Notebook**:

   ```bash
   python -m notebook
   ```

### Option 2: VSCode Integrated Method (Preferred)

This option offers a quicker setup and eliminates the need to manually activate the virtual environment.

#### For macOS:

No additional steps are needed. Simply toggle the 'RUN AND DEBUG' icon in VSCode, then run the Jupyter Notebook.

#### For Windows:

1. Rename the configuration file:

   ```plaintext
   Rename ".vscode/launch-Windows.json" to ".vscode/launch.json"
   ```

2. Delete the old configuration file if necessary.

Once these steps are complete, use the 'RUN AND DEBUG' icon in VSCode to start your Jupyter Notebook.

---

Enjoy your coding journey  Tuwaiq-LLM-28-July! 🚀
