# Contributing to ManaData

Thank you for your interest in contributing to ManaData! This document provides guidelines and instructions for contributing to this project.

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](./CODE_OF_CONDUCT.md).

## How Can I Contribute?

### Reporting Bugs

Bugs are tracked as GitHub issues. Before creating a bug report, please check if the issue has already been reported. When you create a bug report, please include as many details as possible:

- A clear and descriptive title
- Steps to reproduce the behavior
- Expected behavior
- Current behavior
- Screenshots if applicable
- Your environment (OS, browser, etc.)

### Suggesting Enhancements

Enhancement suggestions are also tracked as GitHub issues. When suggesting an enhancement, please include:

- A clear and descriptive title
- Detailed explanation of the proposed enhancement
- Any specific implementation details if applicable
- Why this enhancement would be useful to most users

### Contributing Data

One of the most valuable ways to contribute to ManaData is by helping us collect, clean, and standardize public datasets. Please follow these guidelines:

1. Ensure data is from a reputable and publicly available source
2. Document the source, collection methodology, and any transformations
3. Format data according to our data standards (see [Data Standards](./docs/DATA_STANDARDS.md))
4. Include both Telugu and English metadata where applicable

### Your First Code Contribution

Unsure where to begin? Look for issues labeled `good-first-issue` or `help-wanted`.

#### Development Setup

1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR_USERNAME/mana-data.git`
3. Add the original repository as an upstream remote: `git remote add upstream https://github.com/vamsikrishnajallipalli/mana-data.git`
4. Install dependencies: `npm install`
5. Create a new branch for your changes: `git checkout -b feature/your-feature-name`

### Pull Requests

1. Update your fork to the latest upstream version
2. Create a branch for your changes
3. Make your changes
4. Run tests and ensure they pass
5. Update documentation if needed
6. Submit a pull request

## Styleguides

### Git Commit Messages

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests after the first line

### JavaScript Styleguide

We use ESLint with Airbnb's JavaScript style guide. Run `npm run lint` to check your code.

### CSS Styleguide

We use Tailwind CSS for styling. Please follow their utility-first approach.

### Documentation Styleguide

- Use Markdown for documentation
- Include code examples where applicable
- Keep language simple and accessible
- Provide translations in Telugu for key documentation

## Community

- Join our [Discussions](https://github.com/vamsikrishnajallipalli/mana-data/discussions) for questions and community interaction
- Follow the OpenAP Initiative on social media for updates

Thank you for contributing to make public data accessible to all citizens of Andhra Pradesh!
