# 👋 Welcome to DertInfo

Thank you for visiting the DertInfo GitHub organisation and for your interest in the software that supports the annual **Dancing England Rapper Tournament (DERT)**.

Every year, a host team takes on the challenge of organising the event in their home city. This includes coordinating venues, recruiting and supporting judges, teaching the next generation of dancers, and ensuring the competition is fair, inclusive, well-run, and enjoyable for everyone involved.

DERT is one of the highlights of the rapper dancing calendar, and the community deserves confidence that results are accurate, feedback is constructive, and the event runs smoothly.

That's where DertInfo comes in.

Our aim is to reduce the administrative burden on organisers by providing secure, reliable, and well-engineered software that supports the event from registration through to results publication.

---

# 🚀 Getting Started

DertInfo now uses a monorepo approach.

All active development takes place in:

## 📦 dertinfo-mono

The `dertinfo-mono` repository contains the applications, services, infrastructure, documentation, and supporting components that make up the DertInfo platform.

Moving to a monorepo allows us to:

- Maintain a single source of truth
- Improve visibility across the platform
- Simplify development workflows
- Make cross-project changes easier and safer
- Improve the contributor onboarding experience
- Keep documentation closer to the code it describes

If you're looking to contribute, start with the monorepo.

---

# 📚 Documentation & Project Management

We use several GitHub features to help organise the project and collaborate with the community.

## Documentation

Historically, much of the project's documentation lived within the GitHub Wiki. While the Wiki remains available and contains useful information, our primary technical documentation now lives alongside the code within the `dertinfo-mono` repository.

Where possible, documentation is maintained close to the implementation it describes. This helps ensure documentation evolves with the code and remains accurate over time.

The authoritative source of technical documentation, setup instructions, architecture guidance, and operational information should be considered the documentation contained within the monorepo itself.

## Issues

Bugs, feature requests, enhancements, technical improvements, and other actionable work should be raised as GitHub Issues.

Helpful labels include:

- `good-first-issue`
- `requires-triage`

## Discussions

Questions, ideas, proposals, architectural discussions, and community conversations belong in GitHub Discussions.

If you have an idea for a new feature, want feedback on an approach, or would like to get involved, Discussions is the best place to start.

## Projects

GitHub Projects are used to coordinate larger initiatives, roadmap items, and work that spans multiple areas of the platform.

Project boards provide a high-level view of ongoing work and areas where help may be needed.

---

# 📦 Repository Structure

The monorepo contains several areas of the platform, including:

- Public-facing websites
- Competition management applications
- APIs and backend services
- Shared libraries and tooling
- Infrastructure as Code
- Platform documentation
- Automated testing

See the repository documentation for a detailed breakdown of the structure and ownership of each area.

---

# 🛠️ Development Environment

We aim to make contributing to DertInfo as flexible as possible.

The platform can be developed and operated in several ways:

- Native local development using the required prerequisites
- Docker-based development environments
- Development Containers (Dev Containers)
- Cloud-hosted deployments using the Infrastructure-as-Code templates included in the repository

Getting started documentation, local development guidance, environment configuration, and deployment instructions can be found within:

https://github.com/dertinfo/dertinfo-mono/tree/main/infra/dev

We encourage contributors to choose the approach that best suits their workflow and experience.

---

# 🏗️ Architecture

Architecture documentation, design decisions, environment guidance, and technical reference material are maintained within the monorepo wherever practical.

This approach allows architecture and documentation to evolve alongside implementation and supports both human contributors and modern AI-assisted development workflows.

The Wiki continues to provide useful supporting information and community-facing content, but the monorepo documentation should be considered the primary technical reference.

---

# 💻 Technology Stack

DertInfo is built using a range of modern technologies, including:

- Angular
- TypeScript
- ASP.NET / .NET
- Microsoft Azure
- GitHub
- GitHub Actions
- SQL Server
- Azure Blob Storage
- Application Insights
- Docker
- Dev Containers
- Infrastructure as Code (IaC)
- Bicep
- Playwright
- Mailgun
- Markdown-based documentation

