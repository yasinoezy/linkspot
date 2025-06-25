Note: LinkSpot is a fork of OpenBio.app. We’ve adapted and enhanced the project for our needs while honoring the original attribution.

Thank you for your interest in contributing to LinkSpot! We welcome contributions of all kinds: bug reports, feature requests, documentation improvements, translations, and code enhancements.

Table of Contents

Code of Conduct

Getting Started

Reporting Bugs

Suggesting Enhancements

Submitting a Pull Request

Coding Conventions

Running Tests

Local Development Setup

Additional Resources

Code of Conduct

This project adheres to the Contributor Covenant Code of Conduct. By participating, you are expected to uphold this code. Please report unacceptable behavior to the maintainers.

Getting Started

Fork the repository on GitHub.

Clone your fork locally:

git clone git@github.com:YourUsername/linkspot.git
cd linkspot

Install dependencies:

pnpm install

Create a new branch for your changes:

git checkout -b feature/your-feature-name

Reporting Bugs

If you encounter a bug, open an issue with the following information:

Steps to reproduce the bug

Expected behavior vs. actual behavior

Screenshots or logs if available

Environment details (OS, browser, Node.js version)

Suggesting Enhancements

Enhancement requests are welcome! Please:

Search existing issues to avoid duplicates.

Open a new issue and provide:

A clear description of the enhancement.

Use cases and benefits.

Any relevant mockups or examples.

Submitting a Pull Request

Ensure your branch is up to date with main:

git fetch upstream
git rebase upstream/main

Write clear, descriptive commit messages.

Push your branch to your fork:

git push origin feature/your-feature-name

Open a pull request against the main branch of this repo.

Describe your changes and link to any related issues.

Coding Conventions

Follow the existing code style with Prettier and ESLint.

Keep commits atomic and focused.

Write clear, concise comments and documentation.

For TypeScript code, ensure types are accurate.

Running Tests

Run the test suite before submitting changes:

pnpm test

Local Development Setup

Copy the example environment file:

cp .env.example .env.local

Fill in required variables in .env.local.

Start the development server:

pnpm dev

Visit http://localhost:3000 to view the app.

Additional Resources

Project README

License

Code of Conduct

We appreciate your contributions and look forward to collaborating with you on LinkSpot!

