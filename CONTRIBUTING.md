# Contributing to bundecto

Thank you for your interest in contributing to **bundecto**! We welcome contributions of all kinds — bug reports, feature requests, documentation improvements, and code enhancements.

## How to Contribute

### 1. Report Bugs

If you find a bug, please:

- Search the [existing issues](https://github.com/voyager-2021/bundecto/issues) to see if it's already reported.
- If not, open a new issue with a [issue template](https://github.com/voyager-2021/bundecto/issues/new?template=bug_report.md)

### 2. Suggest Features

Have an idea to improve bundecto? Open a feature request issue describing:

- The feature and why it's useful
- The reason why it should be included
- How it might be implemented (if you have thoughts)

### 3. Submit Pull Requests

We welcome PRs! To get started:

- Fork the repository and clone your fork
- Create a new branch for your changes
- Make your edits and write clear commit messages
- Ensure your code follows our style and passes checks
- Submit a pull request with a clear description

### 4. Development Setup

To set up bundecto for development:

```bash
git clone https://github.com/voyager-2021/bundecto.git
cd bundecto
pip install -e .
```

Install additional dev tools (optional but recommended):

```bash
pip install mypy black isort
```

### 5. Code Style

We use the following tools:

- `mypy` for static type checking
- `black` for code formatting
- `isort` for sorting imports

Run `black .`, `isort .` and `mypy .` before submitting your pull request.

### 6. Code of Conduct

Please be respectful and inclusive in all interactions.

---

Thank you for helping make **bundecto** better!
