# 2. Use CC BY-SA 4.0 License

Date: 2025-11-25

## Status

Accepted

## Context

We need to choose an appropriate license for this architecture documentation repository. The documentation will contain:
- Architecture Decision Records (ADRs)
- Process documentation
- Technical governance guidelines
- Standards and best practices

The license should:
- Allow others to learn from and adapt our architectural decisions
- Ensure that derivative works remain open and accessible
- Require attribution to SciLifeLab
- Be compatible with collaborative development via GitHub issues and pull requests

## Decision

We will use the Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0) license for this repository.

## Consequences

### Positive

- **Share-alike provision**: Any derivative works must be distributed under the same or compatible license, ensuring the documentation remains open
- **Attribution requirement**: Users must give appropriate credit, which helps maintain visibility of SciLifeLab's contributions
- **Wide adoption**: CC BY-SA 4.0 is widely recognized and understood in the open-source community (used by Wikipedia and many documentation projects)
- **Flexibility**: Others can freely use, adapt, and build upon our architectural decisions while keeping them accessible
- **Non-software focus**: CC licenses are specifically designed for creative works and documentation, making them more appropriate than software licenses (MIT, GPL, etc.)

### Negative

- **Not suitable for code**: Any code examples should be licensed separately under a software license
- **Compatibility considerations**: Share-alike requirement may limit how others can combine our documentation with other licensed content
- **No warranty disclaimer**: Users should be aware that architectural decisions are provided "as-is" without guarantees of suitability

### Neutral

- The license file (LICENSE) has been added to the repository root
- A license badge and information have been added to the README
- Future code repositories may need different licenses (e.g., MIT, Apache 2.0) appropriate for software

