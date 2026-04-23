# Amson's Technical Writing Samples

In this repository, you'll find two technical writing exercises I've completed in my own time. They're written in the second person, and complete with YAML frontmatter metadata and references. The next section of this README paraphrases (with confidential details removed) an actual documentation framework that I've authored for Bloomberg's Physical Assets and Geo Data team. I've also included a PowerPoint I made about documentation best practices in the AI era.

## Technical Writing Exercises

Exercise #1 — Explaining Concepts

Write a short overview that helps an engineer choose when to use REST or SOAP web services.

● This exercise should be two pages or less.

Exercise #2 — How to Play Tic-Tac-Toe

Write a short document that describes how to play tic-tac-toe. 

● Assume that your audience is an intelligent adult but has somehow never heard of tic-tac-toe. <br>
● This exercise should be two pages or less.

## Documentation Framework Sample

```markdown
# Documentation Framework and Best Practices

## Overview

This documentation framework defines the writing standards for the Physical Assets and Geo Data ([PAGEO](../general/glossary.md#pageo)) team. Its goal is to ensure that PAGEO documentation is:

- Clear and consistent across domains and regions
- Easy to navigate for FTEs, vendors, and stakeholders
- Useful, relevant, and maintainable over time
- Structured in a way that supports search and AI-assisted discovery

This guide does **not** prescribe detailed rules for every document. Instead, it provides shared principles, templates, and conventions that PAGEO documentation should follow.

## Audience

This framework applies to anyone creating or maintaining PAGEO documentation, including but not limited to:

- PAGEO FTEs
- BNEF analysts contributing documentation
- Geo/Maps partners
- Vendor-facing documentation owners

This guidance is intentionally lightweight so it can be applied incrementally as documentation evolves.

## Core Principles

**Write for the reader.** Assume they may be new to PAGEO, unfamiliar with the system, or switching contexts quickly. Avoid embedding text within images for readability and AI discoverability.

**Be consistent.** Documents covering similar topics should look and feel familiar. Consistent headings and patterns make documentation easier to scan and easier to maintain.

**Prioritize structure over volume.** Clear headings and focused sections work better than long blocks of text. A reader should understand what a page is for by scanning the headings.

**Plan for the future.** Systems and workflows evolve over time. Documentation should be easy to update, clearly owned, and written in a way that avoids duplicating the same rules across many pages.

## Document Types

PAGEO documentation focuses primarily on a small number of document types. They’re ordered intentionally to match how readers typically consume documentation and how work progresses across PAGEO systems.

- **Overviews** provide context. They explain what something is, define scope, and describe how it fits into the broader PAGEO ecosystem before readers move into onboarding or workflow documentation.

- **Onboarding guides** support staged ramp-up. They move from context and access, to first contributions, to deeper system understanding and expectations. These guides are designed to support clarity during the first weeks of engagement.

- **Workflow guides** document repeatable tooling or operational procedures. They focus on execution and consistency. While PAGEO does not rely heavily on classic incident-response runbooks, a structured format is useful for workflows that must be performed reliably across teams.

## Templates

Consider the templates below when creating new pages. They’re designed to keep structure consistent while allowing flexibility to adapt content as needed.

- [Overview Template](template_overview.md)
- [Onboarding Template](template_onboarding.md)
- [Workflow Template](template_workflow.md)

## Writing Style

In addition to structure and document type, consistency at the sentence level is equally important. This guidance focuses on how PAGEO documentation should read, not just how it should be organized.

**Use direct, action-oriented language where applicable.** Choose short sentences and concrete conditions over vague phrasing. If something depends on a condition, state the condition and the expected outcome.

**Clarity should take precedence over style.** If a sentence can be simplified without losing meaning, simplify it. Avoid filler terms such as “usually,” “if needed,” or “should work,” as they introduce ambiguity.

**Keep one idea per sentence and one task per step.** When documenting procedures, use numbered steps. When listing related concepts, use bullet points only when they improve readability.

**Be explicit about scope.** If a document applies only to a specific tool, region, or workflow, state that clearly. If something is out of scope, define those boundaries directly.

**Maintain a professional but approachable tone.** Documentation should feel practical and supportive, neither overly formal nor overly casual.

## Headings and Searchability

Clear heading hierarchy supports readability, long-term maintainability, and discoverability. This section defines how headings should be structured so that documentation is easy to scan and find.

**Use clear and consistent headings.** Headings should help someone (and search) understand what the section contains without reading the full page.

**Each page should have a single H1 (`#`).** This is the page title and should be concise and specific.

**Use H2s (`##`) to define the main sections of the document.** If someone scans only the H2 headings, they should understand the overall structure and intent of the page.

**Use H3s (`###`) only when they improve clarity within a section.** Try to limit unnecessary nesting. If a page requires many levels of headings, consider simplifying the structure or splitting the content into multiple pages.

**Do not skip heading levels (for example, jumping from H2 directly to H4)**. Maintain a logical hierarchy throughout the page.

**Keep one topic per heading.** If a section is performing two separate jobs, split it.

**Avoid vague titles such as “Notes,” or “Other”**. Choose headings that clearly describe the section’s content.

## Documentation Ownership and Feedback

Individual documentation pages should have a clearly identified owner responsible for keeping content accurate and up to date.

In addition, PAGEO has a dedicated documentation owner. If you have questions about structure, standards, or how to apply this framework, you may reach out to the documentation owner, Amson Liu, for guidance.

For documentation feedback, corrections, or suggestions, the recommended method of engagement is to open a GitHub issue. This ensures feedback is visible, trackable, and properly routed.
```


```
