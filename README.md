# Hi, I'm Rohan 👋

**Product manager in Toronto.** 13 years in tech, 8 in product, mostly B2B SaaS.

I like building things that don't exist yet, usually in industries where mistakes are expensive: insurance, trade finance, payments and hospitality operations. Today I'm a PM at **Actabl**, where I own the web and mobile products that hospitality businesses use for asset maintenance and operations.

On the side, I build my own tools with **Claude Code**. It's the fastest way I've found to learn how AI products actually get made.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-rohan--soni--product-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rohan-soni-product)
[![Redline](https://img.shields.io/badge/Live_project-Redline-D7263D?style=flat&logo=vercel&logoColor=white)](https://redline-mauve.vercel.app/)

---

## 🧭 How I work

- **Work backwards from the customer.** Start from the pain, not the feature list.
- **Size the downside of a new bet first**, so the pilot is cheap to run and easy to stop.
- **When something breaks, add the check that was missing.** A pilot gate before a full build. Failsafes so one failed integration can't block a transaction. I'd rather fix the system than ask people to be more careful.

---

## 🛠️ Product skills

| Area | What that looks like |
|---|---|
| **Strategy & roadmaps** | Product vision and roadmap set with the C-suite and key customers. Quarterly product reviews with leadership. |
| **0-to-1** | Took a gamification module from idea to launch. Piloted UPI tap-and-pay on wearables in India before the major payment apps had shipped it. |
| **AI & ML products** | Owned an AI feature end to end: users photograph an asset and AI builds the record. Worked with Data Science to improve ML model recall on trade documents. |
| **Discovery & analytics** | User research, funnel, cohort and path analysis, SQL. Selected and rolled out Pendo for product analytics. Tableau. |
| **Experimentation** | A/B tests and fake-door tests at consumer scale, used to decide what gets built and which partners get integrated. |
| **Payments & fintech** | UPI, tokenized payments, dispute redressal, merchant and partner integrations, REST APIs. |
| **Regulated domains** | Trade finance document compliance, U.S. P&C insurance, payments. |
| **Delivery** | Agile/Scrum, Jira, Figma prototyping. Cross-functional teams across Engineering, UX, QA, DevOps, Sales, CS and Legal. |

---

## 🤖 Claude Code

I work in Claude Code daily and customize it heavily. What I've set up:

- **Spec-driven builds.** PRD first, decisions recorded as ADRs, the spec broken into GitHub issues, then Claude Code builds against the tickets test-first. It's the same discipline I'd expect from a product team, applied to an agent.
- **Custom subagents.** Read-only reviewers that run in an isolated context, so they judge what's actually on the page and not the reasoning that produced it. They propose fixes; they never edit.
- **Hooks.** A `PostToolUse` hook runs a TypeScript linter after every edit and feeds new findings straight back to the agent, with a regression test suite behind the linter.
- **Custom skills.** One, for example, takes a corrected fact, updates every occurrence across a repo, and re-checks until zero stale copies remain.
- **`CLAUDE.md` as operating rules.** Guardrails, sync rules between files, and a retro log where any mistake that happens twice has to get a structural fix. "Be more careful" doesn't count.
- **Skill libraries I use:** Superpowers (brainstorm → plan → TDD → review), Matt Pocock's skills, Impeccable for UI design.

---

## 🚀 Featured project

### [Redline](https://redline-mauve.vercel.app/) · [repo](https://github.com/rohanssoni/redline)

**Reads an agreement you're about to sign and tells you what it actually says.** Built for freelancers who can't justify a lawyer for every contract.

- A plain-English summary
- Flags and missing protections in one list ranked by severity, **each showing the sentence it came from**
- A counter-offer for every flag, soft or firm, your choice
- A question box that answers **only from the document**
- Your own editable red line list, which drives the analysis

**How it was built:** product work first. A PRD, 22 architecture decision records, and a spec split into 19 tickets. Claude Code then built all 19 in one autonomous run: 454 tests, a clean type check and a green build.

`Next.js` · `Supabase` · `Vercel` · `OpenRouter` · `Vitest` · `pdf.js`

---

## 📍 Path so far

| | |
|---|---|
| **Actabl** | Product Manager · U.S. B2B SaaS · asset maintenance and operations for hospitality |
| **Xiaomi India** | Product Manager · Mi Pay, a UPI mobile payments app with millions of registered users |
| **Traydstream** | Senior Manager, Product · UK trade finance platform · AI/ML roadmap and key client accounts |
| **SPJIMR** | PGPM, Information Management |
| **Deloitte** | Product Consultant · moved from QA into product for U.S. P&C insurance clients |
| **LTI** | Test Engineer · QA on a large U.S. insurer's policy systems |

---

## 🧰 Tools

![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=claude&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Pendo](https://img.shields.io/badge/Pendo-EC2059?style=flat)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white)

---

💬 **Happy to talk about** B2B SaaS, AI products, payments, or how to get real work out of Claude Code. [LinkedIn](https://www.linkedin.com/in/rohan-soni-product) is the best place to reach me.
