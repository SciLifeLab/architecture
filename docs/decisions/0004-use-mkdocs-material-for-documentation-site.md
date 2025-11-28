# 4. Use MkDocs Material for Documentation Site

Date: 2025-11-28

## Status

Accepted

## Context

We need a documentation site to publish ADRs, standards, and process documentation at `https://scilifelab.github.io/architecture/`.

Requirements:

- Automatic publishing from GitHub
- Support for Mermaid diagrams (same syntax as GitHub)
- Search functionality
- Easy for contributors (just Markdown)
- Professional appearance
- Adaptable to SciLifeLab visual identity

## Decision

Use **MkDocs Material** with SciLifeLab visual customization.

## Rationale

**Simple and effective:**

- Markdown → beautiful website in 5 minutes
- Built-in Mermaid support (identical to GitHub)
- Contributors only need Markdown knowledge
- Industry standard (Google, Microsoft use it)

**Better than alternatives:**

- Quarto: Too complex for pure documentation
- Jekyll: Less modern, more configuration
- Custom solution: Unnecessary maintenance burden

**Customizable:**
Material theme easily adapted to SciLifeLab brand through `mkdocs.yml` configuration.

## Consequences

**Positive:**

- Fast deployment
- Low contributor barrier
- Professional appearance
- Excellent search
- Automatic publishing via GitHub Actions

**Negative:**

- Web-only output (no native PDF)
- Brand customization limited to theme capabilities

**Implementation:**
Create `mkdocs.yml` with Material theme, SciLifeLab colors, and GitHub Actions deployment.
