# AGENTA – Kommentar-Threads zu ausgewählten Learning Goals

Quelle: `curriculum-agenta-en_Kommentiert_v2.pdf` (2026.1-RC1-EN-20260612)

---

## LG 1-2 – Being familiar with the fundamentals of large language models (LLMs) and their core concepts and terminology

*Verankert am Bullet „Participants understand LLMs as non-deterministic tools and can explain the implications for architecture work."*

- **Michael Sperber:** As an algorithmic principle, LLMs are not non-deterministic. Do you mean: „commonly available commercial LLMs"? Or do you mean „intransparent" instead of „non-deterministic"?
- **Tebea Hentschel:** Change to „probabilistic"

---

## LG 2-1 – Understand the impact of AI on the lifecycle of architectural decisions

*Verankert am Bullet „understand the effect of agentic engineering: It accelerates exploration and (prototype) development…"*

- **Michael Sperber:** This is a statement of fact which is, AFAIK, not empirically grounded. Maybe replace by „can accelerate exploration".
- **Tebea Hentschel:** We can weaken it to „can increase" instead of the matter of fact statement.

---

## LG 2-5 – Be able to treat architectural decisions as testable hypotheses (Thread 2)

*Verankert an „expected quality effects".*

- **Michael Sperber:** What's a „quality effect"?
- **Tebea Hentschel:** Refine to „expected impact on the systems quality characteristics".

---

## LG 2-6 – Understand the limitations of AI in architectural decision support

*Verankert am Bullet „Participants are able to define review checkpoints and know how to maintain human responsibility over consequential architectural decisions".*

- **Michael Sperber:** Is the idea here that the „review checkpoints" are the means to „maintain human responsibility"? If so, say so. If not, what are (the) means here?
- **Tebea Hentschel:** refine to „how to maintain human responsibility over consequential architectural decisions by enforcing these checkpoints and using additional methods (like setting boundaries to Agentic Decisions, enforcing Guardrails a.s.o.)". We don't want a closed list here, as this will likely evolve and should be in the competence of training providers.

---

## LG 4-1 – Understand why AI agents require explicit architectural control

*Verankert am Bullet „Participants understand that explicit architectural controls should only be built and maintained as long as the model itself is not able to reliably perform the controls itself."*

- **Michael Sperber:** I don't understand what this means. What exactly are the circumstances in which a model is „reliably perform the controls itself" (or perform anything reliably).
- **Tebea Hentschel:** We should rewrite this to be more understandable. Sure. The capabilities of Models and Coding Agents are constantly improving. In essence you should build a „sinking" solution to architectural validation as they may hinder evolvability.

---

## LG 4-2 – Be able to design a harness that enforces architectural decisions on AI-generated work (Thread 2)

*Verankert an „Participants can select appropriate enforcement mechanisms for different kinds of architectural concerns … and can explain why some concerns are harder to enforce than others."*

- **Michael Sperber:** It's unclear what the curriculum expects the trainer to say here. Which ones are harder to enforce and why?
- **Tebea Hentschel:** Could add a reference to holistic and atomic Fitness Functions, but to keep it simpler we can add an example where holistic Feedback is hard to come by (maintainability, usability).

---

## LG 5-3 – Know how to use AI and agents to extract architectural information from existing system parts

*Verankert an „Detect technologies and frameworks using code property graphs (e.g. Joern)…".*

- **Michael Sperber:** „Joern" needs a reference
- **Tebea Hentschel:** Will be added

---

## LG 6-1 – Understand, classify, and properly address the legal framework conditions when using AI tools in the organization

*Verankert am Bullet zu Copyright / copyleft licenses.*

- **Michael Sperber:** Shouldn't the curriculum say something along the lines of „Participants understand that an AI-augmented architectural process needs to establish control and process that shields the generated code and artifacts from copyright-related liabilities" or at least „are aware of the legal risks"?
- **Tebea Hentschel:** sure. can be substituted

---

## LG 7-2 – Be able to preserve architectural judgment when using coding agents

*Verankert am Bullet „Participants knows that shared terminology and a consistent domain vocabulary … as anchors that make agent decisions more predictable and aligned with the system's design."*

- **Michael Sperber:** Is that so? Any evidence?
- **Tebea Hentschel:** Yes. Most does perhaps not qualify for your standards, but people share experiences in Articles. Here a paper: https://dl.acm.org/doi/full/10.1145/3697012
