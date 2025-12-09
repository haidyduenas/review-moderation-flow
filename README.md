# review-moderation-flow
Flowchart for moderating product reviews across multiple e-commerce sites.
# Review Moderation Flowchart

This repository contains a visual decision flow for moderating product reviews across multiple e-commerce sites.  
The diagram is implemented in a single HTML file using [Mermaid](https://mermaid.js.org/) to keep it easy to read and edit for non-technical teams.

## Overview

The flowchart describes what happens with each incoming review:

- Detect if the review has only a rating or also text.
- Check for offensive content, spam or sensitive data.
- Identify if the comment is about:
  - **Physical stores / in-store experience**
  - **E-commerce experience (shipping, website, app)**
  - **The product itself**
- Decide whether to:
  - **Publish** the review,
  - **Not publish** it, or
  - **Route it to an internal team** (e.g. Store Experience / Customer Care).

## Getting Started

1. Clone or download this repository.
2. Open the HTML file in any modern browser (Chrome, Edge, Firefox, Safari).
3. The flowchart will render automatically thanks to the Mermaid CDN.

_No build step or local server is required._

## Customization

- The core logic of the diagram is defined inside the `<div class="mermaid">` block.
- You can:
  - Edit node labels to match your internal wording.
  - Add/remove decision steps as your policy evolves.
  - Adjust colors via the CSS variables at the top of the `<style>` block.

This makes it easy for Growth, IT and Service teams to iterate on the decision cascade while keeping a single source of truth.

## License

No License