The platform continues to evolve and new technologies may be introduced where they provide clear value to contributors and the wider DERT community.

---

# 📖 A Brief History

DertInfo was originally created for **DERT 2014**, hosted by **Black Swan Rapper**, as a single ASP.NET application developed by **David Hall**.

Over the following decade, the platform evolved significantly through several architectural iterations, including APIs, Angular-based web applications, mobile experiences, cloud infrastructure, and modern deployment pipelines.

In 2024, following the birth of his daughter and recognising the challenge of maintaining a growing platform alone, David made the decision to gift DertInfo to the community under the **GNU General Public License v3.0**.

David continues to support the project through code reviews, technical guidance, mentorship, and participation in community discussions. The long-term goal is to transfer knowledge into the community and ensure the platform remains sustainable for future generations of DERT organisers and participants.

---

# 🤝 Contributing

We welcome contributions of all sizes.

Whether you're fixing a typo, improving documentation, helping with testing, reviewing Pull Requests, or implementing new features, every contribution helps improve the platform and the experience for the DERT community.

The `main` branch is protected and changes should be submitted through Pull Requests using feature branches.

As the contributor community grows, we hope to continue expanding the pool of maintainers, reviewers, and subject matter experts who can help steward the project.

---

# 🤖 Agentic Development

DertInfo welcomes contributions created with the assistance of AI and agentic development tools.

Modern software development increasingly includes AI-assisted workflows such as code generation, code review support, documentation generation, test creation, analysis, and architectural guidance. We view these tools as valuable aids that can help contributors be more productive and lower the barrier to contribution.

However, responsibility for any change always remains with the contributor submitting it.

Before opening a Pull Request, contributors should:

- Understand the changes they are proposing
- Validate that the implementation is correct
- Ensure generated code follows project conventions
- Be able to explain and support design decisions
- Be prepared to respond to review feedback

We strongly encourage contributors to make small, iterative changes that move the platform towards a larger objective over time.

Large-scale agentic changes affecting many areas of the platform can be difficult for other contributors to review, validate, and maintain. Smaller Pull Requests are generally easier to understand, safer to merge, and more effective at sharing knowledge across the community.

The repository already contains guidance and rules to support AI-assisted development workflows. Contributors are welcome to use these where appropriate, but no specific AI tool, editor, IDE, or agent platform is required. DertInfo aims to remain accessible regardless of the tools you choose to use.

If a change would be difficult for another contributor to review, test, explain, or maintain, consider breaking it into smaller pieces before submitting it for review.

---

# 💡 Ideas & Feature Requests

Have an idea that isn't currently planned?

Want to improve the platform, development experience, documentation, or community processes?

Start a discussion and let's talk about it.

Community feedback is a key part of how DertInfo evolves, and we are always interested in ideas that can make the platform more useful, maintainable, secure, and inclusive.

---

# 🔒 Security

Security issues should **not** be reported through public Issues, Discussions, or Pull Requests.

If you discover a security vulnerability, please report it responsibly by contacting:

**dertinfo@gmail.com**

Please include:

- A description of the issue
- Steps to reproduce the vulnerability
- Potential impact
- Suggested remediation, if known

We will endeavour to acknowledge, triage, and address security reports as quickly as possible.

Where enabled, repositories also support GitHub's **Private Vulnerability Reporting** feature, allowing security issues to be reported confidentially.

The security of participant data, judging information, competition results, and community information is extremely important to us, and we greatly appreciate responsible disclosure from the community.

---

# ❤️ New to Open Source?

So are we, in many ways.

DertInfo is community software built by volunteers for volunteers. We are continually learning and improving both the platform and the way we collaborate.

If you have experience in software engineering, architecture, accessibility, testing, documentation, operations, open-source governance, community building, security, or event management, we'd love to hear from you.

Most importantly, thank you for taking an interest in DertInfo and helping to support the future of DERT.
