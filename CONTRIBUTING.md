# Contributing to Skyflo Engine

First off, thank you for considering contributing to Skyflo Engine! It's people like you that make Skyflo.ai such a great tool.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check [this list](https://github.com/skyflo-ai/engine/issues) as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible:

* Use a clear and descriptive title
* Describe the exact steps which reproduce the problem
* Provide specific examples to demonstrate the steps
* Describe the behavior you observed after following the steps
* Explain which behavior you expected to see instead and why
* Include details about your configuration and environment

### Suggesting Enhancements

Enhancement suggestions are tracked as [GitHub issues](https://github.com/skyflo-ai/engine/issues). When creating an enhancement suggestion, please include:

* A clear and descriptive title
* A detailed description of the proposed functionality
* Any possible drawbacks
* Relevant examples if applicable

### Your First Code Contribution

Unsure where to begin contributing? You can start by looking through these `good-first-issue` and `help-wanted` issues:

* [Good First Issues](https://github.com/skyflo-ai/engine/labels/good%20first%20issue)
* [Help Wanted Issues](https://github.com/skyflo-ai/engine/labels/help%20wanted)

### Development Process

1. Fork the repository
2. Clone your fork locally
3. Create a new branch:
   ```bash
   git checkout -b feature/my-feature
   # or
   git checkout -b fix/my-bugfix
   ```
4. Make your changes
5. Follow the [Style Guides](#style-guides)
6. Write meaningful commit messages
7. Push to your fork
8. Open a Pull Request

## Style Guides

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
* Consider starting the commit message with an applicable emoji:
    * 🎨 `:art:` when improving the format/structure of the code
    * 🐎 `:racehorse:` when improving performance
    * 🚱 `:non-potable_water:` when plugging memory leaks
    * 📝 `:memo:` when writing docs
    * 🐛 `:bug:` when fixing a bug
    * 🔥 `:fire:` when removing code or files
    * 💚 `:green_heart:` when fixing the CI build
    * ✅ `:white_check_mark:` when adding tests
    * 🔒 `:lock:` when dealing with security
    * ⬆️ `:arrow_up:` when upgrading dependencies
    * ⬇️ `:arrow_down:` when downgrading dependencies

### Python Style Guide

* Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/)
* Use type hints for function arguments and return values
* Use docstrings for functions and classes
* Maximum line length of 88 characters (using `black` formatter)
* Sort imports using `isort`
* Use f-strings for string formatting

### Documentation Style Guide

* Use [Google style](https://google.github.io/styleguide/pyguide.html#38-comments-and-docstrings) for docstrings
* Write documentation in Markdown
* Include code examples when relevant
* Keep line length to a maximum of 88 characters
* Use relative links within the repository

## Pull Request Process

1. Update the README.md with details of changes to the interface, if applicable
2. Update the documentation with details of any new functionality
3. The PR template will automatically be populated - fill it out completely
4. Include tests for any new functionality
5. Ensure the test suite passes
6. Update the CHANGELOG.md with a note describing your changes
7. The PR must be reviewed and approved by at least one maintainer

## Additional Notes

### Issue and Pull Request Labels

This section lists the labels we use to help us track and manage issues and pull requests.

* `bug` - Issues that are bugs
* `enhancement` - Issues that are feature requests
* `documentation` - Issues or PRs that affect documentation
* `good first issue` - Good for newcomers
* `help wanted` - Extra attention is needed
* `invalid` - Issues that aren't valid (e.g., user errors)
* `question` - Further information is requested
* `wontfix` - Issues that won't be worked on

## Getting Help

If you need help, you can:

* Join our [Discord community](https://discord.gg/kCFNavMund)
* Ask in [GitHub Discussions](https://github.com/skyflo-ai/skyflo/discussions)
* Email the maintainers at [dev@skyflo.ai](mailto:dev@skyflo.ai)

## License

By contributing to Skyflo Engine, you agree that your contributions will be licensed under its Business Source License 1.1.

## Code of Conduct

By participating in this project, you are expected to uphold our Code of Conduct. Please report unacceptable behavior to [conduct@skyflo.ai](mailto:conduct@skyflo.ai).