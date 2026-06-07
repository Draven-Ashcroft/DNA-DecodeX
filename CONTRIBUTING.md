# Contributing to DeCodeX

Thank you for your interest in contributing to DeCodeX! This document provides guidelines for contributing to the project.

## How to Contribute

### Reporting Bugs
- Check existing issues before reporting
- Provide clear description of the bug
- Include browser/OS information
- Steps to reproduce the issue

### Suggesting Features
- Open an issue with the tag `enhancement`
- Describe the use case and benefits
- Include mockups if applicable

### Submitting Pull Requests
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes with clear messages
4. Push to the branch
5. Open a Pull Request with description of changes

## Code Style Guidelines

### HTML/CSS
- Use semantic HTML elements
- Follow BEM naming convention for CSS classes
- Keep CSS organized with clear section comments
- Maintain responsive design principles

### JavaScript
- Use meaningful variable and function names
- Add comments for complex logic
- Keep functions focused and modular
- Follow existing code style

## Teacher Customization Guide

The tool is designed for easy customization:

### Changing Colors
Search for `COLOR SCHEME` in the CSS to modify:
- `--at`: A-T base pair color
- `--gc`: G-C base pair color
- `--blue`: Left backbone color
- `--cyan`: Right backbone color

### Modifying DNA Sequence
Edit `SEQ_NC` array in JavaScript (around line 705)

### Adjusting Animation Speed
Modify `ROTATE_SPEED` constant (around line 695)

## Questions?
Open an issue or start a discussion on the repository.

Happy contributing! 🧬
