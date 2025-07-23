# Contributing to 25x Agentic Calls

Thank you for your interest in contributing to 25x Agentic Calls! We welcome contributions from everyone.

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- Git
- A GitHub account

### Setting Up Your Development Environment

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/25x-agentic-calls.git
   cd 25x-agentic-calls
   ```
3. **Create a virtual environment** (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
4. **Create a new branch** for your feature:
   ```bash
   git checkout -b feature/your-feature-name
   ```

## 📝 How to Contribute

### Types of Contributions

We welcome several types of contributions:

- **Bug fixes**
- **Feature enhancements**
- **Documentation improvements**
- **Performance optimizations**
- **Test coverage improvements**
- **Code quality improvements**

### Pull Request Process

1. **Make your changes** in your feature branch
2. **Test your changes** thoroughly
3. **Update documentation** if necessary
4. **Commit your changes** with a clear commit message:
   ```bash
   git commit -m "feat: add user authentication system"
   ```
5. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Create a Pull Request** on GitHub

### Commit Message Guidelines

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

- `feat:` for new features
- `fix:` for bug fixes
- `docs:` for documentation changes
- `style:` for formatting changes
- `refactor:` for code refactoring
- `test:` for adding tests
- `chore:` for maintenance tasks

Examples:
```
feat: add interactive task scheduler
fix: resolve user input validation issue
docs: update installation instructions
```

## 🧪 Testing

Before submitting a pull request:

1. **Test your changes** manually:
   ```bash
   python userinput.py
   ```
2. **Verify the interactive loop** works correctly
3. **Test edge cases** and error conditions
4. **Check that the exit condition** (`stop` command) works

## 📋 Code Style Guidelines

### Python Style

- Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/) guidelines
- Use meaningful variable and function names
- Add docstrings for functions and classes
- Keep functions small and focused
- Use type hints where appropriate

### Example:

```python
def process_user_input(user_input: str) -> bool:
    """
    Process user input and determine if the loop should continue.
    
    Args:
        user_input (str): The input provided by the user
        
    Returns:
        bool: True if the loop should continue, False if it should stop
    """
    if user_input.lower().strip() == "stop":
        return False
    return True
```

### Documentation Style

- Use clear, concise language
- Provide examples where helpful
- Update README.md for significant changes
- Add inline comments for complex logic

## 🐛 Reporting Bugs

When reporting bugs, please include:

1. **Description** of the bug
2. **Steps to reproduce** the issue
3. **Expected behavior**
4. **Actual behavior**
5. **System information** (OS, Python version)
6. **Error messages** (if any)

Use our [issue template](.github/ISSUE_TEMPLATE/bug_report.md) when available.

## 💡 Suggesting Features

When suggesting new features:

1. **Check existing issues** to avoid duplicates
2. **Describe the feature** clearly
3. **Explain the use case** and benefits
4. **Consider implementation** complexity
5. **Provide examples** if possible

## 📚 Documentation

Help improve our documentation by:

- **Fixing typos** and grammatical errors
- **Adding examples** and use cases
- **Improving clarity** of instructions
- **Adding missing information**
- **Translating** to other languages

## 🏷 Issue Labels

We use the following labels to categorize issues:

- `bug`: Something isn't working
- `enhancement`: New feature or request
- `documentation`: Improvements to documentation
- `good first issue`: Good for newcomers
- `help wanted`: Extra attention is needed
- `priority: high`: High priority issues
- `priority: low`: Low priority issues

## 🎉 Recognition

Contributors will be:

- **Listed** in the README.md acknowledgments
- **Credited** in release notes for significant contributions
- **Invited** to join the core team for consistent contributors

## ❓ Questions

If you have questions about contributing:

1. **Check** the existing documentation
2. **Search** existing issues and discussions
3. **Ask** in [GitHub Discussions](https://github.com/devvrat-hans/25x-agentic-calls/discussions)
4. **Contact** the maintainers directly

## 📞 Contact

- **GitHub Issues**: For bug reports and feature requests
- **GitHub Discussions**: For questions and general discussion
- **Email**: devvrat.hans@example.com (for sensitive matters)

Thank you for contributing to 25x Agentic Calls! 🚀
