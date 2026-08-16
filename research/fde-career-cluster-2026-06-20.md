# FDE career cluster research note - 2026-06-20

## Page jobs

| Page | Target URL | Primary reader question | Page type | Boundary |
| --- | --- | --- | --- | --- |
| How to Become a Forward Deployed Engineer | `/fde/careers/` | How do I become an FDE? | Career guide | Owns preparation path, portfolio proof, and readiness signals. It must not duplicate the full job definition page. |
| Forward Deployed Engineer Interview Questions | `/fde/careers/interview/` | What questions should I prepare for in FDE interviews? | Interview guide | Owns practice questions and answer structure. It must not become a generic job description. |
| Forward Deployed Engineer Resume | `/fde/careers/resume/` | How should I write an FDE resume? | Resume guide | Owns resume framing and bullet evidence. It must not become a general career roadmap. |

## Sources checked

| Source | URL | Type | Stability | Facts or search intent used |
| --- | --- | --- | --- | --- |
| OpenAI Ashby jobs board | `https://jobs.ashbyhq.com/openai` | Primary employer source | Unstable; role pages change often | Checked 2026-06-20. The board lists multiple Forward Deployed Engineer and Forward Deployed Software Engineer openings across locations. Used for the broad claim that OpenAI treats FDE as a current role family. |
| OpenAI Forward Deployed Engineer role pages | `https://jobs.ashbyhq.com/openai` | Primary employer source | Unstable; job postings | Used for role pattern only: customer embedding, production systems, full-stack/backend implementation, frontier model deployment, feedback loops into product/research. |
| Anthropic Greenhouse jobs board | `https://job-boards.greenhouse.io/anthropic` | Primary employer source | Unstable; jobs board | Checked for Applied AI and adjacent production/customer AI roles. Used as directional evidence that AI companies organize work around deployment, production, customer use, and applied AI. |
| Palantir AI FDE overview | `https://www.palantir.com/docs/foundry/ai-fde/overview/` | Primary product documentation | Moderately stable | Used to ground AI-era FDE language around building AI workflows close to operational use rather than treating FDE as only a career title. |
| Palantir careers and public FDE search results | `https://www.palantir.com/careers/` | Primary employer source | Unstable; role pages change often | Used for role pattern only: FDSE/FDE roles emphasize customer work, engineering, data, and implementation close to real problems. |
| Exponent FDE resume page | `https://www.tryexponent.com/blog/forward-deployed-engineer-resume-examples-skills-2026` | Competitor/search-intent source | Unstable; SEO page | Used only to understand resume search intent: readers want examples, skills, bullets, and FDE-specific framing. Not used as factual authority. |
| Common SERP patterns for `how to become a forward deployed engineer`, `forward deployed engineer interview questions`, and `forward deployed engineer resume` | Web search checked 2026-06-20 | Search intent research | Unstable | Search results skew toward role definitions, resume examples, interview prep, and generic career guides. iRizwan pages need stronger operating-model framing, production constraints, field judgment, and AI deployment specificity. |

## Source-backed facts translated into article claims

| Claim in article | Source basis | How it appears without copied phrasing |
| --- | --- | --- |
| FDE preparation should include production-grade code, customer-facing work, data/integration judgment, deployment, and product feedback. | OpenAI role pattern, Palantir FDE/FDSE public material, Anthropic Applied AI role ecosystem | The articles state that current public role descriptions signal the same blend, without quoting job postings or linking externally in body copy. |
| AI-era FDE work requires evals, retrieval, tool use, prompt/version management, latency, privacy, cost, and human review. | OpenAI FDE/product AI deployment language, Palantir AI FDE docs, Anthropic Applied AI context | The articles frame AI as deployment-specific rather than only model-specific. |
| Resume pages should answer examples/skills/bullets intent. | SERP and competitor review | The resume page includes concrete bullet shapes and mistakes instead of generic resume advice. |
| Interview pages should cover coding, systems, data, AI, product judgment, customer discovery, and behavioral examples. | Role requirement patterns and interview-intent SERPs | The interview page uses question banks grouped by the actual FDE operating loop. |

## Internal structure decisions

- Use `/fde/careers/` for the primary career guide because the project rules prefer short, stable child slugs.
- Use `/fde/careers/interview/` and `/fde/careers/resume/` because these are deeper career-intent subtopics that can stand alone.
- Keep visible article links internal-first. No external article-body links were added.
- Add navigation entries under a `Careers` group so the pages are discoverable.
- Update the FDE hub only where it already answers career questions, so the new pages do not remain orphaned.

## Article build decision

Decision: `Research build complete`.

Remaining risk: job-market pages change often, so any future salary, employer-specific, or role-specific claims should be rechecked before publishing or expanding these pages.
