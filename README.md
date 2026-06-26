# Awesome Design Skills [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<img width="1200" height="630" alt="og-awesome-design-skills" src="https://github.com/user-attachments/assets/d392937a-a0a3-408d-b3f8-4d8920f836f9" />

<br>

> A curated registry of 67 design system skill files for AI-powered agentic tools like [Claude Code](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview), [Cursor](https://www.cursor.com/), [Codex](https://openai.com/index/codex/), and others. Pull any skill into your project with a single command.

Each skill now ships as a folder with:
- `SKILL.md` for AI-agent instructions (tokens, component rules, accessibility constraints, quality gates)
- `DESIGN.md` for human-readable design intent, rationale, and implementation notes

**[Preview all design skills on Type UI](https://typeui.sh/design-skills)**

## Quick Start

Pull any design skill directly into your project using the [TypeUI CLI](https://github.com/bergside/typeui.sh):

```bash
npx typeui.sh pull <slug>
```

For example, to pull the Glassmorphism design skill:

```bash
npx typeui.sh pull glassmorphism
```

Or browse all available skills interactively:

```bash
npx typeui.sh list
```

## What is a Design Skill?

A design skill is a folder containing `SKILL.md` and `DESIGN.md`.

`SKILL.md` acts as the instruction source for AI agents and LLMs. It contains:

- **Brand & mission** — the design philosophy and visual identity
- **Style foundations** — typography scale, color palette, spacing system
- **Component families** — buttons, inputs, cards, modals, navigation, and more
- **Accessibility rules** — WCAG 2.2 AA compliance, keyboard-first interactions
- **Writing tone** — content and voice guidelines
- **Do/Don't rules** — explicit patterns and anti-patterns
- **Quality gates** — testable acceptance criteria for code review

`DESIGN.md` is a companion document for human readers and maintainers. It captures:

- **Design overview** — concise summary of the visual direction
- **Rationale and references** — context for why patterns/tokens exist
- **Maintenance notes** — guidance for keeping design decisions aligned over time

When an AI agent reads a skill file, it follows the `SKILL.md` guidelines to generate UI code that is consistent, accessible, and true to the design system.

## Design Skills

Browse all **67** design skills. Click any thumbnail to open the live preview on [typeui.sh/design-skills](https://typeui.sh/design-skills), or copy the pull command underneath to add the skill to your project.

<table>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/agentic"><img src="https://www.typeui.sh/registry-examples/agentic-marketing.png" alt="Agentic" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/agentic"><b>Agentic</b></a><br />
      <sub><code>npx typeui.sh pull agentic</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/ant"><img src="https://www.typeui.sh/registry-examples/ant-marketing.png" alt="Ant" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/ant"><b>Ant</b></a><br />
      <sub><code>npx typeui.sh pull ant</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/roku"><img src="https://www.typeui.sh/registry-examples/roku-marketing.png" alt="Roku" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/roku"><b>Roku</b></a><br />
      <sub><code>npx typeui.sh pull roku</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/artistic"><img src="https://www.typeui.sh/registry-examples/artistic-marketing.png" alt="Artistic" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/artistic"><b>Artistic</b></a><br />
      <sub><code>npx typeui.sh pull artistic</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/bento"><img src="https://www.typeui.sh/registry-examples/bento-marketing.png" alt="Bento" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/bento"><b>Bento</b></a><br />
      <sub><code>npx typeui.sh pull bento</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/bold"><img src="https://www.typeui.sh/registry-examples/bold-marketing.png" alt="Bold" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/bold"><b>Bold</b></a><br />
      <sub><code>npx typeui.sh pull bold</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/brutalism"><img src="https://www.typeui.sh/registry-examples/brutalism-marketing.png" alt="Brutalism" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/brutalism"><b>Brutalism</b></a><br />
      <sub><code>npx typeui.sh pull brutalism</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/cafe"><img src="https://www.typeui.sh/registry-examples/cafe-marketing.png" alt="Cafe" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/cafe"><b>Cafe</b></a><br />
      <sub><code>npx typeui.sh pull cafe</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/claymorphism"><img src="https://www.typeui.sh/registry-examples/claymorphism-marketing.png" alt="Claymorphism" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/claymorphism"><b>Claymorphism</b></a><br />
      <sub><code>npx typeui.sh pull claymorphism</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/claude"><img src="https://www.typeui.sh/registry-examples/claude-marketing.png" alt="Claude" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/claude"><b>Claude</b></a><br />
      <sub><code>npx typeui.sh pull claude</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/clean"><img src="https://www.typeui.sh/registry-examples/clean-marketing.png" alt="Clean" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/clean"><b>Clean</b></a><br />
      <sub><code>npx typeui.sh pull clean</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/codex"><img src="https://www.typeui.sh/registry-examples/codex-marketing.png" alt="Codex" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/codex"><b>Codex</b></a><br />
      <sub><code>npx typeui.sh pull codex</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/colorful"><img src="https://www.typeui.sh/registry-examples/colorful-marketing.png" alt="Colorful" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/colorful"><b>Colorful</b></a><br />
      <sub><code>npx typeui.sh pull colorful</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/contemporary"><img src="https://www.typeui.sh/registry-examples/contemporary-marketing.png" alt="Contemporary" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/contemporary"><b>Contemporary</b></a><br />
      <sub><code>npx typeui.sh pull contemporary</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/corporate"><img src="https://www.typeui.sh/registry-examples/corporate-marketing.png" alt="Corporate" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/corporate"><b>Corporate</b></a><br />
      <sub><code>npx typeui.sh pull corporate</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/cosmic"><img src="https://www.typeui.sh/registry-examples/cosmic-marketing.png" alt="Cosmic" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/cosmic"><b>Cosmic</b></a><br />
      <sub><code>npx typeui.sh pull cosmic</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/creative"><img src="https://www.typeui.sh/registry-examples/creative-marketing.png" alt="Creative" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/creative"><b>Creative</b></a><br />
      <sub><code>npx typeui.sh pull creative</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/enterprise"><img src="https://www.typeui.sh/registry-examples/enterprise-marketing.png" alt="Enterprise" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/enterprise"><b>Enterprise</b></a><br />
      <sub><code>npx typeui.sh pull enterprise</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/dithered"><img src="https://www.typeui.sh/registry-examples/dithered-marketing.png" alt="Dithered" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/dithered"><b>Dithered</b></a><br />
      <sub><code>npx typeui.sh pull dithered</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/doodle"><img src="https://www.typeui.sh/registry-examples/doodle-marketing.png" alt="Doodle" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/doodle"><b>Doodle</b></a><br />
      <sub><code>npx typeui.sh pull doodle</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/dramatic"><img src="https://www.typeui.sh/registry-examples/dramatic-marketing.png" alt="Dramatic" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/dramatic"><b>Dramatic</b></a><br />
      <sub><code>npx typeui.sh pull dramatic</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/editorial"><img src="https://www.typeui.sh/registry-examples/editorial-marketing.png" alt="Editorial" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/editorial"><b>Editorial</b></a><br />
      <sub><code>npx typeui.sh pull editorial</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/elegant"><img src="https://www.typeui.sh/registry-examples/elegant-marketing.png" alt="Elegant" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/elegant"><b>Elegant</b></a><br />
      <sub><code>npx typeui.sh pull elegant</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/pulse"><img src="https://www.typeui.sh/registry-examples/pulse-marketing.png" alt="Pulse" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/pulse"><b>Pulse</b></a><br />
      <sub><code>npx typeui.sh pull pulse</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/stitch"><img src="https://www.typeui.sh/registry-examples/stitch-marketing.png" alt="Stitch" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/stitch"><b>Stitch</b></a><br />
      <sub><code>npx typeui.sh pull stitch</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/expressive"><img src="https://www.typeui.sh/registry-examples/expressive-marketing.png" alt="Expressive" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/expressive"><b>Expressive</b></a><br />
      <sub><code>npx typeui.sh pull expressive</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/fantasy"><img src="https://www.typeui.sh/registry-examples/fantasy-marketing.png" alt="Fantasy" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/fantasy"><b>Fantasy</b></a><br />
      <sub><code>npx typeui.sh pull fantasy</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/fiction"><img src="https://www.typeui.sh/registry-examples/fiction-marketing.png" alt="Fiction" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/fiction"><b>Fiction</b></a><br />
      <sub><code>npx typeui.sh pull fiction</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/flat"><img src="https://www.typeui.sh/registry-examples/flat-marketing.png" alt="Flat" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/flat"><b>Flat</b></a><br />
      <sub><code>npx typeui.sh pull flat</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/friendly"><img src="https://www.typeui.sh/registry-examples/friendly-marketing.png" alt="Friendly" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/friendly"><b>Friendly</b></a><br />
      <sub><code>npx typeui.sh pull friendly</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/futuristic"><img src="https://www.typeui.sh/registry-examples/futuristic-marketing.png" alt="Futuristic" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/futuristic"><b>Futuristic</b></a><br />
      <sub><code>npx typeui.sh pull futuristic</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/glassmorphism"><img src="https://www.typeui.sh/registry-examples/glassmorphism-marketing.png" alt="Glassmorphism" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/glassmorphism"><b>Glassmorphism</b></a><br />
      <sub><code>npx typeui.sh pull glassmorphism</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/gradient"><img src="https://www.typeui.sh/registry-examples/gradient-marketing.png" alt="Gradient" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/gradient"><b>Gradient</b></a><br />
      <sub><code>npx typeui.sh pull gradient</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/immersive"><img src="https://www.typeui.sh/registry-examples/immersive-marketing.png" alt="Immersive" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/immersive"><b>Immersive</b></a><br />
      <sub><code>npx typeui.sh pull immersive</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/impeccable"><img src="https://www.typeui.sh/registry-examples/impeccable-marketing.png" alt="Impeccable" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/impeccable"><b>Impeccable</b></a><br />
      <sub><code>npx typeui.sh pull impeccable</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/levels"><img src="https://www.typeui.sh/registry-examples/levels-marketing.png" alt="Levels" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/levels"><b>Levels</b></a><br />
      <sub><code>npx typeui.sh pull levels</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/lingo"><img src="https://www.typeui.sh/registry-examples/lingo-marketing.png" alt="Lingo" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/lingo"><b>Lingo</b></a><br />
      <sub><code>npx typeui.sh pull lingo</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/luxury"><img src="https://www.typeui.sh/registry-examples/luxury-marketing.png" alt="Luxury" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/luxury"><b>Luxury</b></a><br />
      <sub><code>npx typeui.sh pull luxury</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/material"><img src="https://www.typeui.sh/registry-examples/material-marketing.png" alt="Material" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/material"><b>Material</b></a><br />
      <sub><code>npx typeui.sh pull material</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/matrix"><img src="https://www.typeui.sh/registry-examples/matrix-marketing.png" alt="Matrix" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/matrix"><b>Matrix</b></a><br />
      <sub><code>npx typeui.sh pull matrix</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/minimal"><img src="https://www.typeui.sh/registry-examples/minimal-marketing.png" alt="Minimal" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/minimal"><b>Minimal</b></a><br />
      <sub><code>npx typeui.sh pull minimal</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/modern"><img src="https://www.typeui.sh/registry-examples/modern-marketing.png" alt="Modern" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/modern"><b>Modern</b></a><br />
      <sub><code>npx typeui.sh pull modern</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/mono"><img src="https://www.typeui.sh/registry-examples/mono-marketing.png" alt="Mono" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/mono"><b>Mono</b></a><br />
      <sub><code>npx typeui.sh pull mono</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/neon"><img src="https://www.typeui.sh/registry-examples/neon-marketing.png" alt="Neon" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/neon"><b>Neon</b></a><br />
      <sub><code>npx typeui.sh pull neon</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/neobrutalism"><img src="https://www.typeui.sh/registry-examples/neobrutalism-marketing.png" alt="Neobrutalism" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/neobrutalism"><b>Neobrutalism</b></a><br />
      <sub><code>npx typeui.sh pull neobrutalism</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/neumorphism"><img src="https://www.typeui.sh/registry-examples/neumorphism-marketing.png" alt="Neumorphism" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/neumorphism"><b>Neumorphism</b></a><br />
      <sub><code>npx typeui.sh pull neumorphism</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/pacman"><img src="https://www.typeui.sh/registry-examples/pacman-marketing.png" alt="Pacman" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/pacman"><b>Pacman</b></a><br />
      <sub><code>npx typeui.sh pull pacman</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/paper"><img src="https://www.typeui.sh/registry-examples/paper-marketing.png" alt="Paper" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/paper"><b>Paper</b></a><br />
      <sub><code>npx typeui.sh pull paper</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/perspective"><img src="https://www.typeui.sh/registry-examples/perspective-marketing.png" alt="Perspective" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/perspective"><b>Perspective</b></a><br />
      <sub><code>npx typeui.sh pull perspective</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/premium"><img src="https://www.typeui.sh/registry-examples/premium-marketing.png" alt="Premium" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/premium"><b>Premium</b></a><br />
      <sub><code>npx typeui.sh pull premium</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/professional"><img src="https://www.typeui.sh/registry-examples/professional-marketing.png" alt="Professional" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/professional"><b>Professional</b></a><br />
      <sub><code>npx typeui.sh pull professional</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/basic"><img src="https://www.typeui.sh/registry-examples/basic-marketing.png" alt="Basic" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/basic"><b>Basic</b></a><br />
      <sub><code>npx typeui.sh pull basic</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/refined"><img src="https://www.typeui.sh/registry-examples/refined-marketing.png" alt="Refined" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/refined"><b>Refined</b></a><br />
      <sub><code>npx typeui.sh pull refined</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/retro"><img src="https://www.typeui.sh/registry-examples/retro-marketing.png" alt="Retro" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/retro"><b>Retro</b></a><br />
      <sub><code>npx typeui.sh pull retro</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/riso"><img src="https://www.typeui.sh/registry-examples/riso-marketing.png" alt="Riso" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/riso"><b>Riso</b></a><br />
      <sub><code>npx typeui.sh pull riso</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/sega"><img src="https://www.typeui.sh/registry-examples/sega-marketing.png" alt="Sega" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/sega"><b>Sega</b></a><br />
      <sub><code>npx typeui.sh pull sega</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/shadcn"><img src="https://www.typeui.sh/registry-examples/shadcn-marketing.png" alt="Shadcn" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/shadcn"><b>Shadcn</b></a><br />
      <sub><code>npx typeui.sh pull shadcn</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/simple"><img src="https://www.typeui.sh/registry-examples/simple-marketing.png" alt="Simple" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/simple"><b>Simple</b></a><br />
      <sub><code>npx typeui.sh pull simple</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/sketch"><img src="https://www.typeui.sh/registry-examples/sketch-marketing.png" alt="Sketch" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/sketch"><b>Sketch</b></a><br />
      <sub><code>npx typeui.sh pull sketch</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/skeumorphism"><img src="https://www.typeui.sh/registry-examples/skeumorphism-marketing.png" alt="Skeumorphism" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/skeumorphism"><b>Skeumorphism</b></a><br />
      <sub><code>npx typeui.sh pull skeumorphism</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/sleek"><img src="https://www.typeui.sh/registry-examples/sleek-marketing.png" alt="Sleek" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/sleek"><b>Sleek</b></a><br />
      <sub><code>npx typeui.sh pull sleek</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/spacious"><img src="https://www.typeui.sh/registry-examples/spacious-marketing.png" alt="Spacious" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/spacious"><b>Spacious</b></a><br />
      <sub><code>npx typeui.sh pull spacious</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/storytelling"><img src="https://www.typeui.sh/registry-examples/storytelling-marketing.png" alt="Storytelling" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/storytelling"><b>Storytelling</b></a><br />
      <sub><code>npx typeui.sh pull storytelling</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/terracotta"><img src="https://www.typeui.sh/registry-examples/terracotta-marketing.png" alt="Terracotta" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/terracotta"><b>Terracotta</b></a><br />
      <sub><code>npx typeui.sh pull terracotta</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/tetris"><img src="https://www.typeui.sh/registry-examples/tetris-marketing.png" alt="Tetris" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/tetris"><b>Tetris</b></a><br />
      <sub><code>npx typeui.sh pull tetris</code></sub>
    </td>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/vibrant"><img src="https://www.typeui.sh/registry-examples/vibrant-marketing.png" alt="Vibrant" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/vibrant"><b>Vibrant</b></a><br />
      <sub><code>npx typeui.sh pull vibrant</code></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%" valign="top">
      <a href="https://typeui.sh/design-skills/vintage"><img src="https://www.typeui.sh/registry-examples/vintage-marketing.png" alt="Vintage" width="260" /></a><br />
      <a href="https://typeui.sh/design-skills/vintage"><b>Vintage</b></a><br />
      <sub><code>npx typeui.sh pull vintage</code></sub>
    </td>
    <td align="center" width="33%"></td>
    <td align="center" width="33%"></td>
  </tr>
</table>

## Usage

### Pull a skill into your project

Use the [typeui.sh CLI](https://github.com/bergside/typeui.sh) to pull any skill by its slug:

```bash
npx typeui.sh pull <slug>
```

The CLI will fetch the `SKILL.md` file from this registry and write it to your configured provider paths (e.g., `.cursor/skills/`, `.claude/`, etc.). The companion `DESIGN.md` remains in this repo alongside each skill for reference and maintenance.

### Specify providers

Target specific agentic tools when pulling:

```bash
npx typeui.sh pull glassmorphism -p cursor,claude
```

### Preview before writing

Use `--dry-run` to see what would be written without making changes:

```bash
npx typeui.sh pull glassmorphism --dry-run
```

### Browse and pull interactively

List all available skills with preview links, then pull one:

```bash
npx typeui.sh list
```

### Generate a custom skill

Run the interactive prompts to create your own design system skill:

```bash
npx typeui.sh generate
```

## Registry Structure

Each skill lives in its own folder under `skills/`:

```
skills/
├── index.json          # Slug-keyed map for fast CLI lookups
├── glassmorphism/
│   ├── SKILL.md        # AI-agent instruction file
│   └── DESIGN.md       # Human-readable design companion
├── brutalism/
│   ├── SKILL.md
│   └── DESIGN.md
├── minimal/
│   ├── SKILL.md
│   └── DESIGN.md
└── ...
```

The `index.json` file maps each slug to its skill path:

```json
{
  "glassmorphism": {
    "slug": "glassmorphism",
    "name": "Glassmorphism",
    "skillPath": "skills/glassmorphism/SKILL.md"
  }
}
```

When you run `npx typeui.sh pull <slug>`, the CLI reads this index, resolves the skill path, and fetches the corresponding `SKILL.md` file. `DESIGN.md` is stored next to each skill for human-facing documentation.

## Contributing

Contributions are welcome! If you'd like to add a new design skill to the registry:

1. Create a new folder under `skills/` with your slug name
2. Add a `SKILL.md` file following the existing format
3. Add a companion `DESIGN.md` file in the same folder
4. Add an entry to `skills/index.json`
5. Submit a pull request

Please ensure your skill file includes all required sections: mission, brand, style foundations, component families, accessibility rules, writing tone, do/don't rules, and quality gates.

## License

[MIT License](LICENSE) &copy; Built and maintained by [Bergside](https://github.com/bergside).

## Sponsors

A huge thank you to the companies supporting our open-source work.

<table width="100%">
  <tr>
    <td align="center" width="33%">
      <a href="https://www.skybridge.tech/" target="_blank" rel="noopener noreferrer">
        <img src="https://github.com/user-attachments/assets/88c401ee-b19b-4b78-9a7e-325337dba529" alt="Skybridge" width="300" />
        <br /><b>Skybridge</b>
      </a>
    </td>
  </tr>
</table>

Want to see your logo here? [Become a sponsor](https://www.typeui.sh/sponsor).