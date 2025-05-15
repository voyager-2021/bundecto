# bundecto

![PyPI Version](https://img.shields.io/pypi/v/bundecto) ![PyPI - Python Version](https://img.shields.io/pypi/pyversions/bundecto) ![License](https://img.shields.io/pypi/l/bundecto) [![Code Style: Black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black) [![Code Style: isort](https://img.shields.io/badge/code%20style-isort-ef8336.svg)](https://github.com/PyCQA/isort)

**bundecto** is a minimal terminal-based text editor written in Python using `curses`. It aims to provide a distraction-free, keyboard-only editing experience directly in your terminal.

## Features

- Minimal interface with a focus on productivity
- Fully keyboard-driven controls
- Support for scrolling, cursor movement, and text editing
- Quick save to file with Ctrl+S
- Exit with Ctrl+X
- Ctrl+H to show keybind help menu
- Ctrl+G to open debug menu

## Installation

You can install `bundecto` using `pip`:

```bash
pip install bundecto
```

Or install from source:

```bash
git clone https://github.com/voyager-2021/bundecto.git
cd bundecto
pip install .
```

## Usage

Launch the editor from your terminal:

```bash
bund [filename] [-v|-h|-r]
```

If the file exists, it will be loaded. Otherwise, a new buffer is created.

## Development

Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for information on how to contribute to the project.

Clone the repo and install in editable mode:

```bash
git clone https://github.com/voyager-2021/bundecto.git
cd bundecto
pip install -e .
```

## Bug Reporting

If you encounter any bugs, please help us improve **bundecto** by reporting issues on the GitHub repository:

- Check if the issue is already reported before opening a new one.
- Provide clear steps to reproduce the bug.
- Include your operating system, Python version, and terminal emulator details.
- If possible, include error messages or screenshots.
- Use a [issue template](https://github.com/voyager-2021/bundecto/issues/new?template=bug_report.md) to file a bug report.

Report bugs to: [bundecto/issues](https://github.com/voyager-2021/bundecto/issues)

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

Inspired by the elegance of minimal terminal editors like `micro`, `nano`, and `pico`, but aimed to be as simple as possible in pure Python.
