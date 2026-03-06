# Contributing

Thank you for contributing to SolarPoint! This guide outlines how to get involved and make meaningful contributions.

Questions about contributing can be asked in the **Discussions** tab of the repository.

## Table of Contents

- [Ways to Contribute](#ways-to-contribute)
- [Before You Contribute](#before-you-contribute)
    - [Community Guidelines](#community-guidelines)
    - [Project Licensing](#project-licensing)
    - [AI-Assisted Contributions](#ai-assisted-contributions)
    - [Governance](#governance)
- [Getting Help & Support](#getting-help--support)
- [Submitting Issues](#submitting-issues)
    - [Bug Reports](#bug-reports)
    - [Feature Requests](#feature-requests)
- [Triaging Issues](#triaging-issues)
- [Your First Contribution](#your-first-contribution)
- [Local Development Setup](#local-development-setup)
    - [Git Configuration](#git-configuration)
- [Coding Standards](#coding-standards)
- [Deprecation Policy](#deprecation-policy)
- [Development Workflow](#development-workflow)
    - [Branching Strategy](#branching-strategy)
    - [Writing Tests](#writing-tests)
    - [Commit Messages](#commit-messages)
    - [Commit Signing](#commit-signing)
- [Opening a Pull Request](#opening-a-pull-request)
    - [Submitting Code](#submitting-code)
    - [Submitting Documentation](#submitting-documentation)
    - [PR Requirements](#pr-requirements)
    - [Review Process](#review-process)
- [Project Communication](#project-communication)
    - [Global Communication Standards](#global-communication-standards)
    - [GitHub Discussions](#github-discussions)
    - [Using GitHub Issues and Discussions](#using-github-issues-and-discussions)
    - [Project and Development Updates](#project-and-development-updates)

## Ways to Contribute

You can contribute to our projects in several ways:

- Report and triage bugs.
- Contribute to the codebase or documentation.
- Request new features or improvements.
- Write blog posts or tutorials about the project.
- Help others by answering questions about this project.

Any other contributions that improve the project are welcome!

## Before You Contribute

### Community Guidelines

All contributors are expected to adhere to our [Code of Conduct](https://github.com/solarpointwp/.github?tab=coc-ov-file).

### Project Licensing

By submitting a pull request, you represent that you have the right to license your contribution to the project and the community. All contributions are subject to the terms of the repository's `LICENSE` file.

### AI-Assisted Contributions

AI tools are not prohibited. They are a normal part of modern development, and the requirement is understanding, not avoidance.

If you use AI tooling in any part of your contribution, you must disclose this in the pull request. All AI-assisted contributions are held to the exact same standards as any other submission:

- **Total Ownership:** You are fully responsible for every line of code you submit, regardless of how it was generated. When you sign your commits (DCO), you are certifying you have the right to submit this code.
- **Comprehension:** Code that you cannot explain, debug, or defend during the review process will not be merged.
- **Human Context:** Pull request descriptions must be written in your own words. PRs with generic, AI-generated descriptions, or low-effort AI dumps without human insight, will be closed.
- **License Compatibility:** All contributions must be compatible with the terms of the repository's `LICENSE` file. You must avoid AI tools whose terms conflict with or restrict redistribution under the applicable license.

AI tools should be used to **enhance, not replace** the human elements that make open source special: learning, collaboration, and community growth.

### Governance

SolarPoint currently operates with a light governance structure. This will evolve as the community grows. Your feedback is welcome.

## Getting Help & Support

For questions, troubleshooting, and usage guidance, use the **Discussions** tab. Search existing discussions before starting a new topic.

See our [Support Guidelines](https://github.com/solarpointwp/.github/blob/main/SUPPORT.md) for where to direct your inquiry, how to ask quality questions, and what to expect from the community.

> [!IMPORTANT]
> GitHub Issues are reserved for confirmed bug reports and approved feature requests. Support questions opened as issues will be converted or closed.

## Submitting Issues

All issues should be submitted through the **Issues** tab.

> [!IMPORTANT]
> Do not open public issues for security vulnerabilities. Refer to the [Security Policy](https://github.com/solarpointwp/.github/security/policy) for responsible disclosure instructions.

**New features or significant changes:** Open an issue before submitting a pull request. This allows maintainers and the community to discuss the design before significant time is invested.

**Small fixes:** Documentation updates, typo corrections, or minor bug fixes do not require an issue. A pull request on its own is sufficient. Maintainers may request an issue for larger design decisions.

### Bug Reports

Bug reports help make SolarPoint better for everyone. Please provide as much detail as possible to help investigate and resolve the issue efficiently.

**Before submitting:**

- Search the **Issues** tab (including closed issues) to check if the bug has already been reported or resolved.
- Isolate the issue by reproducing it in a minimal environment with as few dependencies as possible (e.g. deactivating other packages, extensions, or conflicting WordPress plugins).
- Note if the issue is a regression, meaning something that previously worked but has stopped working in a newer version.

**When submitting:**

- Provide a clear and concise description of the bug.
- Describe what was expected to happen and what actually happened instead.
- Include steps to reproduce the issue with code samples that follow [SSCCE principles](https://sscce.org/).
- Include environment details: package version, PHP version, WordPress version, OS, and any other relevant context.
- Provide any error logs, stack traces, or screenshots that may help diagnose the issue.

Reports that do not contain enough information to reproduce the issue may be closed without further action.

### Feature Requests

Feature ideas help shape the future of SolarPoint. Please include as much detail as possible so the request can be fully understood and evaluated.

**Before submitting:**

- Search the **Issues** tab (including closed issues) to check if the feature has already been proposed or implemented.
- If a similar request exists, use a reaction to show support rather than opening a duplicate.
- If you plan to implement the feature yourself, open a discussion in the **Discussions** tab first to confirm it aligns with the project's direction before investing time writing code.

**When submitting:**

- Provide a clear and concise description of the feature.
- Explain the problem or use case the feature would solve and why it is needed.
- Include any proposed solution or implementation ideas.
- Add examples, references, or additional context that might help evaluate the request.

## Triaging Issues

Triage helps maintainers and contributors address issues efficiently:

- Clarifying the issue's intent so contributors have what they need before starting work.
- Preventing duplicate issues and discussions.
- Keeping the issue tracker organized and actionable.

If you do not have the time or background to contribute code, consider helping with triage instead. You can ask clarifying questions, reproduce reported bugs, identify duplicates, and suggest workarounds directly in the issue comments. No repository access is required.

As the project grows, trusted contributors may be granted the GitHub **Triage** role, allowing them to manage labels and organize issues without write access to the codebase.

## Your First Contribution

New to open source or to this project? Welcome. Here's how to get started:

- Look for issues labeled `good first issue` for approachable starting points.
- Ask questions in the **Discussions** tab before starting work on anything non-trivial. It is far better to check alignment upfront than to have a pull request rejected after significant effort.
- Small contributions such as documentation fixes, additional test coverage, and typo corrections are just as valued as new features.

## Local Development Setup

Setup instructions vary by project. See the repository's `README.md` for prerequisites, installation steps, and any project-specific architecture notes.

### Git Configuration

Make sure your Git configuration matches your GitHub account for DCO compliance. To configure your name and email:

```bash
git config user.name "Your Name"
git config user.email "your@email.com"
```

## Coding Standards

All code contributions must pass automated quality checks before review. This includes code style formatting, static analysis, and all tests. Check the repository's `README.md`, `composer.json`, or `package.json` for the exact commands.

### Code Style

Projects enforce consistent code formatting. **Do not hand-format code;** always use the configured formatter.

#### PHP CS Fixer

Code style follows [@PhpCsFixer](https://cs.symfony.com/doc/ruleSets/PhpCsFixer.html) (based on [PER Coding Style 3.0](https://www.php-fig.org/per/coding-style/)) with custom modifications. Apply formatting using:

```bash
composer cs:fix
```

> [!NOTE]
> See `.php-cs-fixer.dist.php` for the full ruleset.

Notable rules and overrides:

- **No Yoda conditions:** Write `$value === null` rather than `null === $value`.
- **Void returns:** Always declare `: void` on void methods.
- **Type ordering:** Ensure `null` is always the last element in union types (e.g. `string|int|null`).
- **Namespace imports:** Use `use` statements instead of inline fully-qualified class names.
- **Strict types:** Include `declare(strict_types=1)` in all PHP files.

### Static Analysis

Where configured, static analysis runs in CI. Failures are blocking and must be resolved before requesting review.

#### PHPStan

All code must pass PHPStan static analysis at `max` level. See `phpstan.neon.dist` for the configuration.

### Naming Conventions

For PHP projects, use the following conventions:

| Construct | Convention | Example |
| --- | --- | --- |
| Classes | `UpperCamelCase` for specific implementation | `SendmailTransport` |
| Abstract classes | `UpperCamelCase` for base concepts | `ApiTransport` |
| Interfaces | `UpperCamelCase` for concept names | `Logger` |
| Traits | `UpperCamelCase` for verb-based names | `HasPriority` |
| Exceptions | `UpperCamelCase` | `InvalidConfig` |
| Methods and properties | `camelCase` | `getContainer()` |
| Constants | `SCREAMING_SNAKE_CASE` | `DEFAULT_PRIORITY` |

**Interfaces:** Named after the concept they represent, not their role as an interface. They live alongside their concrete implementations within the same package.

**Abstract classes:** Named after what they represent, not their role as a base class. Each level in an inheritance hierarchy should add meaningful shared behavior. Inheritance chains are permitted when each level serves a clear purpose; depth alone is not a problem.

For non-PHP projects, follow the language's community conventions unless the repository README specifies otherwise.

### PHPDoc

For PHP projects:

- Add PHPDoc blocks only when they provide information not already expressed by type hints.
- Avoid writing PHPDoc blocks that simply restate the type signature.
- Place `null` at the end of union types.

## Deprecation Policy

Public APIs are **never removed without a deprecation cycle**. This protects downstream code from unexpected breakage.

**Three-step deprecation process:**

1. **Documentation / DocBlocks:** Mark the method, class, or property with `@deprecated`, noting the version and replacement.

   *PHP example:*

   ```php
   /**
    * @deprecated since 1.2, use Bar::newMethod() instead.
    */
   public function oldMethod(): void
   ```

2. **Runtime notice:** Trigger a deprecation notice inside the method body so it surfaces during testing, using the appropriate mechanism for the language or runtime.

   *PHP examples:*

   **Unconditional Trigger:** Trigger unconditionally using PHP's native `trigger_error()`:

   ```php
   trigger_error('Call Bar::newMethod() instead.', E_USER_DEPRECATED);
   ```

   **Conditional Trigger:** Gate the notice on `WP_DEBUG` so it only surfaces when debug mode is enabled:

   ```php
   if (defined('WP_DEBUG') && WP_DEBUG) {
       trigger_error('Call Bar::newMethod() instead.', E_USER_DEPRECATED);
   }
   ```

3. **CHANGELOG entry:** Document the deprecation under the appropriate version in `CHANGELOG.md`.

Deprecated APIs remain functional until the next major release, when they may be removed.

> [!IMPORTANT]
> To prevent breaking changes, do not:
>
> - Remove a public API in a minor or patch release without a prior deprecation cycle.
> - Change the signature of a public method in a patch release.
> - Change exception messages in a patch release, as downstream code may depend on them.

## Development Workflow

This section describes the step-by-step process for moving a contribution from a local idea to a merged pull request.

### Branching Strategy

Branching workflows vary by repository. Some repositories use `main` as the active development branch, while others use versioned branches (e.g. `1.x`, `2.x`). Check the repository's README or open issues to confirm which branch to target before opening a pull request.

#### When Using Version Branches

**Creation:** When a new major version enters active development, a new version branch is created (e.g. `2.x`).

**Maintenance:** Standard bug fixes are maintained in the lowest actively supported version branch. Security vulnerabilities are patched across all actively maintained branches until they reach end-of-life.

**Propagation:** Bug fixes are applied to the lowest actively maintained branch and cherry-picked forward to newer branches. Critical security fixes are applied across all relevant branches simultaneously.

#### Branch Naming Conventions

Branch names follow the format `<prefix>/<description>` using lowercase letters, numbers, and hyphens. Include the issue number when applicable.

| Prefix | Purpose |
| --- | --- |
| `feature/` | New features or enhancements |
| `bugfix/` | Standard bug fixes |
| `security/` | Patches for confirmed security vulnerabilities |
| `hotfix/` | Urgent production-breaking fixes (non-security) |
| `chore/` | Maintenance, documentation, or dependency updates |

> [!TIP]
> If unsure which branch to target, ask in the linked issue or check the repository's README.

**Examples:**

```text
feature/add-hook-priority-support
bugfix/issue-42-config-null-fallback
hotfix/issue-91-bootstrap-fatal
chore/update-installation-guide
chore/update-dependencies
```

### Writing Tests

All new features must include automated tests.

Bug fixes must include a regression test: a test that fails before the fix is applied and passes afterward.

#### Test Execution and CI

Test runners vary depending on the project architecture. PHP packages primarily use **PHPUnit**, while frontend packages may use Jest or similar tools.

- **Running tests:** Check the project's `README.md` for the correct command (e.g. `composer test`, `npm run test`).
- **Strict mode:** In PHPUnit environments, strict mode is enforced. Risky tests, `E_USER_DEPRECATED` notices, and standard PHP warnings or errors will cause CI failures and must be resolved rather than suppressed.

#### Best Practices and Quality

- **Mocking:** Use mocks to isolate the code under test. This ensures tests remain fast and do not require a live WordPress or browser environment unless explicitly testing integration.
- **Coverage:** Aim for meaningful coverage of all logical paths. Avoid testing only "happy paths"; ensure edge cases and error conditions are accounted for.
- **Isolation:** Tests must not rely on the state of previous tests. Always use setup and teardown methods to reset the environment.

### Commit Messages

SolarPoint follows the [Conventional Commits](https://www.conventionalcommits.org/) specification. Consistent commit messages enable **automated changelog generation**, **semantic versioning**, and a **readable project history**.

#### Message Format

Each commit must follow this structure:

```text
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

#### Common Commit Types

| Type | Purpose |
| --- | --- |
| `feat` | A new feature (correlates with **MINOR** in Semantic Versioning) |
| `fix` | A bug fix (correlates with **PATCH** in Semantic Versioning) |
| `docs` | Documentation changes only |
| `style` | Formatting changes that do not affect code logic |
| `refactor` | Code changes that neither fix a bug nor add a feature |
| `perf` | A change that improves performance |
| `test` | Adding or updating tests |
| `chore` | Routine maintenance, dependency updates, or configuration changes |
| `ci` | Changes to CI configuration and workflows |
| `revert` | Reverts a previous commit |

#### Contribution Rules

- **Imperative mood:** Use verbs such as "add," "fix," or "remove" instead of "added" or "fixes."
- **Lowercase description:** Begin the description with a lowercase letter for a uniform log.
- **Subject line limit:** Keep the subject line under 72 characters for readability across Git interfaces.
- **Optional scope:** Include context in parentheses when relevant, e.g. `feat(logger): add new handler`.
- **Issue references:** Place references to issues in the commit body or footer, not the subject line.
- **Atomic commits:** Each commit should focus on a single change, ensuring stability and a clear project history.

#### Breaking Changes

Breaking changes (correlating with **MAJOR** in Semantic Versioning) must be clearly highlighted to ensure they are not overlooked during automated releases. They can be indicated in one of two ways:

- **Bang (!) notation:** Append a `!` immediately before the colon, e.g.

  ```text
  feat(mailer)!: remove SMTP transport provider
  ```

- **Footer notation:** Include `BREAKING CHANGE:` as the first words of a footer, followed by a description of the change.

Example with a footer:

```text
refactor(logger): update error reporting signature

This change ensures all error logs include a mandatory error code for better debugging.

BREAKING CHANGE: the log() method now requires a numeric error code as the second argument.
```

### Commit Signing

All commits must be signed off using the [Developer Certificate of Origin (DCO)](https://developercertificate.org/). Adding a `Signed-off-by` line certifies that you authored the code and have the right to submit it under the project's license.

```text
Developer Certificate of Origin
Version 1.1

Copyright (C) 2004, 2006 The Linux Foundation and its contributors.

Everyone is permitted to copy and distribute verbatim copies of this
license document, but changing it is not allowed.


Developer's Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or

(b) The contribution is based upon previous work that, to the best
    of my knowledge, is covered under an appropriate open source
    license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part
    by me, under the same open source license (unless I am
    permitted to submit under a different license), as indicated
    in the file; or

(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.

(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including all
    personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with
    this project or the open source license(s) involved.
```

#### How to Sign Your Commits

Add the sign-off using the `-s` flag:

```bash
git commit -s -m "fix: short description of the change"
```

This produces:

```text
Signed-off-by: Your Name <your@email.com>
```

> [!IMPORTANT]
> Make sure your [Git configuration](#git-configuration) is set up before committing.

#### Fixing a Missing Sign-off

If you have already committed and forgot to include the sign-off, you can fix it without needing to redo your work.

For the most recent commit:

```bash
git commit --amend --no-edit -s
```

For multiple previous commits:

```bash
# Replace 'n' with the number of commits you need to sign
git rebase --signoff HEAD~n
```

After fixing the commits locally, you will need to force-push the changes to your fork:

```bash
git push --force-with-lease origin HEAD
```

## Opening a Pull Request

For significant changes, ensure your contribution corresponds to an open issue before opening a pull request. For small fixes, a pull request on its own is sufficient.

### Submitting Code

Code contributions must meet the project's strict quality and testing standards.

- **Branch:** Create a branch from the appropriate base branch. See [Branching Strategy](#branching-strategy).
- **Standards:** Ensure your code adheres to the SolarPoint [Coding Standards](#coding-standards).
- **Tests:** Include or update tests as necessary. See [Writing Tests](#writing-tests).
- **Quality:** Run the project's automated quality checks (e.g. `composer qa` or `npm run lint`) before committing.
- **Commit:** Sign your commits and follow the [Commit Messages](#commit-messages) format.

### Submitting Documentation

Documentation improvements are highly valued and do not require running the full code quality suite.

- **Branch:** Create a branch for your edits. See [Branching Strategy](#branching-strategy).
- **Style:** Ensure your language is clear and follows the [Global Communication Standards](#global-communication-standards).
- **Commit:** Use the `docs:` prefix in your commit message (e.g. `docs: add section to getting started`).

### PR Requirements

Before clicking **Create pull request**, ensure your submission meets the following criteria:

- **Single focus:** Each PR should address a single topic. Do not mix unrelated changes. Each commit should be atomic and leave the project in a working state. See [Commit Messages](#commit-messages).
- **Linked issue:** Reference an existing issue, if one was created (e.g. `Fixes #123`).
- **Conventional title:** Follow the [Conventional Commits](https://www.conventionalcommits.org/) format (e.g. `feat: add new feature`).
- **Human description:** Complete the PR template in your own words. Generic or AI-generated descriptions will be returned for revision.
- **.gitignore:** Do not add IDE- or OS-specific entries (e.g. `.vscode/`, `.idea/`, `Thumbs.db`). Maintain these in a global `.gitignore` file.
- **Passing CI:** All automated checks must pass. Resolve any errors before requesting review.
- **License:** All contributions are subject to the terms of the repository's `LICENSE` file.

Pull request descriptions must match the provided template. New pull requests are automatically pre-populated based on `pull_request_template.md` content.

### Review Process

Once a pull request is opened:

- **CI checks:** Code style checks, static analysis, and automated tests will run. These must pass before human review begins.
- **Feedback:** A maintainer will review your contribution. Be prepared to discuss your implementation and make requested changes.
- **Approval:** Once approved, your pull request will be merged into the active development branch and included in the next release.

Pull requests labeled `needs info` that receive no response will be marked as stale after 30 days and closed 7 days later. They can be reopened once you are ready to continue.

Draft pull requests are welcome for early feedback. Convert to **Ready for Review** when complete. Drafts left inactive for more than 7 days may be closed but can be reopened when you are ready to proceed.

## Project Communication

### Global Communication Standards

To ensure clarity and consistency across a global community, the following standards apply to all documentation, issues, and discussions:

- **Simplicity first:** This project serves an international audience. Strive for simple, clear language and avoid unnecessary jargon or complex idioms.
- **Language and grammar:** Use modern American English spelling and grammar for all public-facing documentation, commit messages, and release notes.
- **Dates and time:** Prefer [ISO 8601](https://www.iso.org/iso-8601-date-and-time-format.html) or [IETF RFC 3339](https://datatracker.ietf.org/doc/html/rfc3339) formats for all dates and times.
- **Units of measure:** Where applicable, prefer metric (SI) units.
- **Secure links:** Always use `https` URLs. Ensure links are direct and do not rely on unnecessary redirects.

### GitHub Discussions

Join the conversation, ask questions, and help improve SolarPoint on GitHub Discussions. Discussions are organized into categories to help you find relevant topics:

- **Announcements:** For official development announcements, release notes, and project updates.
- **General:** For community chat and topics that do not fit elsewhere.
- **Ideas:** For proposing new features, architectural changes, or project direction.
- **Q&A:** For technical questions, troubleshooting, and general support related to SolarPoint.

### Using GitHub Issues and Discussions

GitHub Issues and Discussions serve different purposes. Use the guidance below to determine where to post:

- **Discussions (Q&A):** For questions or issues that do not point to a specific code problem (e.g. "I am experiencing a strange error when using this package, but I am not sure why").
- **GitHub Issues:** For actionable tasks that require a specific code change (e.g. "There is a bug in a specific class or method that causes a crash").
- **Discussions (Ideas):** For proposing new architectural components or features.
- **GitHub Issues:** For implementing an agreed-upon feature or fix.

### Project and Development Updates

Stay connected as SolarPoint evolves. Official development announcements and project updates are posted in the **Announcements** category within GitHub Discussions.

To receive notifications, click the **Watch** button at the top right of the repository and subscribe to the events you want to follow.
