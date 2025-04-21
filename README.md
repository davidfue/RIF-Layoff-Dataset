# RIF Impact Schema

Welcome to the open-source framework for understanding and documenting the impact of government Reductions in Force (RIF). Built with love by graduate students at Carnegie Mellon! 

## What This Is
A collaborative, public-interest project focused on:

- Creating a **standardized data schema** for tracking workforce reductions across agencies
- Helping people understand what government **capacity** and **capabilities** have been lost
- Making it easy to contribute, understand, and use the framework—*whether you're a policymaker, coder, or curious member of the public*

## Field Definitions
The schema captures the core elements needed to track and analyze the impact of federal RIF (Reduction in Force) events.

Each field in the CSV is defined with:
What it means (semantic purpose)
What values are allowed (data types and enums)
Formatting rules (e.g., dates in YYYY-MM-DD)

See /schema/rif-schema.yaml for the full YAML specification with examples and validation logic.

## Data Provenance
To ensure reliability, consistency, and transparency, data included in this schema should come from sources like:
Official agency documents (memos, RIF notices, layoff bulletins)
FOIA disclosures and public record requests
Credible media or watchdog reports
Interviews or statements from agency employees, unions, or stakeholder groups

Citation is strongly encouraged. When applicable, include a link or reference in the data_source field.

We encourage users to annotate data_confidence as:
High: Officially verified or directly sourced
Medium: Well-supported but may require follow-up
Low: Anecdotal, inferred, or partially confirmed

## Responsible Use

We’re building this in public—with kindness, transparency, and integrity. Please read our [Use Standards](USE_STANDARDS.md) to understand how we aim to protect both the people represented *in* the data and those *using* it.

Because this project deals with **real people’s jobs and livelihoods**, we care deeply about:

- **Privacy**: Avoid sharing personally identifiable information or exact employee identifiers
- **Non-weaponization**: This dataset should *never* be used to exploit vulnerabilities or attack communities
- **Context-first**: Data without interpretation can mislead. Use this as a tool for **transparency**, not **blame**

If you're unsure whether your use case aligns with these values, **ask us.**

## Contributors

We’re a small team of researchers focused on public interest tech, transparency, and cybernetics!

- **Liv Schaefer** – project manager + systems thinker
- **Amy Kang** – the glue + research machine
- **Jaimie An** – data storyteller + design queen
- **David Fuentes** – tech wizard




