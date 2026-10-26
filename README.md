# Hi, I'm Marcin

Lead Frontend Engineer in Copenhagen. I build agentic software development tools (coding-agent pipelines, the harnesses that keep them safe, and the evals that show they work) on top of 6+ years of product and design system engineering. TypeScript-first.

## What I work on

- **Agents that ship real UI.** At Grundfos I built GDS Studio: designers describe a screen in plain words and an agent builds a working prototype with the real design system. About 20 designers, 150 prototypes, minutes instead of hours.
- **The system decides, not the agent.** Every agent result goes through a validator, typecheck, build and runtime sweep, with up to 2 automatic fix rounds and an eval set run before each release.
- **Design systems.** One of the main developers of the Maersk Design System (69 Lit web components, 90% adoption across 467+ repos), and built the Grundfos design system from zero (60 components, WCAG 2.2 AA).

That work is internal, so it isn't on this profile. What's public is below.

## Building in public

**[Mylder](https://github.com/marcin-sieradzki/mylder)** · [live demo](https://marcin-sieradzki.github.io/mylder/)

A live map of Copenhagen's buses, S-tog, metro and trains that is honest about how fresh each position is: every vehicle is Live, Ageing, Estimated, Timetable only or No signal, and the map never dresses one up as another. Every vehicle moves along its route, with vehicle and stop panels, a City pulse, a searchable vehicle list and disruptions, in English and Danish, light and dark. Next.js, React 19, MapLibre with deck.gl, and an Effect tracker on the server. Until the Rejseplanen API key arrives it runs on a simulated network, and the demo runs that tracker in a Web Worker in your browser.

**[Perron](https://github.com/marcin-sieradzki/perron)** · [docs](https://marcin-sieradzki.github.io/perron/)

Mylder's design system, published as [`@mylder/perron`](https://www.npmjs.com/package/@mylder/perron): design tokens on the W3C DTCG 2025.10 spec, icons, the Mylder mark, and 68 React components and patterns on Base UI, in four locales. It comes with an MCP server, [`@mylder/perron-mcp`](https://www.npmjs.com/package/@mylder/perron-mcp), so coding agents read the tokens, the docs and the pinned library references, and its components are built by an agent factory: a spec goes in, and code, stories, tests and docs come out through a code review gate.

Both are built with Claude Code from GitHub issues: a spec, tracer-bullet tickets, test-first builds and an automated review on every pull request.

## Stack

TypeScript, React, Next.js, Vue 3, Lit, Node.js, Effect · Claude Code, Claude Agent SDK, GitHub Copilot SDK, MCP · Vitest, Playwright, Cypress, Storybook, GitHub Actions

## Contact

[LinkedIn](https://www.linkedin.com/in/marcin-sieradzki-5a9774150/) · marcin.sieradzki97@gmail.com
