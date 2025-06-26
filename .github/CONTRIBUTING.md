# Contributing to Usama Sarwar's Projects 🚀

Thank you for your interest in contributing! This document provides guidelines and information for
contributing to any of my open-source projects.

## 🌟 Welcome Contributors

I welcome contributions from developers of all skill levels! Whether you're fixing a typo, adding a
feature, or improving documentation, your contribution is valuable.

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [How to Contribute](#how-to-contribute)
- [Development Setup](#development-setup)
- [Pull Request Process](#pull-request-process)
- [Coding Standards](#coding-standards)
- [Community](#community)

## 📜 Code of Conduct

This project and everyone participating in it is governed by our
[Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## 🚀 Getting Started

### Prerequisites

- Git installed on your machine
- Relevant development tools (Flutter SDK, Node.js, etc.) depending on the project
- A GitHub account

### First Time Setup

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/REPOSITORY_NAME.git
   cd REPOSITORY_NAME
   ```
3. **Add the original repository** as an upstream remote:
   ```bash
   git remote add upstream https://github.com/UsamaSarwar/REPOSITORY_NAME.git
   ```

## 🤝 How to Contribute

### Reporting Bugs 🐛

1. Check if the bug has already been reported in [Issues](../../issues)
2. If not, create a new issue using the bug report template
3. Provide detailed information including:
   - Clear description of the problem
   - Steps to reproduce
   - Expected vs actual behavior
   - Screenshots (if applicable)
   - Environment details

### Suggesting Features ✨

1. Check if the feature has already been requested
2. Create a new issue using the feature request template
3. Describe the feature, its benefits, and potential implementation approach

### Documentation Improvements 📚

- Fix typos, grammar, or unclear explanations
- Add missing documentation
- Improve code examples
- Translate documentation (if applicable)

### Code Contributions 💻

1. **Pick an issue** to work on (look for "good first issue" or "help wanted" labels)
2. **Comment on the issue** to let others know you're working on it
3. **Create a feature branch** from the main branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Make your changes** following the coding standards
5. **Test your changes** thoroughly
6. **Commit your changes** with clear, descriptive messages
7. **Push to your fork** and submit a pull request

## ⚙️ Development Setup

### For Flutter Projects

```bash
# Install Flutter dependencies
flutter pub get

# Run the app
flutter run

# Run tests
flutter test
```

### For Web Projects

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Run tests
npm test
```

### For PHP Projects

```bash
# Install dependencies
composer install

# Set up environment
cp .env.example .env

# Run local server
php -S localhost:8000
```

## 🔄 Pull Request Process

1. **Ensure your code follows** the project's coding standards
2. **Update documentation** if you've made changes to functionality
3. **Add or update tests** for your changes
4. **Make sure all tests pass**
5. **Update the README.md** if needed
6. **Submit your pull request** with:
   - Clear title and description
   - Reference to related issues
   - Screenshots (for UI changes)
   - Testing instructions

### Pull Request Template

```markdown
## Description

Brief description of changes made.

## Type of Change

- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Performance improvement
- [ ] Other (please describe)

## How Has This Been Tested?

Describe the tests you ran and how to reproduce them.

## Screenshots (if applicable)

Add screenshots for UI changes.

## Checklist

- [ ] My code follows the project's style guidelines
- [ ] I have performed a self-review of my code
- [ ] I have commented my code where necessary
- [ ] I have made corresponding changes to documentation
- [ ] My changes generate no new warnings
- [ ] I have added tests that prove my fix/feature works
- [ ] New and existing tests pass locally
```

## 📏 Coding Standards

### General Guidelines

- Write clean, readable, and maintainable code
- Follow language-specific best practices
- Use meaningful variable and function names
- Add comments for complex logic
- Keep functions small and focused

### Flutter/Dart Projects

- Follow [Dart Style Guide](https://dart.dev/guides/language/effective-dart/style)
- Use `dart format` to format code
- Follow Flutter best practices
- Use meaningful widget names

### JavaScript/TypeScript Projects

- Follow [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
- Use ESLint and Prettier
- Write JSDoc comments for functions
- Use TypeScript when applicable

### PHP Projects

- Follow [PSR-12 coding standard](https://www.php-fig.org/psr/psr-12/)
- Use meaningful class and method names
- Write PHPDoc comments
- Follow SOLID principles

## 🏷️ Commit Message Guidelines

Use conventional commit format:

```
type(scope): description

[optional body]

[optional footer]
```

### Types:

- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc.)
- `refactor`: Code refactoring
- `test`: Adding or updating tests
- `chore`: Maintenance tasks

### Examples:

```
feat(auth): add Google OAuth integration
fix(ui): resolve mobile responsive issues
docs(readme): update installation instructions
```

## 🌐 Community

- **Discord**: [Join our community](https://discord.gg/usamasarwar)
- **Twitter**: [@UsamaSarwarPro](https://twitter.com/UsamaSarwarPro)
- **LinkedIn**: [UsamaSarwarPro](https://linkedin.com/in/UsamaSarwarPro)
- **Email**: [contact@usama.dev](mailto:contact@usama.dev)

## 🎯 Recognition

Contributors will be:

- Added to the project's contributors list
- Mentioned in release notes (for significant contributions)
- Featured on social media (with permission)
- Invited to join the core contributors team (for ongoing contributions)

## 📝 License

By contributing, you agree that your contributions will be licensed under the same license as the
project.

## ❓ Questions?

If you have any questions about contributing, feel free to:

- Open a discussion on GitHub
- Reach out on Discord
- Send an email to [contact@usama.dev](mailto:contact@usama.dev)

---

Thank you for contributing to open source! 🙏

**Happy Coding!** 🚀
