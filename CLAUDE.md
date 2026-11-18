# BedrockIQ

Sito statico di consulenza e formazione per ristoratori ("Bedrock — Strong foundations. Real results.").

## Stack
- HTML/CSS/JS statico, file singoli autonomi (`index.html`, `corsi.html`, `bedrock-social.html`, `healthcheck.html`).
- Form via Formspree. Font: Playfair Display. Variabili CSS (`--ink`, `--cream`).
- Contenuti in italiano.

## Pagine
- `index.html` — home, diagnosi → azione, contatti.
- `corsi.html` — formazione per ristoratori.
- `bedrock-social.html` — gestione social, guide operative.
- `healthcheck.html` — questionario diagnostico con risultato dinamico.

## Regole di lavoro
- Copy: italiano, diretto, orientato al risultato per ristoratori.
- Mobile-first, accessibile (WCAG AA), nessuna dipendenza di build.
- Ogni modifica: verifica a 375px e 1280px.
- Niente segreti nel codice; endpoint Formspree pubblico è ok.

## Toolkit (da Everything Claude Code, vedi `.claude/ECC-SOURCE`)
- Agent: `planner`, `code-reviewer`, `security-reviewer`, `seo-specialist`, `marketing-agent`, `a11y-architect`.
- Skill: `seo`, `frontend-design-direction`, `frontend-patterns`, `accessibility`, `brand-voice`, `content-engine`, `marketing-campaign`, `market-research`.
- Comandi: `/plan`, `/marketing-campaign`.
