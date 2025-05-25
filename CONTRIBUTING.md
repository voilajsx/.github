# Contributing to @voilajsx

Thank you for your interest in contributing to **@voilajsx**! We’re building a family of open-source tools focused on simplicity, modularity, and developer autonomy — and we welcome contributions of all kinds from the community.

---

## Table of Contents

- [Getting Started](#getting-started)
- [Development Setup](#development-setup)
- [Project Structure](#project-structure)
- [How to Contribute](#how-to-contribute)
- [Pull Request Process](#pull-request-process)
- [Coding Standards](#coding-standards)
- [Testing Guidelines](#testing-guidelines)
- [Documentation](#documentation)
- [Reporting Issues](#reporting-issues)
- [Security Vulnerabilities](#security-vulnerabilities)
- [Code of Conduct](#code-of-conduct)
- [License](#license)
- [Recognition](#recognition)
- [Questions?](#questions)

---

## Getting Started

1. **Fork** the repository you want to contribute to
2. **Clone** your fork locally:
   \`\`\`bash
   git clone https://github.com/YOUR-USERNAME/REPO-NAME.git
   cd REPO-NAME
   \`\`\`
3. **Add upstream remote**:
   \`\`\`bash
   git remote add upstream https://github.com/voilajsx/REPO-NAME.git
   \`\`\`
4. **Create a feature branch**:
   \`\`\`bash
   git checkout -b feature/your-feature-name
   \`\`\`

---

## Development Setup

### Prerequisites

- Node.js ≥ 18.x
- npm ≥ 8.x

> Some projects may use \`pnpm\` or \`bun\`. Refer to the individual project's README.

### Installation

\`\`\`bash
npm install
\`\`\`

To run tests and start development:

\`\`\`bash
npm test
npm run dev
\`\`\`

---

## Project Structure

While each \`@voilajsx\` repo may differ, most follow a modular pattern like:

\`\`\`
project/
├── src/ # Core source code
│ ├── module/ # Modules by concern
│ ├── docs/ # Module-specific documentation
│ ├── tests/ # Unit and integration tests
├── examples/ # Sample usage examples
├── scripts/ # Dev and build scripts
├── README.md # Project overview
├── CONTRIBUTING.md # Contribution guide
└── package.json # Project metadata
\`\`\`

---

## How to Contribute

### Ways to Contribute

- 💡 **Suggest Features**: Open a discussion or issue with your idea.
- 🐞 **Report Bugs**: Help us improve by reporting reproducible bugs.
- 🔧 **Fix Issues**: Pick an issue and propose a fix.
- ✨ **Add Features**: Help expand functionality in new or existing modules.
- 🧪 **Improve Tests**: Add missing tests or improve coverage.
- 📝 **Enhance Docs**: Make documentation clearer or more complete.
- 🎓 **Create Examples**: Provide real-world usage for new contributors.

### Development Workflow

1. Pick an open issue or propose a new idea.
2. Comment to avoid duplication.
3. Create a feature branch.
4. Write code & tests.
5. Submit a pull request (PR).

---

## Pull Request Process

1. Sync your branch with upstream:
   \`\`\`bash
   git fetch upstream
   git rebase upstream/main
   \`\`\`
2. Ensure your changes pass linting and tests:
   \`\`\`bash
   npm run lint
   npm test
   \`\`\`
3. Update documentation and examples if relevant.
4. Submit a PR:
   - Use a clear and descriptive title.
   - Reference related issues.
   - Describe **why** you made the change.
   - Add screenshots (if UI-related).
   - Follow the commit/PR title format below.

### PR Title Format

\`\`\`
type(scope): short description

Examples:
feat(router): add dynamic route support
fix(auth): prevent token leak on refresh
docs(core): improve install guide
test(cli): add coverage for init command
\`\`\`

Types: \`feat\`, \`fix\`, \`docs\`, \`test\`, \`refactor\`, \`chore\`, \`perf\`, \`style\`

---

## Coding Standards

- Use **ES Modules**
- Prefer \`async/await\` over Promises
- 2-space indentation
- Single quotes for strings
- Use \`const\` and \`let\`, avoid \`var\`
- Always handle edge cases and errors gracefully

### File Naming

- Use **kebab-case** for filenames
- \`\*.test.js\` for test files
- \`example-\*.js\` for usage samples

### Example Function Docblock

\`\`\`js
/\*\*

- Capitalizes a string
- @param {string} input - The string to capitalize
- @returns {string} Capitalized string
  \*/
  export function capitalize(input) {
  return input.charAt(0).toUpperCase() + input.slice(1);
  }
  \`\`\`

---

## Testing Guidelines

- Use **Vitest** or the framework specified in the repo
- Aim for >90% coverage
- Cover success, failure, and edge cases
- Run tests locally before PR

\`\`\`bash

# Run all tests

npm test

# Watch mode

npm run test:watch

# Coverage

npm run test:coverage
\`\`\`

---

## Documentation

Each module or repo should include:

1. \`README.md\` — Quick overview and usage
2. \`DEVELOPER_REFERENCE.md\` — Internal module guide
3. \`API_REFERENCE.md\` — Detailed API signatures
4. \`PROMPT_REFERENCE.md\` (if AI-based) — LLM prompts and patterns

Write docs that explain **why**, not just what.

---

## Reporting Issues

Before submitting:

1. Search for existing issues
2. Confirm it's not fixed on the main branch
3. Try to reproduce it

When reporting:

- Title and summary
- Steps to reproduce
- Expected vs actual result
- OS, Node.js version, and browser (if relevant)
- Logs, screenshots, or error messages

---

## Security Vulnerabilities

Please **do not** post security issues publicly.

Instead, email: **kt@voilacode.com**  
Include:

- Description
- Steps to reproduce
- Severity and potential impact
- Optional suggested fix

We'll respond within **48 hours**.

---

## Code of Conduct

We follow the [Contributor Covenant](https://www.contributor-covenant.org/) standard.

### Be Respectful

- Welcome newcomers
- Give constructive feedback
- Assume good intent
- Report abuse to **kt@voilacode.com**

---

## License

All contributions to \`@voilajsx\` projects are subject to the terms of the **MIT License**, unless otherwise stated.

By contributing, you agree your work may be modified and redistributed under this license.

---

## Recognition

We love highlighting contributors!

You’ll be acknowledged in:

- The \`CONTRIBUTORS.md\` file
- Release notes
- Community posts or spotlights

---

## Questions?

- Email: **kt@voilacode.com**
- Use GitHub Discussions if enabled in the repo

---

Thanks again for helping build the future of modular, developer-first tools with @voilajsx! 🚀
