# Contributing to JARVIS-X

Thank you for your interest in contributing to JARVIS-X! This document provides guidelines and instructions for contributing.

## Getting Started

1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR_USERNAME/JARVIS-X.git`
3. Create a feature branch: `git checkout -b feature/your-feature-name`
4. Make your changes
5. Push to your fork: `git push origin feature/your-feature-name`
6. Open a Pull Request

## Code Style

### Kotlin
- Follow [Kotlin conventions](https://kotlinlang.org/docs/coding-conventions.html)
- Use 4 spaces for indentation
- Use camelCase for variables and functions
- Use PascalCase for classes
- Add kdoc comments for public APIs

### Python
- Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/)
- Use 4 spaces for indentation
- Use snake_case for variables and functions
- Use PascalCase for classes
- Add docstrings for functions and classes

## Commit Messages

Use clear, descriptive commit messages:
```
feature: Add voice interruption support
fix: Resolve memory leak in voice engine
docs: Update installation guide
refactor: Simplify AutomationEngine code
test: Add unit tests for CommandParser
```

## Pull Request Process

1. Update README.md with any new features
2. Add tests for new functionality
3. Ensure all tests pass locally
4. Update documentation as needed
5. Link any related issues

## Testing

Run tests before submitting:

```bash
# Android
cd android
./gradlew test

# Python
cd backend
python -m pytest tests/
```

## Reporting Issues

Include:
- Clear description of the issue
- Steps to reproduce
- Expected vs actual behavior
- Device/environment information
- Relevant logs

## Feature Requests

Describe:
- Use case
- Proposed solution
- Alternatives considered
- Potential impact

## Code of Conduct

- Be respectful and inclusive
- No harassment or discrimination
- Constructive feedback only
- Respect privacy and security

## Questions?

Open an issue or start a discussion in the GitHub repository.

Thanks for contributing! 🚀
