# Contributing to Green Leaf

Thank you for considering contributing to Green Leaf! This document provides guidelines and information for contributors.

## 🌟 How to Contribute

We welcome all kinds of contributions:
- 🐛 Bug reports and fixes
- ✨ New features and enhancements
- 📚 Documentation improvements
- 🧪 Tests and test improvements
- 💡 Ideas and suggestions

## 🚀 Getting Started

### Prerequisites
- Python 3.8+ installed
- Git installed
- GitHub account

### Setting up the Development Environment

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/yourusername/Green-Leaf.git
   cd Green-Leaf
   ```

3. **Create a virtual environment**:
   ```bash
   python -m venv .venv
   # Activate it
   # Windows:
   .venv\Scripts\activate
   # macOS/Linux:
   source .venv/bin/activate
   ```

4. **Install development dependencies**:
   ```bash
   pip install -r requirements.txt
   pip install -r requirements-dev.txt  # if available
   
   # Or install common development tools:
   pip install pytest ruff black mypy
   ```

5. **Create a new branch** for your feature:
   ```bash
   git checkout -b feature/your-feature-name
   ```

## 📝 Development Workflow

### Making Changes

1. **Write your code** following our style guidelines
2. **Add tests** for new functionality
3. **Update documentation** as needed
4. **Run the test suite**:
   ```bash
   pytest
   ```
5. **Check code formatting**:
   ```bash
   ruff check .
   black --check .
   ```

### Code Style Guidelines

We follow these conventions:
- **PEP 8** for Python code style
- **Black** for code formatting
- **Ruff** for linting
- **Type hints** where appropriate
- **Docstrings** for all public functions and classes

### Running Quality Checks

Before submitting your changes:

```bash
# Format code
black .

# Lint code
ruff check .

# Run tests
pytest

# Type checking (if mypy is installed)
mypy green_leaf/

# Run all checks at once (if you have a Makefile)
make check
```

## 🔧 Pull Request Process

1. **Update documentation** if you've added features
2. **Add tests** for new functionality
3. **Ensure all tests pass**
4. **Update the README.md** if needed
5. **Write a clear PR description** that includes:
   - What changes were made
   - Why the changes were necessary
   - Any breaking changes
   - Screenshots if applicable

### PR Title Format
Use clear, descriptive titles:
- `feat: add new data processing algorithm`
- `fix: resolve memory leak in core module`
- `docs: update installation instructions`
- `test: add unit tests for utils module`

### PR Description Template
```markdown
## Description
Brief description of changes made.

## Type of Change
- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] Documentation update

## Testing
- [ ] I have added tests that prove my fix is effective or that my feature works
- [ ] New and existing unit tests pass locally with my changes

## Checklist
- [ ] My code follows the style guidelines of this project
- [ ] I have performed a self-review of my own code
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] I have made corresponding changes to the documentation
- [ ] My changes generate no new warnings
```

## 🐛 Reporting Bugs

When filing a bug report, please include:

1. **Clear title** and description
2. **Steps to reproduce** the behavior
3. **Expected behavior**
4. **Actual behavior**
5. **Environment information**:
   - Operating system
   - Python version
   - Green Leaf version
   - Any relevant dependencies

### Bug Report Template
```markdown
**Bug Description**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

**Expected Behavior**
A clear and concise description of what you expected to happen.

**Screenshots**
If applicable, add screenshots to help explain your problem.

**Environment**
- OS: [e.g. Windows 10, macOS 12, Ubuntu 20.04]
- Python version: [e.g. 3.9.7]
- Green Leaf version: [e.g. 1.0.0]

**Additional Context**
Add any other context about the problem here.
```

## 💡 Suggesting Features

We love feature suggestions! When suggesting a feature:

1. **Check existing issues** to avoid duplicates
2. **Provide clear use cases** for the feature
3. **Describe the proposed solution**
4. **Consider alternatives** you've thought about
5. **Be open to discussion** and iteration

## 📋 Issue Labels

We use these labels to categorize issues:

- `bug` - Something isn't working
- `enhancement` - New feature or request
- `documentation` - Improvements or additions to documentation
- `good first issue` - Good for newcomers
- `help wanted` - Extra attention is needed
- `question` - Further information is requested

## 🏆 Recognition

Contributors will be recognized in several ways:
- Listed in the project's README
- Mentioned in release notes for significant contributions
- Given credit in commit messages and PR descriptions

## 📞 Getting Help

If you need help:
- 📋 Check existing [GitHub Issues](https://github.com/0PKunal/Green-Leaf/issues)
- 💬 Start a [GitHub Discussion](https://github.com/0PKunal/Green-Leaf/discussions)
- 📧 Create a new issue for support requests

## 📜 Code of Conduct

Please note that this project is released with a [Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project, you agree to abide by its terms.

## 🙏 Thank You

Thank you for taking the time to contribute to Green Leaf! Your contributions help make this project better for everyone.

---

*This contributing guide is adapted from best practices in the open source community. Feel free to suggest improvements!*