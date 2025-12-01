# Contributing to Mortiscope

Thank you for your interest in contributing to Mortiscope! We appreciate your support and engagement with us.

## About This Project

Mortiscope is a two-person thesis project focused on Post-Mortem Interval (PMI) estimation using _Chrysomya megacephala_ developmental stage analysis. As this is an academic research project, **direct code contributions from external developers are currently closed**.

However, we warmly welcome:

- Bug reports
- Feature suggestions
- Feedback and discussions
- Documentation improvements
- Research inquiries and academic collaboration opportunities

## How You Can Contribute

### Reporting Bugs

If you encounter a bug, please use our [Bug Report Template](https://github.com/mortiscope/.github/blob/main/ISSUE_TEMPLATE/bug_report.yml) and provide:

- Clear description of the issue
- Steps to reproduce
- Expected vs. actual behavior
- Environment details (OS, browser, versions)
- Screenshots or logs (if applicable)

### Suggesting Features

Feature suggestions are welcome! Please use our [Feature Request Template](https://github.com/mortiscope/.github/blob/main/ISSUE_TEMPLATE/feature_request.yml) and include:

- Problem statement
- Proposed solution
- Use case scenarios
- Research impact (if applicable)

### Reporting Security Vulnerabilities

**Do NOT open public issues for security vulnerabilities.** Please follow our [Security Policy](SECURITY.md) for responsible disclosure.

### Asking Questions

For general questions or discussions:

- Check existing [GitHub Discussions](https://github.com/orgs/mortiscope/discussions)
- Review repository README files for setup and usage information
- Open a new discussion if your question hasn't been addressed

## Code of Conduct

All interactions must comply with our [Code of Conduct](CODE_OF_CONDUCT.md). We are committed to providing a welcoming, safe, and respectful environment for all participants.

## Academic Collaboration

If you are interested in:

- Using Mortiscope data for your research
- Citing Mortiscope in your work
- Discussing research methodologies

Please contact the maintainers directly.

## Development Guidelines (For Maintainers)

### Repository Structure

```plaintext
mortiscope/
├── mortiscope-api/
├── mortiscope-web/
└── .github/
```

### Code Quality Standards

- **Python**: Follow PEP 8, use Ruff for linting, type hints required
- **TypeScript**: ESLint + Prettier, strict type checking
- **Testing**: Maintain test coverage for critical paths
- **Documentation**: Keep README files and inline documentation updated

### Commit Message Convention

We follow a conventional commit format with timestamped commits:

```bash
git commit -m '<type>: <short description>' \
-m '<detailed description>'
```

**Format:**

- **Type**: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`, `perf`, `ci`, `build`
- **Short description**: Concise title
- **Detailed description**: Explain what changed and why

**Examples:**

```bash
# Documentation update
git add . && \
git commit -m 'docs: Update README tech stack with links and notes' \
-m 'Improved `README.md` by linking technology stack items to their official sites and adding a reference to the main configuration file for the full dependency list.'

# Feature addition
git add . && \
git commit -m 'feat: Add SAHI sliced inference support' \
-m 'Implemented sliced inference for improved small object detection in forensic images.'

# Bug fix
git add . && \
git commit -m 'fix: Resolve authentication token refresh bug' \
-m 'Fixed token expiration handling in Auth.js middleware to prevent premature logouts.'
```

## License

All Mortiscope repositories are licensed under the [GNU Affero General Public License v3.0 (AGPL-3.0)](https://www.gnu.org/licenses/agpl-3.0.en.html).

By submitting feedback or suggestions, you agree that:

- Your contributions may be incorporated into the project under the AGPL-3.0 license
- You have the right to submit the content
- You understand this is a research/thesis project

## Contact

For questions or inquiries, please:

- Open a GitHub Discussion for general questions
- Use issue templates for bugs and features
- Contact maintainers directly for academic collaboration
