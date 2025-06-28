# Template-Python-CLI

This repository provides a starter template for building Python Command Line Interface (CLI) applications. It's designed to help Tonyc developers quickly set up new CLI projects with a clean structure and essential dependencies.

## Getting Started

To use this template, follow these steps:

1. **Clone the repository (or download the zip):**
   ```bash
   git clone https://github.com/UgoEkwe/Template-Python-CLI.git
   cd Template-Python-CLI
   ```

2. **Install dependencies:**
   It's recommended to use a virtual environment for your project.
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   pip install -r requirements.txt
   ```

3. **Run the example application:**
   The template includes a basic CLI application. You can run it using:
   ```bash
   python cli.py
   ```
   Or, if you want to install it locally as a package (for development):
   ```bash
   pip install -e .
   your_cli_command  # Replace with the entry point defined in setup.py
   ```

## Project Structure

```
Template-Python-CLI/
├── cli.py            # Main entry point for the CLI application
├── setup.py          # Project setup and packaging information
├── requirements.txt  # Project dependencies
├── README.md         # This file
└── ...               # Other project files
```

## Customization

- **Modify `cli.py`**: Add your application's logic and commands here.
- **Update `setup.py`**: Change the project name, version, author, and entry points as needed.
- **Manage Dependencies**: Add or remove packages from `requirements.txt`.

## Contributing

If you have suggestions or improvements for this template, please open an issue or submit a pull request.