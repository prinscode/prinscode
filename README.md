# Jos Prins

Frontend engineer building reliable product interfaces and applied AI systems.

I work primarily with TypeScript, Vue and React/Next.js. My focus is the engineering behind a polished interface: explicit data contracts, accessible interaction, resilient service boundaries and tests that protect real user journeys. I also help teams modernize Vue applications without turning a migration into a rewrite.

## Selected work

### [Gym Tracker](https://github.com/prinscode/gym-tracker)

A local-first Vue application for planning, running and analysing strength workouts.

- Recoverable sessions and serialized IndexedDB persistence
- Versioned, validated and transactional import/export
- Tested training analytics and personal-record detection
- Desktop/mobile journeys with automated accessibility and performance budgets
- Architecture decisions documented alongside their trade-offs

[View the repository](https://github.com/prinscode/gym-tracker) · [Read the v1.0.0 release](https://github.com/prinscode/gym-tracker/releases/tag/v1.0.0)

## Applied AI and data products

My current private case studies explore two complementary problems:

- **Natural-language workout logging:** model output is treated as untrusted input, validated against typed schemas and measured with a versioned 100-case evaluation set. Provider calls, Telegram delivery and billing webhooks have explicit timeout, retry, authentication and deduplication boundaries.
- **Country comparison:** World Bank responses are validated before presentation, missing observations remain distinct from zero, partial failures stay visible, and browser tests run against deterministic local fixtures.

These projects remain private while their public demos and evaluation baselines are prepared. I prefer an honest limitation over a polished claim that cannot be reproduced.

## How I work

- Start with the user journey and its failure modes.
- Keep external data and model output behind validated boundaries.
- Test business rules low in the pyramid and reserve browser tests for critical flows.
- Treat accessibility, performance, privacy and operability as product requirements.
- Record consequential decisions, including rejected alternatives and residual risks.

## Contact

[LinkedIn](https://www.linkedin.com/in/jos-prins-bba29621/) · [Email](mailto:jco.prins@me.com)
