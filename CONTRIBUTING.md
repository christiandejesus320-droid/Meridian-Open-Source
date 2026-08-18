# Contributing to Meridian

Thank you for your interest in building the public movement around Meridian. This repository is the **Public Face** of Meridian: a documentation-first space for architecture, standards, experiments, integrations, community proposals, and shared vocabulary.

> **Zero-Code Exposure is mandatory.** This repository does not accept private engine source code, production configuration, secrets, credentials, customer data, database exports, internal URLs, or copied files from private repositories.

## What You Can Contribute

You can contribute without access to the private Meridian engine. Useful contributions include documentation improvements, architecture proposals, MCP connector patterns, agent safety practices, evaluation ideas, public examples that are intentionally self-contained, issue triage, developer experience improvements, and community education.

## Before You Start

Please read the README, search existing Issues and Discussions, and confirm that your proposal belongs in the public repository. If your idea depends on private implementation details, describe the public interface or problem without revealing those details.

For security-sensitive matters, do not open a public issue. Follow `SECURITY.md` instead.

## Development Workflow

The public repository is documentation-first. A typical contribution looks like this:

1. Fork the repository and create a focused branch.
2. Make a small, clearly scoped change.
3. Keep examples self-contained and free of credentials or private identifiers.
4. Check links, Markdown rendering, terminology, and bilingual consistency.
5. Open a pull request describing the problem, the proposed change, and its public-safety review.

Example commands:

```bash
git clone https://github.com/christiandejesus320-droid/Meridian-Open-Source.git
cd Meridian-Open-Source
git checkout -b docs/your-proposal
# edit documentation only
git diff --check
git add .
git commit -m "docs: explain your public contribution"
git push origin docs/your-proposal
```

These commands are for the public documentation repository only. Do not clone or reference the private application repository as part of a public contribution.

## Pull Request Expectations

A strong pull request has one purpose, explains its motivation, identifies the affected public audience, and includes enough context for a reviewer to understand the change without access to private code. Use clear English or Spanish; bilingual improvements are welcome.

Pull requests may be rejected when they expose private implementation details, add credentials or generated secrets, make unsupported claims, duplicate an existing proposal, or expand scope without discussion.

## Commit Style

Use concise, imperative commit messages with a public scope when possible:

- `docs: clarify the agent capability model`
- `docs: add an MCP integration pattern`
- `community: propose an evaluation rubric`
- `governance: improve contributor guidance`

## Review and Decision Making

Maintainers review contributions for usefulness, clarity, public safety, and alignment with Meridian's vision. A proposal can be technically interesting and still belong in a private channel if implementing it would reveal proprietary details.

## Recognition

We want to recognize contributors who improve the public operating model for agentic software. Meaningful documentation, safety practices, architecture proposals, issue triage, examples, and community stewardship all count.

## Code of Conduct

Participation is governed by `CODE_OF_CONDUCT.md`. By contributing, you agree to follow it.
