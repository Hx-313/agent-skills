# Repository-Wide Personal Branding

## Scope

Apply these defaults to user-facing writing and presentation throughout this
repository: website copy, portfolio content, product messaging, UI text,
documentation intended for customers, profiles, case studies, social content,
presentations, and calls to action.

Do not apply the brand voice to code, test names, dependency metadata, or
internal implementation comments unless the user explicitly asks for it.

## Source of Truth

For personal-brand decisions, read:

1. `writing-conversion-copy/detailed.md` for the brand identity, visual
   direction, voice, messaging, and guardrails.
2. `writing-conversion-copy/SKILL.md` for the writing workflow and conversion
   copy standards.

The current user request always takes priority. When no specific direction is
given, use this file for repository-wide defaults and `detailed.md` for the
brand system.

## Brand Direction

The working identity is a sharp, technical, premium, human personal brand
represented by a stylized THX monogram. Its central idea is:

> Make complex work feel clear, deliberate, and ready to move forward.

The brand should communicate clarity, craft, momentum, and trust. It should
feel confident without boasting, technical without becoming cold, and modern
without relying on trend language.

## Writing Rules

- Lead with the reader's situation, outcome, or reason to care.
- Write for one primary reader at a time.
- Use concrete nouns, active verbs, and specific language.
- Explain the benefit before the implementation when that improves clarity.
- Keep sections easy to scan with useful headings and short paragraphs.
- Put evidence close to the claim it supports.
- Use calls to action that state a verb and an outcome.
- Preserve the author's natural personality and intentional informality.
- Remove filler, generic introductions, corporate padding, and AI-sounding
  phrasing.
- Keep the promise in the hero, headline, or opening consistent with the body.

## Truth and Evidence

Never invent or imply unverified:

- metrics, growth, revenue, conversion, or performance results
- clients, customers, testimonials, awards, partnerships, or certifications
- seniority, scale, production impact, or capabilities
- technical details that have not been confirmed

When proof is missing, narrow the claim, use a clear placeholder, or describe
the work without claiming a result.

## Visual Defaults

Use the supplied mark and `detailed.md` as the visual reference. The working
palette is near-black, graphite, silver, ice white, electric cyan, and signal
teal.

- Prefer dark, high-contrast surfaces with restrained cyan or teal accents.
- Preserve the logo's proportions, colors, and clear space.
- Use geometric structure, strong alignment, and generous spacing.
- Let accents guide attention instead of decorating every surface.
- Prefer readable grotesk typography over novelty display fonts.
- Avoid busy backgrounds, excessive neon, generic stock imagery, and visual
  effects that compete with the mark.

If the repository already has design tokens or a component system, extend
those centralized definitions rather than scattering new brand values across
individual files.

## Content Patterns

### Page or feature

```text
Audience or context → useful outcome → how it works → proof → next action
```

### Portfolio project

```text
Problem → role and constraints → key decisions → work → supported result → lesson
```

### Social post

```text
Useful opening → explanation or example → practical implication
```

Use these as defaults, not mandatory templates. Follow the user's requested
format when it calls for a different structure.

## Repository Review Checklist

Before finalizing brand-related work, check:

- Does the reader understand what this is and why it matters quickly?
- Is the intended audience specific enough?
- Is the main claim supported or appropriately narrowed?
- Does the tone feel direct, thoughtful, technical, and human?
- Are the headline, body, visuals, and CTA saying the same thing?
- Is the copy easy to scan without becoming choppy?
- Are the logo, palette, spacing, and contrast handled consistently?
- Did any generic, inflated, or AI-sounding language slip in?
- Were any facts, credentials, results, or proof points invented?

Return finished copy when finished copy is requested. Explain the reasoning
only when the user asks for critique, alternatives, or a review.
