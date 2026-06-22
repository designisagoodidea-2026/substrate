# Substrate

An agentic operating system for design organizations — a reference architecture and working blueprint, presented as a single scrollable site.

Substrate reframes the standard "AI workspace setup" (context files, slash commands, subagents, plan loops, tool connections) as five kinds of asset living in one **memory graph** as versioned nodes — maintained by agents, governed by policy, and graded by evaluation. The site walks through the vision, the seven-layer model, the build-vs-buy verdict, and a phase-by-phase implementation roadmap.

## Live site

https://designisagoodidea-2026.github.io/substrate/

## Structure

This is a single self-contained `index.html` — all CSS and JavaScript are inline, no build step, no dependencies (fonts load from Google Fonts). GitHub Pages serves it as-is.

```
index.html    the entire site
.nojekyll     tells Pages to serve files verbatim
README.md     this file
```

## Run locally

Open `index.html` in any browser, or serve the folder:

```
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Background

Built on two design memos:

- *From Setup to System* — why the five components should become versioned, agent-maintained nodes in one governed graph.
- *The Cultivated Workspace* — the reference architecture and the June 2026 market scan behind the buy / assemble / build verdict.
