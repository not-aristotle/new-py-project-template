# Contributing

1. Clone the project into your workspace.
2. Create virtual environment if not created: `python -m ven venv`.
3. Activate virtual environment: `source venv/bin/activate`.
4. Install dependencies: `pip install -r requirements.txt`.
5. Run `pre-commit install`.
6. Create new bug/feature branch.

Other important steps include:
- Updating [CHANGELOG.md](./CHANGELOG.md).
- Updating relevant `version.py` file(s) (could be multiple files for different
  interfaces such as CLI and REST API).
- Implementing test cases for new features and ensuring previous bugs are
  caught during testing.
