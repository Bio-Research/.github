# Bio-Research `.github` Repository

This repository contains organization-wide default community health files, configuration templates, and shared resources for all repositories under the **Bio-Research** GitHub organization.

## What Is This Repository?

GitHub treats a repository named `.github` within an organization in a special way. Files placed here serve as **organization-level defaults** that automatically apply to every repository in the organization that does not have its own equivalent file. This makes it easy to maintain consistent standards, policies, and workflows across all Bio-Research projects from a single location.

## What's Inside

| Path | Purpose |
|------|---------|
| `profile/README.md` | Organization public profile shown on the Bio-Research GitHub page |
| `CONTRIBUTING.md` | Default guidelines for contributing to any Bio-Research repository |
| `CODE_OF_CONDUCT.md` | Code of conduct that applies across all Bio-Research repositories |
| `SECURITY.md` | Instructions for responsibly reporting security vulnerabilities |
| `SUPPORT.md` | Where to get help with Bio-Research projects |
| `.github/ISSUE_TEMPLATE/` | Default issue templates (bug reports, feature requests, etc.) |
| `.github/PULL_REQUEST_TEMPLATE.md` | Default pull-request checklist |
| `.github/workflow-templates/` | Reusable GitHub Actions workflow templates for CI/CD pipelines |

> Files that already exist in an individual repository always take precedence over the defaults here.

## About Bio-Research

Bio-Research is an organization dedicated to open, reproducible, and collaborative biological research. Our repositories span:

- **Bioinformatics pipelines** – sequence analysis, genome assembly, variant calling
- **Data management tools** – lab data ingestion, LIMS integrations, and storage utilities
- **Statistical & ML models** – predictive models for biological datasets
- **Documentation & protocols** – wet-lab and dry-lab standard operating procedures

## Contributing to This Repository

Changes to this repository affect every project in the organization, so please follow these steps:

1. **Open an issue** first to discuss the change you'd like to make.
2. **Fork or branch** off `main` and make your changes.
3. **Open a pull request** with a clear description of what is changing and why.
4. At least **one maintainer review** is required before merging.

## Contact & Support

- For general questions, open a [Discussion](../../discussions) in this repository.
- For security concerns, please open a **private** [security advisory](../../security/advisories/new) or email the maintainers directly. A `SECURITY.md` with full details will be added to this repository.
- For questions specific to a project, open an issue in that project's repository.

---

*Maintained by the Bio-Research core team.*