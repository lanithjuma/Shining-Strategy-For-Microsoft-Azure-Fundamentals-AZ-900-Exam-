# Shining-Strategy-For-Microsoft-Azure-Fundamentals-AZ-900-Exam-
# ☁️ AZ-900 Prep Hub (Unofficial)

A free, single-page study tool for the Microsoft Azure Fundamentals (AZ-900) exam, built for the **#1MillionDevs Vibe Coding Hackathon**.

> **Disclaimer:** This is an unofficial community project. It is not affiliated with or endorsed by Microsoft. All questions are original and based on the public AZ-900 skills outline on Microsoft Learn. No real exam questions or Microsoft logos are used.

**Theme:** Building Smarter Exam Prep Tools from Our Own Learning Journey.

## The problem

While preparing for AZ-900, we found that:

- practice questions say right or wrong but rarely explain why
- Azure terms are easy to read and easy to forget
- there is no clear signal of when you are ready to book the exam

## The solution: one study loop

| Feature | What the learner gets |
|---|---|
| **Smart Quiz** | 18 original questions across 6 topics, with instant feedback and an explanation for every answer |
| **Readiness Tracker** | Per-topic scores and an overall score. "Ready" means 80%+ overall and at least 60% in every topic |
| **Flashcard Coach** | 13 cards in three Leitner boxes. Missed cards return to box 1 and appear first |
| **Study Planner** | Enter your exam date and daily hours. Study time is split across topics, with more for weak ones |
| **Study Buddy** | Explains terms in simple language with everyday African analogies (matatus, boda bodas, market stalls) |

Topics follow the skills outline: Cloud Concepts, Azure Architecture, Compute & Networking, Storage, Identity & Security, Cost & Governance.

## Run it

No build step and no dependencies.

1. Download `index.html` (the app file).
2. Open it in any modern browser.

Progress is saved in your browser's `localStorage`. Nothing is sent to a server.


## How it works

- Plain HTML, CSS and JavaScript in one file
- Quiz results feed the dashboard and the planner, so one set of scores drives the whole loop
- Flashcard boxes: correct answers move a card up a box, a miss sends it back to box 1, and the next card is always from the lowest box
- Planner weighting: weak topics (low score) get more hours, and untried topics count as weak
- Light and dark mode follow your device

## Built with

- **Claude.ai** for planning, content writing and code generation
- Vibe coding approach: describe the learner problem, generate, then review the content for accuracy

## Prompts used


1. *"Write 3 original multiple-choice AZ-900 questions for [topic] based on the public skills outline. Give 4 options, the correct index, and a one-sentence explanation of why the answer is right and why a common wrong answer is wrong. Do not copy real exam questions."*
2. *"Explain [Azure term] to a beginner in two sentences, then give one everyday example from East Africa."*
3. *"Build a single-file app combining a quiz, Leitner flashcards, a study planner and a readiness dashboard. Label it unofficial."*

## Content accuracy

Questions were written for learning, not copied from any exam. Please check anything important against [Microsoft Learn](https://learn.microsoft.com/credentials/certifications/azure-fundamentals/). Found an error? Open an issue.

## Roadmap

- [ ] Larger question bank per topic (target: 10+ per topic)
- [ ] Live AI Study Buddy (Claude API) with guardrails
- [ ] Local-language explanations
- [ ] Shared progress for study groups
- [ ] Question banks for other fundamentals certifications

## Contributing

Add original questions as pull requests. Each needs a topic, 4 options, the correct answer and an explanation. Please do not submit real exam content.

## License

MIT (add a `LICENSE` file).
