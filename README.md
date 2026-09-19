# Quant Reality Check

An evidence-linked career exploration tool that helps first-time applicants compare quantitative-finance roles, challenge assumptions and choose what to investigate next.

[Live demo](https://quantrealitycheck.netlify.app/) | [GitHub repository](https://github.com/yunlongyang0666-prog/quant-reality-check)

## Problem

Quantitative-career information is abundant but fragmented. Similar titles can describe different work across firms, while different titles can overlap. First-time applicants can struggle to translate job descriptions into realistic preparation decisions.

## Solution

Quant Reality Check combines reviewed role evidence with a guided exploration flow. It explains workstyle signals, preserves company context and directs users back to official sources instead of presenting an unsupported fit score.

## How it works

- Guides users through an 11-question career-context and task-preference flow.
- Produces transparent workstyle directions, a Reality Gap and a Preparation Gap.
- Provides exactly three contextual next actions.
- Includes 23 reviewed early-career roles across 8 selected firms.
- Supports search, filtering and side-by-side comparison of two or three roles.
- Stores progress locally in the browser and does not require an account.

## Tools and technologies

- React
- TypeScript
- HTML and CSS
- Browser `localStorage`
- Netlify for static hosting

The deployed site does not call an external AI model or another runtime API.

## Development approach

This was a team project for Catalyst 2026. The team combined official-source desk research, a 17-response consented convenience sample, two live interview perspectives and one asynchronous student perspective. Product rules were revised when evidence contradicted initial assumptions, and uncertainty was kept visible in the interface.

I originated the core product idea and served as the project lead and main builder. I led the website structure, implementation and complete interface design. Teammates contributed suggestions, research perspectives and feedback, and the team agreed that the project could be included in my public portfolio.

ChatGPT/Codex assisted with prototyping, coding, debugging, document preparation and quality assurance. The team remained responsible for research design, source selection, interpretation, product logic, testing and final decisions.

## Impact and result

The project produced a working, responsive prototype that connects research evidence to a user-facing decision-support flow. Major paths, role filters, comparisons, saved state, mobile layout and downloadable result-card behaviour were tested.

The current evidence does not establish improved career outcomes or employer impact. Those outcomes require future usability and longitudinal validation.

## Research boundaries

- The survey is a small convenience sample and is used as directional evidence.
- The eight firms are mainly large international companies and do not represent the full quant market.
- Role requirements and application status can change after the 22 August 2026 data cut-off.
- Workstyle directions are not a psychometric assessment and do not measure ability or future success.

## Repository contents

- `index.html` - self-contained production build.
- `Quant_Reality_FinalSubmission.zip` - final product and supporting research pack.
