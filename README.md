# Micro-Interactions Skill

An expert micro-interaction architect skill for AI coding agents. Covers **mobile apps** (iOS, Android, React Native), **web applications** (React, Vue, Svelte, vanilla), and **responsive websites**.

## What It Does

When activated, your AI agent becomes a micro-interaction specialist that can:

- **Design** micro-interactions using Dan Saffer's 4-part framework (Trigger → Rules → Feedback → Loops)
- **Implement** animations with the right tool for the job (CSS transitions, Framer Motion, GSAP, SwiftUI springs, Jetpack Compose, Reanimated)
- **Audit** existing interactions against a 10-dimension scorecard
- **Consult** on timing, easing curves, spring physics, and motion tokens
- **Adapt** interactions across platforms and input methods (touch vs mouse, mobile vs desktop)

## Coverage

### Platforms
- Web (CSS, React, Vue, Svelte, vanilla JS)
- iOS (SwiftUI, UIKit)
- Android (Jetpack Compose, XML)
- React Native (Reanimated 3, Gesture Handler)

### 20+ Interaction Patterns
Buttons, toggles, pull-to-refresh, swipe actions, bottom sheets, form validation, skeleton loading, toasts, modals, dropdowns, cards, scroll reveals, shared elements, tabs, accordions, progress indicators, dark mode toggle, badges, drag & drop, add-to-cart, password strength, command palette

### Reference Tables
- Duration scale (instant → dramatic)
- 10 easing curves with CSS `cubic-bezier` values
- Spring physics presets (gentle → stiff)
- Design system motion tokens (JSON)
- Audit scorecard (10 dimensions)

### Built-In Guardrails
- Performance: compositor-only properties, 60fps enforcement, mobile budgets
- Accessibility: `prefers-reduced-motion`, ARIA live regions, focus management, touch targets
- Responsive: `pointer`/`hover` media queries, breakpoint-aware duration scaling

## Install

```bash
npx skills add solinkz/micro-interactions-skill
```

Or install for a specific agent:

```bash
npx skills add solinkz/micro-interactions-skill --agent claude
npx skills add solinkz/micro-interactions-skill --agent cursor
npx skills add solinkz/micro-interactions-skill --agent opencode
```

## Usage

Once installed, the skill activates automatically when you mention micro-interactions, animations, transitions, motion, easing, springs, gestures, haptics, or ask to make something "feel better" / "feel snappy" / "feel polished".

You can also invoke it directly:

```
/micro-interactions
```

## Contributing

Contributions are welcome! Whether it's new interaction patterns, platform coverage (Flutter, .NET MAUI, desktop), improved easing values, or accessibility fixes — see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

MIT
