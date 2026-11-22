# Awesome-Static-Analysis-Code-Quality-Verification

<FollowUp>
Would you like me to:
* Add a **feature comparison table** (Supported Languages, Analysis Type: Linter vs. SAST vs. Type Checker vs. IaC, Implementation Language, SARIF output)
* Include **GitHub star counts and license badges** next to each open-source repository
* Generate a `README.md` for **another repository topic**

Let me know how you'd like to refine it!
</FollowUp>
# Awesome-Static-Analysis-Code-Quality-Verification

# Top Static Analysis & Code Quality Verification Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Static Application Security Testing (SAST), Linters, Type Checkers, Formal Verification & CI Quality Gates*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted code quality platforms** and **open-source GitHub projects** for **Static Analysis & Code Quality Verification**. These tools inspect source code without executing it to detect security vulnerabilities, memory safety bugs, anti-patterns, style violations, complexity hotspots, and formal specification regressions across CI/CD pipelines and local editors.

**Examples** include Semgrep, SonarQube Community Build, ESLint, Ruff, Oxlint, Biome, Bandit, Gosec, Clippy, PMD, Checkstyle, CodeQL, Infer, Trivy, SonarQube Cloud, Snyk Code, DeepSource, Codacy, Code Climate, Veracode, Checkmarx, Coverity, and we-promise/sure.

