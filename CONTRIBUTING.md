# Contributing to Micro-Interactions Skill

Thanks for your interest in contributing! This skill is open source and we welcome contributions from anyone.

## Ways to Contribute

### Add New Interaction Patterns
The pattern library in `skills/micro-interactions/SKILL.md` covers 20+ patterns but there's always more. Great additions would be:
- Carousel / image gallery interactions
- Search bar expand/collapse
- Floating action button (FAB) menu
- Onboarding / walkthrough flows
- Chat message animations
- Infinite scroll loading
- Gesture-based navigation patterns
- Audio/video player controls
- Map interactions (pin drop, cluster expand)
- Table sorting/filtering animations

### Improve Existing Patterns
- Add code examples (CSS, React, SwiftUI, Compose) to pattern descriptions
- Add platform-specific implementation notes
- Update easing/spring values based on real-world testing
- Add new library references (new animation libraries, new platform APIs)

### Platform Coverage
- Flutter/Dart micro-interaction patterns
- Kotlin Multiplatform (KMP) patterns
- .NET MAUI / Xamarin patterns
- Desktop (Electron, Tauri) specific patterns
- Game engine UI (Unity, Unreal) patterns

### Fix Issues
- Incorrect easing values or spring configs
- Outdated API references
- Missing accessibility considerations
- Performance advice that needs updating

## How to Contribute

1. **Fork** the repo
2. **Create a branch** for your changes: `git checkout -b add-carousel-pattern`
3. **Edit** `skills/micro-interactions/SKILL.md`
4. **Test** — install your fork locally to verify the skill works:
   ```bash
   npx skills add your-username/micro-interactions-skill
   ```
5. **Submit a PR** with a clear description of what you added/changed and why

## Guidelines for the SKILL.md

### Pattern Format
Follow the existing pattern format:
```
### Pattern Name
\```
Trigger    → What happens, duration, easing
State 2    → Next step in the interaction
State 3    → Resolution, any cleanup
           → Accessibility note if relevant
\```
```

### Quality Standards
- Every pattern must include **timing** (duration in ms) and **easing** (curve name or cubic-bezier)
- Every pattern must consider **accessibility** (reduced motion, ARIA, keyboard)
- Every pattern must consider **mobile vs desktop** differences where applicable
- Use specific values, not vague descriptions ("200ms ease-out" not "quick and smooth")
- Keep descriptions concise — this is a reference, not a tutorial

### What Belongs in the Skill
- Interaction patterns with specific timing/easing values
- Platform-specific implementation guidance
- Performance constraints and rules
- Accessibility requirements
- Reference tables (durations, curves, spring configs)

### What Doesn't Belong
- Full code tutorials or lengthy examples (keep code snippets short)
- Opinion pieces on design trends
- Marketing language
- Anything not directly actionable by an AI coding agent

## Code of Conduct

Be respectful. Focus on making the skill better. Technical disagreements are fine — keep them constructive and back them with evidence (user research, performance data, platform guidelines).

## Questions?

Open an issue on the repo. We're happy to discuss ideas before you start working on a PR.
