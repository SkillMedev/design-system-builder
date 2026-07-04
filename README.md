# Design System Builder

**For design/UI engineers: ship a production design system, tokens to handoff.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

Reach for this when you're standing up or maturing a real design system and need every layer to fit together — not a pile of one-off design tips. You get a coherent token architecture (global → semantic → component) with theming and dark mode, accessible color and contrast, a consistent icon and motion system, clean component APIs, and implementation-ready specs your engineers can build from. The result is a system that stays consistent across light/dark, scales past the first few screens, and survives the handoff to engineering.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/design-system-builder](https://skillme.dev/pack/design-system-builder) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add SkillMedev/design-system-builder`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[Design Token System](aouellets)** — Creates multi-tier token systems: global → semantic → component, with dark mode variants. _(external — see source)_
- **[Component API Design](aouellets)** — Designs React/Vue component APIs — props, composition, event handling, accessibility. _(external — see source)_
- **[Color Accessibility](skills/color-accessibility/SKILL.md)** — WCAG 2.2 contrast compliance, accessible palettes, and color choices that survive color blindness.
- **[Dark Mode Design](aouellets)** — Designs dark mode systems with proper elevation, surface hierarchy, and reduced contrast. _(external — see source)_
- **[Icon System](skills/icon-system/SKILL.md)** — Designs consistent icon systems — grid, stroke weight, optical sizing, naming conventions.
- **[Prototype Spec](skills/prototype-spec/SKILL.md)** — Writes detailed prototype specs: interactions, transitions, states, and edge cases.
- **[Animation System](skills/animation-system/SKILL.md)** — Designs motion systems — easing curves, durations, choreography — for UI components.
- **[Frontend Design](https://github.com/anthropics/skills/tree/main/skills/frontend-design)** — Official Anthropic skill. _(external — see source)_

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
