# FDE Comparisons Research Note

Checked date: 16 June 2026

Page job:

- Target URL: `https://irizwan.com/fde/job/comparisons/`
- Slug: `/fde/job/comparisons/`
- Primary reader question: What is the difference between a forward deployment engineer and a full-stack engineer or similar customer-facing technical roles?
- Page type: comparison.
- Boundary: This page owns role comparisons and decision tests. `/fde/job/` owns the full FDE job definition, workflow, responsibilities, salary signals, and production boundary. `/fde/job/skills/` owns the detailed skill breakdown.

Sources checked:

1. AWS, "What is Full Stack Development?"
   - URL: https://aws.amazon.com/what-is/full-stack-development/
   - Type: primary/authoritative cloud vendor explainer.
   - Claim used: Full-stack development covers both frontend and backend application development; frontend is user-facing code, backend includes database, integrations, application logic, and processing.
   - Stability: stable definition.
   - Article use: define full-stack scope as code-layer breadth, not customer-outcome ownership.

2. OpenAI, "Forward Deployed Engineer (FDE) - NYC"
   - URL: https://openai.com/careers/forward-deployed-engineer-%28fde%29-nyc-new-york-city/
   - Type: primary employer job posting.
   - Claim used: OpenAI describes FDEs as owning discovery, technical scoping, system design, build, production rollout, production adoption, workflow impact, eval-driven feedback, and product/model roadmap feedback.
   - Stability: current job posting; likely to change.
   - Article use: support the FDE role as customer-embedded, production-outcome, product-feedback work.

3. OpenAI, "Forward Deployed Software Engineer - SF"
   - URL: https://openai.com/careers/forward-deployed-software-engineer-sf-san-francisco/
   - Type: primary employer job posting.
   - Claim used: FDSWE role includes deep customer embedding, full-stack solution design, prototypes and production deployments, hands-on work in customer infrastructure, and codifying delivery patterns.
   - Stability: current job posting; likely to change.
   - Article use: support overlap with full-stack engineering while separating by environment and ownership.

4. Anthropic, "Forward Deployed Engineer, Applied AI"
   - URL: https://job-boards.greenhouse.io/anthropic/jobs/4985877008
   - Type: primary employer job posting.
   - Claim used: Anthropic FDEs embed with strategic customers, ship production applications with Claude models, deliver MCP servers, sub-agents, and agent skills, provide enterprise deployment support, codify repeatable patterns, and feed insights back to Product and Engineering.
   - Stability: current job posting; likely to change.
   - Article use: support AI-era FDE comparison with AI engineer, implementation engineer, and solutions architect.

5. Palantir, "Forward Deployed Software Engineer"
   - URL: https://jobs.lever.co/palantir/dab396d4-2f14-4796-aac0-0d82883dccf0
   - Type: primary employer job posting.
   - Claim used: Palantir describes FDSE as embedded with customers, working on architecture and design, large-scale data, custom applications, customer stakeholders, and end-to-end execution from ideation to deployment.
   - Stability: current job posting; likely to change.
   - Article use: support historical/original role framing and customer-side execution.

6. Salesforce Careers, "Solution Engineer (Pre-Sales)"
   - URL: https://careers.salesforce.com/en/jobs/jr317953/solution-engineer-pre-sales-all-levels/
   - Type: primary employer job posting.
   - Claim used: Salesforce solution engineers solicit business requirements, develop technical sales strategy, configure and demonstrate solutions, align strategy to technology, and support product demonstrations.
   - Stability: current job posting; likely to change.
   - Article use: distinguish solutions engineer and sales engineer from FDE by pre-sales/demo/commercial context.

7. Google Careers, "Customer Engineer Associate, Platform, Google Cloud"
   - URL: https://www.google.com/about/careers/applications/jobs/results/110914304852533958-customer-engineer-associate-platform-google-cloud
   - Type: primary employer job posting.
   - Claim used: Google Cloud customer engineers partner with technical sales, act as technical partner and trusted advisor, troubleshoot questions, run proofs of concept and demos, architect cloud solutions, and drive technical wins and delivery plans.
   - Stability: current job posting; likely to change.
   - Article use: distinguish customer engineer from FDE by technical sales and architecture emphasis, with some overlap around POCs and delivery planning.

8. AWS, "AWS Certified Solutions Architect - Associate"
   - URL: https://aws.amazon.com/certification/certified-solutions-architect-associate/
   - Type: primary certification/role-skill page.
   - Claim used: Solutions architect certification emphasizes designing cost and performance optimized cloud solutions and does not require deep hands-on coding experience.
   - Stability: relatively stable but certification requirements may change.
   - Article use: distinguish solutions architect from FDE by architecture/design emphasis versus production code/customer deployment ownership.

9. Paraform, "FDE vs SE vs CE"
   - URL: https://www.paraform.com/blog/forward-deployed-engineer-vs-solutions-engineer-vs-customer-engineer
   - Type: competitor/market-intent research.
   - Claim used: Competitor page frames FDE as production-code/customer-embedded, SE as pre-sales/demo, and CE as customer adoption/support; useful for reader intent and gap analysis, not primary evidence.
   - Stability: current competitor framing.
   - Article use: search intent check and content gap comparison.

10. Baseten, "What I learned as a forward-deployed engineer working at an AI startup"
    - URL: https://www.baseten.co/blog/what-i-learned-as-a-forward-deployed-engineer-working-at-an-ai-startup/
    - Type: first-person industry article.
    - Claim used: FDE title varies by company; at Baseten, FDE is part of engineering and similar to a technical co-founder for customer AI projects.
    - Stability: stable perspective, not universal.
    - Article use: support caution that titles vary and role descriptions matter more than labels.

Structure decision:

- Open with direct distinction: full-stack breadth versus FDE ownership boundary.
- Use a role comparison table with dimensions: primary object, where work starts, where work ends, customer proximity, code depth, production responsibility, product feedback.
- Include dedicated sections for full-stack engineer, software engineer, solutions engineer/sales engineer, solutions architect, customer engineer, implementation engineer, consultant, AI engineer, product engineer, data/ML engineer, deployment strategist.
- Add practical tests: "what are you accountable for?", "where does the spec come from?", "what happens after go-live?", "does field learning return to product?"
- Use one internal link to `/fde/job/`, one to `/fde/job/skills/`, and one closing link to `/fde/`.

Article build decision:

- Research build complete if local build passes, article renders at `/fde/job/comparisons/`, internal links resolve, SVG loads, and no unintended external article-body links are present.
