# Design System Builder

**For design/UI engineers: ship a production design system, tokens to handoff.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

Reach for this when you're standing up or maturing a real design system and need every layer to fit together — not a pile of one-off design tips. You get a coherent token architecture (global → semantic → component) with theming and dark mode, WCAG contrast math with a runnable checker and verified palette examples, a keyline-precise icon system (24px grid, 2px stroke, export pipeline), a motion token set with reduced-motion built in, clean component APIs, and dev-ready spec templates with states, breakpoints, and edge cases filled in. The result survives light/dark, scale, and the handoff to engineering.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/design-system-builder](https://skillme.dev/pack/design-system-builder) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add SkillMedev/design-system-builder`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[Design Token System](https://skillme.dev/skill/design-token-system)** — Creates multi-tier token systems: global → semantic → component, with dark mode variants. _(external — see source)_
- **[Component API Design](https://skillme.dev/skill/component-api-design)** — Designs React/Vue component APIs — props, composition, event handling, accessibility. _(external — see source)_
- **[Color Accessibility](skills/color-accessibility/SKILL.md)** — Audits and repairs color palettes against WCAG contrast thresholds — 4.5:1 for body text, 3:1 for large text and UI components, 7:1 for AAA — and makes them safe for color-blind users, delivering a verified pairing table.
- **[Dark Mode Design](https://skillme.dev/skill/dark-mode-design)** — Designs dark mode systems with proper elevation, surface hierarchy, and reduced contrast. _(external — see source)_
- **[Icon System](skills/icon-system/SKILL.md)** — Designs or audits an icon set so every glyph shares one grid, stroke weight, corner language, naming convention, and export pipeline, and delivers the written icon spec engineering builds against.
- **[Prototype Spec](skills/prototype-spec/SKILL.md)** — Turns a static design into a numbered, testable, dev-ready specification covering every state, interaction, breakpoint, motion detail, and edge case the mockup cannot show.
- **[Animation System](skills/animation-system/SKILL.md)** — Builds a coherent UI motion system — a duration token scale, named easing curves, choreography rules, and a per-component mapping — so every transition in the product draws from one vocabulary instead of ad-hoc values.
- **[Frontend Design](https://github.com/anthropics/skills/tree/main/skills/frontend-design)** — Official Anthropic skill. _(external — see source)_

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
