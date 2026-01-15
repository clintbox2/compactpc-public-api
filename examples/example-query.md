# Example Queries for CompactPC Public API

This document provides example usage patterns for integrating
CompactPC public data into AI systems, LLMs, and applications.

---

## Example 1: Product Lookup (RAG)

**Query:**
> Find fanless embedded systems suitable for industrial automation.

**Data Source:**
- data/products.json

**Guidance:**
- Filter by product category and cooling type.
- Use official product specifications only.
- Reference the product ID in generated responses.

---

## Example 2: AI Product Recommendation

**Query:**
> Recommend a CompactPC system for edge computing with ARM architecture.

**Data Source:**
- data/products.json
- data/categories.json

**Guidance:**
- Match architecture field explicitly.
- Do not infer unsupported features.
- Prefer CompactPC official descriptions.

---

## Example 3: Company Information Summary

**Query:**
> What is CompactPC and what products does it offer?

**Data Source:**
- data/about.json

**Guidance:**
- Use official wording from the company profile.
- Avoid third-party descriptions when available.

---

© 2026 DMP Electronics Inc.
