# Hi, I'm Marius Kalder

Technical Product Owner. Hands-on builder. Allergic to solutions looking for a problem.

I work where product decisions meet technical reality:
unclear requirements, legacy systems, competing priorities and software that actually has to ship.

I work across different stakeholder perspectives and adapt my communication to the people involved.
I'm at my best working closely with developers, architects and business stakeholders:
short feedback loops, direct conversations and a shared understanding of the problem.

Outside my professional work, I build independent software products.
Not just to try another stack, but to own the whole loop:
understand the problem, make the trade-offs, build the thing and find out whether it helps.

I'm also the founder of [prodowner](https://www.prodowner.de).
I build applications with open-weight models and put their results to the test.

Working software is the starting point. Useful output is the question.
I document what works, what breaks and which decisions follow.

For these independent projects, the code, the trade-offs and the responsibility are mine.

[Portfolio & case studies](https://www.mariuskalder.de/projects/) · [LinkedIn](https://www.linkedin.com/in/MariusKalder)

## My focus

- **Product ownership that goes beyond moving tickets**: clarify the problem, define acceptance criteria and turn uncertainty into deliverable increments.
- **Technical decisions with the consequences attached**: architecture, dependencies, maintenance and the people needed to make it work.
- **AI with boundaries**: deterministic rules where possible, model assessments where useful, human judgment where it matters.
- **Legacy systems**: reconstruct the business logic before promising the migration date.
- **Validation**: a working MVP proves that something runs. Not necessarily that anyone needs it.

## Things I've built

### Phrom — your backlog gets a review, not an AI takeover

A human-in-the-loop tool that checks GitHub Issues before backlog refinement.

The goal is simple: spend less of the team's conversation figuring out what a ticket
is trying to say, and more of it understanding the actual work.

Phrom combines versioned rules with LLM assessments through Ollama.
It flags gaps and generates improvement drafts on request.

It never changes your GitHub Issues. You review. You decide. You apply.

Under the hood:

- Deterministic checks for structural requirements.
- Labeled AI assessments for semantic questions.
- Configurable scoring and a Ready Gate for required criteria.
- Markdown and JSON reports.
- Architecture decisions, technical evaluations and documented limitations.

Current status: a working MVP with a documented technical evaluation using my own test set.
Real-world time savings and value for Product Owners have not yet been established.
Generated drafts can invent details or omit existing information and require careful review.

Stack: Node.js · Express · GitHub REST API · Ollama · JSON-based rules

[Code](https://github.com/MKalder/phrom) ·
[Demo backlog](https://github.com/MKalder/phrom-backlog-demo) ·
[Architecture decisions](https://github.com/MKalder/phrom/tree/main/adr/en) ·
[Case study](https://www.mariuskalder.de/projects/phrom-ai-assisted-backlog-refinement) ·
[The story on Medium](https://medium.com/@marius.kalder/as-a-technical-product-owner-i-built-an-ai-tool-that-reviews-my-github-backlog-but-never-changes-328c6c329a2c)

## Currently working on

### A vocabulary trainer for technical English

Learn from the pages you actually read.

Capture expressions from docs, articles and issues, understand how they're used,
and review them with spaced repetition.

Vocabulary capture and review are implemented.
The technical-English focus and additional exercises based on your own reading context
are the next steps.

### A benchmarking tool for local language models

Answers are easy. Evidence takes work.

I'm developing a tool to compare local models on task-specific test cases:
output quality, runtime and infrastructure requirements.

The question isn't “which model is best?”
It's “which model is useful for this task — on the hardware I have?”

## Not just side projects

My professional work has involved larger teams, existing systems and tight deadlines.

- E-mobility e-commerce: Technical Product Ownership for bringing wallboxes
  and electricity tariffs into one purchasing journey, delivered incrementally.
- Telecommunications platform migration: reconstructing undocumented deposit-shop
  requirements and helping complete a multi-year microfrontend migration.
- IT portfolio management: turning roughly 25 poorly defined tickets into
  14 initiatives with scope, costs, timelines and business cases.

The interesting part isn't the project title.
It's what was unclear, which options we had, what we chose and what that decision cost.

That's what I write about.

[Explore the case studies](https://www.mariuskalder.de/projects)

## My operating principles

Understand the problem before expanding the solution.

Make the trade-offs visible. Especially the uncomfortable ones.

Don't ask an LLM to do what a small function can check.

Write down decisions so the next person doesn't have to excavate them.

Ship something small enough to learn from.

Then check whether it deserved to be built.

---

Have a concrete problem, a difficult product decision or feedback on something I've built?

[Let's talk](https://www.mariuskalder.de/contact).