**Open-source emphasis**: This list heavily expands on active open-source SAST engines, ultra-fast Rust-powered linters, language-specific static analyzers, and self-hosted quality dashboards — ideal for developers, AppSec engineers, and DevOps teams enforcing automated code verification without vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[SonarQube Cloud (formerly SonarCloud)](https://sonarsource.com)**  
  Cloud-based continuous code quality and security inspection service offering automated pull-request decoration, branch analysis, and multi-language quality gates.

- **[Snyk Code](https://snyk.io)**  
  Developer-first AI-powered Static Application Security Testing (SAST) platform providing real-time vulnerability scanning and automated fix suggestions inside IDEs and PRs.

- **[DeepSource](https://deepsource.com)**  
  Automated static analysis and code health platform that detects bug risks, anti-patterns, security flaws, and test coverage gaps with Autofix pull requests.

- **[Codacy](https://codacy.com)**  
  Cloud code quality and AppSec platform aggregating static analysis, complexity metrics, duplication tracking, and coverage enforcement across 40+ languages.

- **[Code Climate (Qlty Cloud)](https://qlty.sh)**  
  Hosted maintainability, technical debt, and test coverage analytics platform providing automated pull-request quality checks and multi-linter orchestration.

- **[Veracode Static Analysis](https://veracode.com)**  
  Enterprise cloud SAST platform scanning compiled binaries and source code for OWASP Top 10 and CWE vulnerabilities with policy compliance reporting.

- **[Checkmarx One](https://checkmarx.com)**  
  Enterprise cloud application security platform offering SAST, Infrastructure-as-Code (IaC) scanning, and supply-chain risk verification.

- **[Black Duck Coverity](https://blackduck.com)**  
  Industrial-grade static analysis engine for C, C++, C#, Java, and modern web languages targeting deep concurrency, memory corruption, and security defects.


## Open-Source GitHub Projects

- **[Semgrep (OSS Engine)](https://github.com)**  
  Fast, lightweight, open-source static analysis engine for finding bugs, security vulnerabilities, and enforcing custom code standards across 30+ languages using syntax-aware rules.

- **[SonarQube Community Build](https://github.com)**  
  Self-hosted open-source edition of SonarQube providing continuous inspection of code quality, code smells, bugs, and security hotspots across major programming languages.

- **[ESLint](https://github.com)**  
  Pluggable, open-source JavaScript and TypeScript static analysis and linting tool with an extensive ecosystem of security, framework, and style rules.

- **[Ruff](https://github.com)**  
  Extremely fast Python linter and code formatter written in Rust, replacing Flake8, isort, pyupgrade, and Bandit rulesets in a single tool.

- **[Biome](https://github.com)** & **[Oxlint (Oxc)](https://github.com)**  
  High-performance, Rust-based open-source linters and formatters for JavaScript, TypeScript, JSX, and JSON designed as drop-in replacements for legacy toolchains.

- **[GitHub CodeQL (CLI & Open-Source Queries)](https://github.com)**  
  Semantic code analysis engine and open-source query suite that treats code as data to uncover complex taint-tracking and security vulnerabilities.

- **[Meta Infer](https://github.com)**  
  Open-source static analyzer written in OCaml for Java, C, C++, and Objective-C that detects null pointer dereferences, memory leaks, and data races.

- **[Clippy](https://github.com)**  
  Official open-source collection of over 700 lints to catch common mistakes, performance bottlenecks, and non-idiomatic code in Rust projects.

- **[GolangCI-Lint](https://github.com)**  
  Fast, parallel Go linters runner that aggregates dozens of static analysis tools (including `govet`, `staticcheck`, and `gosec`) for CI verification.

- **[Bandit](https://github.com)** & **[Gosec](https://github.com)**  
  Dedicated open-source security linters that inspect Python and Go ASTs for hardcoded secrets, SQL injection, weak cryptography, and unsafe system calls.

- **[PMD](https://github.com)** & **[SpotBugs](https://github.com)**  
  Mature open-source static code analyzers for Java and JVM languages detecting dead code, concurrency bugs, and security flaws at source and bytecode levels.

- **[Trivy](https://github.com)**  
  All-in-one open-source security scanner for Infrastructure-as-Code (Terraform, Kubernetes, Dockerfiles) misconfigurations, secrets, and dependencies.

- **[Sure (we-promise/sure)](https://github.com/we-promise/sure)**  
  Community-maintained open-source personal finance platform (Ruby on Rails) showcasing production-grade automated CI verification, RuboCop/Brakeman static security auditing, and Renovate dependency checks.

### Additional Strong Open-Source Options

- **[ShellCheck](https://github.com)** — Essential static analysis tool for `sh`/`bash` shell scripts catching quoting bugs, syntax pitfalls, and portability issues.
- **[Hadolint](https://github.com)** — Smarter Dockerfile linter that parses Dockerfiles into an AST and validates inline `bash` via ShellCheck.
- **[Cppcheck](https://github.com)** & **[Clang-Tidy](https://llvm.org)** — Open-source static analysis and bug-finding tools for C and C++ codebases.
- **[PHPStan](https://github.com)** & **[Psalm](https://github.com)** — Static analysis and type-checking engines for PHP that catch bugs without running tests.
- **[Brakeman](https://github.com)** — Zero-configuration static analysis security vulnerability scanner built specifically for Ruby on Rails applications.
- **[Gitleaks](https://github.com)** & **[TruffleHog](https://github.com)** — Open-source secret scanners that detect API keys, tokens, and credentials in Git history and pre-commit hooks.
- **[Qlty CLI](https://github.com)** & **[MegaLinter](https://github.com)** — Open-source multi-linter CLI runners that execute dozens of static analyzers consistently across local machines and CI.

**Frameworks for building custom systems**: Combine **Semgrep** + **Gitleaks** + **Trivy** in pre-commit hooks and GitHub Actions with language-native linters (**Ruff**, **Oxlint**, **Clippy**, **GolangCI-Lint**) and **SonarQube Community Build** for complete, self-hosted code quality and security verification.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Static analysis tools can produce false positives and false negatives; combine SAST with dynamic testing (DAST), dependency auditing, and manual security reviews.
- When running custom Semgrep or linter rulesets from third-party repositories, inspect rule definitions to avoid unintended command execution or data leakage in CI environments.

---

**Made for software engineers, AppSec teams, DevOps practitioners, and open-source maintainers.**  
Let's make static analysis and code quality verification faster, automated, and open to everyone.
