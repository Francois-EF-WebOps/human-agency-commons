# Cage Fluency: related-work crosswalk, quotation ledger, and provenance

**Version:** 0.2 research update  
**Prepared:** 2026-10-25  
**Status:** Initial scoped literature scan and artefact audit; not a systematic review.  
**Purpose:** Identify established work that overlaps with Cage Fluency, preserve traceable wording from known artefacts, and distinguish synthesis from evidence.

## 1. What this review can and cannot claim

Cage Fluency is not being treated as a wholly new scientific theory. Its current concepts overlap substantially with established work in cybernetics, viability theory, ecological psychology, resilience engineering, situation awareness, active inference, decision-making under uncertainty, cognitive control, and SRE/incident learning.

The contribution worth testing is narrower: whether the particular *combination and operational packaging*—navigation capability, drift triage, bounded reconnaissance, resource-aware action, option preservation, privacy-conscious archives, and explicit closure—helps people make better decisions in real constraints than existing methods do.

This document is an initial targeted scan, not an exhaustive or systematic literature review. Search coverage is limited by indexing, access, terminology, and the repositories visible to this review. Absence from this document is not evidence that no relevant work exists.

## 2. Provenance: known Cage Fluency mentions and artefacts

### 2.1 User wording preserved from prior conversation

The following wording is recorded in the prior-conversation context as the user's formulation on 2026-08-17. Spelling is preserved as recorded:

> “being able to pivot, flow and adapte through situations and intances planned or unplanned without breaking to the point of no return”

This is the clearest user-origin wording located for the practical intuition behind the framework: adaptation across planned and unplanned situations while avoiding irreversible breakdown.

A later working definition in the framework is:

> “Cage Fluency is the ability to preserve navigation capability while operating inside, through, and—where feasible—outside evolving constraint systems.”

The latter is a stabilised working definition recorded in prior discussion and now present in the repository; it should not be represented as a quotation from an external author.

The associated working definition of Drift is:

> “Drift: The accumulation of differences between reality and the agent’s current projection of reality.”

This is a proposed term within Cage Fluency, not a claim that the term “drift” is new to science or engineering.

### 2.2 Repository artefacts found

**A. Human Agency Commons — framework**

- File: [frameworks/cage-fluency-theory.md](https://github.com/Francois-EF-WebOps/human-agency-commons/blob/main/frameworks/cage-fluency-theory.md)
- Current exact core wording: “preserve navigation capability while operating inside, through, and—where feasible—outside evolving constraint systems.”
- Existing contents include the operating loop; Drift types and triage; control/influence/outside-control zones; time and cognitive load; bounded reconnaissance; Babar archive and closure; evidence discipline; context-specific measures; a job-search example; cross-domain applications; falsifiability questions; and version control.
- Assessment: this is a useful integrative structure, but the presence of these components does not by itself demonstrate novelty or efficacy.

**B. Human Agency Commons — glossary**

- File: [frameworks/cage-fluency-glossary.md](https://github.com/Francois-EF-WebOps/human-agency-commons/blob/main/frameworks/cage-fluency-glossary.md)
- Exact entry: “Drift — Accumulation of differences between reality and the agent's projection of reality.”
- Exact stable distinction: “A working model is not a validated theory.”
- Assessment: the glossary appropriately labels terms as working vocabulary. It should remain subordinate to source-grounded definitions where established disciplines already have terms.

**C. Human Agency Commons — navigation review**

- File: [templates/navigation-review.md](https://github.com/Francois-EF-WebOps/human-agency-commons/blob/main/templates/navigation-review.md)
- Role: turns the vocabulary into a bounded decision exercise. It should be evaluated against existing incident reviews, decision logs, premortems, after-action reviews, and decision-analysis templates rather than assumed to be a new method.

**D. Mozenrath-Pub — interactive prototype**

- File: [App.tsx](https://github.com/Finley-E/Mozenrath-Pub/blob/5e4b22c8f8f3bf1211002c0c662885456ee2d44b/App.tsx)
- Exact phrase in the footer: “Authentic Cage Fluency-designed standalone prototype”
- Related implementation files: [GameMap.tsx](https://github.com/Finley-E/Mozenrath-Pub/blob/main/src/components/GameMap.tsx) and [gameEngine.ts](https://github.com/Finley-E/Mozenrath-Pub/blob/main/lib/gameEngine.ts).
- Observed mechanics: a grid map with path, tree, water, volcano, wind, grass, berry, and shrine tiles; player position and directional movement; explicit world boundaries; obstacle checks; movement success/failure messages; and events for encounters, harvesting, shrines, and memory fragments. The main app also maintains state for weather, time of day, pantry inventory, discovered resources, and saved game slots.
- Exact implementation strings include “Reached edge of localized Munu Sea!”, “Blocked by ${barrier}!”, and “Moved successfully.”
- Potential Cage Fluency mapping (inference, not validated design intent): grid and tile types can represent a partial map; obstacles represent constraints; movement and blocked actions expose available versus unavailable routes; harvesting and inventory represent resource acquisition; weather/time variables represent changing conditions; save slots represent state persistence. This makes the game a promising *candidate demonstration environment* for navigation under constraints.
- Still missing: an explicit mapping from each Cage Fluency principle to a game mechanic, a task specification, success/failure measures, baseline comparison, play-test results, and evidence that the design improves user understanding. The current code shows mechanics, not proof of learning or efficacy.
- Caution: the prototype appears in a separate GitHub account/namespace from Human Agency Commons. The audit records the public artefact without assuming account ownership, authorship rights, or that every design choice is documented.

### 2.3 Related analogies and projects recorded in prior discussion

Prior conversation summaries connect the framework to family systems and FamilyOS, WORLDSELF, 10COgraphie, and analogies involving plant growth through obstacles, revealing fog of war in a strategy game, and navigating game-world systems. These are useful explanatory analogies, but the original full text and exact wording were not available in this targeted artefact scan. They are therefore recorded as *leads to reconcile*, not quoted source material and not evidence for the theory.

The phrase “How do we maintain individual sovereignty, family integrity and increasing optionality while operating inside institutions we do not control?” was previously proposed by the assistant as a possible framing question. It is not recorded here as a direct user quotation.

### 2.4 Search boundary

The GitHub code search returned the Mozenrath-Pub footer as an additional indexed exact mention. The current Human Agency Commons framework, glossary, template, and README were also inspected directly. This is not a complete audit of every private, unindexed, deleted, archived, or inaccessible repository, nor a full export of all historical chats. Additional artefacts should be appended with exact path, date/commit, quotation, author/source status, and relevance when located.

## 3. Related work: concept-by-concept crosswalk

### 3.1 Cybernetics and feedback regulation

**Source:** W. Ross Ashby, *An Introduction to Cybernetics* (1956), section on requisite variety.  
Link: https://ashby.info/Ashby-Introduction-to-Cybernetics.pdf

**Short source quotation:** “Only variety in R can force down variety due to D.”

**Overlap:** Cage Fluency's adaptation to changing constraints, information gathering, feedback, and response options closely resemble regulation under disturbance. Ashby's work also warns that a regulator's capacity is limited by the variety it can detect and respond to.

**Implication:** “Navigation capability” should include the range and reliability of available responses, not only the ability to change one's plan. Bounded reconnaissance is a trade-off: too little information leaves disturbances unregulated; indiscriminate scanning consumes the resources needed to act.

**Boundary:** Requisite variety is a formal cybernetic principle, not proof of the entire Cage Fluency framework. The analogy must be specified carefully for human and social settings.

### 3.2 Viability theory and viability kernels

**Source:** Viability Theory, “Viability Kernel.”  
Link: https://viability-theory.org/en/node/43

**Short source quotation:** “at least one feasible trajectory satisfying the constraints for all future times.”

**Overlap:** This is close to the framework's emphasis on preserving viable options and avoiding irreversible thresholds. Viability theory formalises which states and paths remain feasible under constraints.

**Implication:** “Option preservation” should be made more precise: identify essential constraints, reversible and irreversible actions, and whether at least one acceptable future path remains feasible. “Cage Fluency” should not be used as a synonym for viability theory.

**Boundary:** A formal viability kernel requires a defined state space, dynamics, constraints, and assumptions. A personal checklist does not calculate a true viability kernel unless those elements are operationalised.

### 3.3 Ecological psychology and affordances

**Source:** James J. Gibson, *The Ecological Approach to Visual Perception* (1979); overview by Anthony Chemero, Open Encyclopedia of Cognitive Science (2024).  
Links: https://patterns.architexturez.net/doc/az-cf-193204 and https://oecs.mit.edu/pub/984ungzu

**Short source quotation:** “The affordances of the environment are what it offers the animal.”

**Overlap:** Navigation is not only representing a map; it is perceiving actionable possibilities relative to the agent's capabilities and environment. The same environment can offer different actions to agents with different skills, tools, bodies, permissions, or resources.

**Implication:** The framework should record *available actions and their preconditions*, not merely constraints and labels. An option is real only if it is feasible for this agent in this context.

**Boundary:** Affordances are not just subjective beliefs or a list of choices. The concept has competing interpretations and should be used with its ecological-psychology context intact.

### 3.4 Resilience engineering and graceful adaptation

**Source:** Erik Hollnagel, “What is Resilience Engineering?” via the Resilience Engineering Association.  
Link: https://www.resilience-engineering-association.org/what-is-resilience-engineering/

**Short source quotation:** “adjust its functioning prior to, during, or following events.”

**Overlap:** Both approaches address adjustment under expected and unexpected change. Resilience engineering has mature work on monitoring, anticipating, responding, and learning in complex systems.

**Implication:** Cage Fluency should cite resilience engineering as a principal predecessor and compare its practical loop against established resilience-engineering methods. It should not claim to have originated adaptation under disturbance.

**Boundary:** Resilience, robustness, recovery, and adaptability are not interchangeable. The relevant property and time horizon need to be stated for each use case.

### 3.5 Situation awareness and imperfect projections

**Source:** NASA, *Human Performance and Error*, section 5.1.6, Situation Awareness.  
Link: https://www.nasa.gov/reference/5-0-human-performance-and-error-vol-2/

**Short source quotation:** “understanding the current context and environment.”

**Overlap:** Cage Fluency's map/projection, orientation, observation, and anticipation overlap with situation awareness: understanding current conditions, interpreting them against goals, and projecting likely future states.

**Implication:** Distinguish (a) observing a signal, (b) understanding its significance, and (c) projecting what may happen next. Measure whether each step was adequate; do not collapse all three into “the map.”

**Boundary:** Situation awareness has domain-specific models and measures, especially in safety-critical work. A general-purpose personal template should not be described as a validated situation-awareness instrument.

### 3.6 Active inference and predictive models

**Source:** “Active inference on discrete state-spaces: A synthesis” (2020), open access via PubMed Central.  
Link: https://pmc.ncbi.nlm.nih.gov/articles/PMC7732703/

**Short source quotation:** “beliefs are continuously updated to mirror the environment and its dynamics.”

**Overlap:** The framework's Drift concept resembles discrepancies between a generative model or belief state and incoming observations. Active inference also connects model updating with action selection under uncertainty.

**Implication:** Treat Drift as a useful descriptive label, not as a new discovery. In any operational use, separate observed prediction error from the proposed explanation for that error, and include uncertainty and alternative models.

**Boundary:** Active inference is a formal research programme with specific mathematical assumptions. A plain-language Observe–Compare–Adapt cycle is not itself active inference, and this source does not validate Cage Fluency as a whole.

### 3.7 OODA, orientation, and decision cycles

**Source:** “Automating the OODA loop in the age of intelligent machines…” (2022) and “Imaginaries of omniscience…” (2023), both discussing Boyd's model and its simplified popular depiction.  
Links: https://www.tandfonline.com/doi/full/10.1080/14702436.2022.2102486 and https://pmc.ncbi.nlm.nih.gov/articles/PMC10543130/

**Short source quotation:** “orientation shapes the way we observe, the way we decide, the way we act.”

**Overlap:** The Cage Fluency operating loop shares the broad pattern of sensing, orientation, decision, action, and feedback.

**Implication:** Cite OODA as a comparison, not a synonym. Retain the role of experience, culture, previous assumptions, implicit action, and feedback; do not present the Cage Fluency loop as a novel cycle.

**Boundary:** Scholarly discussions caution that the popular four-step circular diagram can oversimplify Boyd's more interconnected conception. Cage Fluency should likewise be treated as a practical aid, not a universal description of cognition.

### 3.8 Cognitive control and task switching

**Sources:** Stephen Monsell, “Task switching” (2003); Kiesel et al., “Control and interference in task switching—a review” (2010); “What are we measuring when we measure task switch costs?” (2024).  
Links: https://pubmed.ncbi.nlm.nih.gov/12639695/ ; https://pubmed.ncbi.nlm.nih.gov/20804238/ ; https://doi.org/10.1016/j.cobeha.2024.101352

**Short source quotation:** Monsell's review reports that responses are “substantially slower and, usually, more error-prone immediately after a task switch.”

**Overlap:** The framework's single-thread rule, parking lot, bounded reconnaissance, and stopping rules address the cost of opening too many workstreams and switching between them.

**Implication:** Keep the single-thread rule as a practical hypothesis. Test whether it reduces delay, errors, and abandoned work for the actual user/task. Include context and switching motivation; task switching is not always bad, and the research literature notes methodological complexity.

**Boundary:** Laboratory task-switch costs do not directly quantify every real-world interruption or project transition. Do not turn them into a universal claim that all multitasking is harmful.

### 3.9 SRE, incident learning, and closure

**Sources:** Google SRE, “Postmortem Culture: Learning from Failure” and “Postmortem Practices for Incident Management.”  
Links: https://sre.google/sre-book/postmortem-culture/ and https://sre.google/workbook/postmortem-culture/

**Short source quotation:** “learn from outages and improve our systems.”

**Overlap:** Evidence separation, incident records, contributing-factor analysis, corrective actions, review, and reopening conditions overlap with established SRE practice.

**Implication:** The navigation review should borrow mature postmortem design: observable timeline, impact, contributing conditions, what worked, what did not, actions with owners, priority and verifiable end states, and follow-up. “Closure” should mean a justified state transition with a reopening condition, not premature dismissal.

**Boundary:** Blamelessness is not lack of accountability. Google SRE's examples emphasize verifiable evidence, concrete action items, ownership, and measurable outcomes. The Cage Fluency template should be tested against an existing postmortem template before claiming advantage.

## 4. Synthesis: what remains potentially distinctive?

The literature scan suggests that most component ideas have substantial predecessors. The possible contribution is therefore a **cross-domain synthesis and lightweight operating protocol**, not a new law of human behaviour.

Potentially useful integration:
1. A common unit of work: an agent pursuing an objective within explicit constraints and resource limits.
2. Drift triage that distinguishes observation, interpretation, hypothesis, confidence, and consequence.
3. Reconnaissance with a decision question, budget, stop rule, and expiry.
4. Choice of bounded, reversible action while uncertainty is high.
5. Explicit preservation of essential functions and viable future options.
6. Archive hygiene and closure/reopening rules that prevent an unbounded backlog from consuming attention.
7. A short review that records outcome, learning, and whether the method helped.

Each element has precedents. Their integration must be compared against existing decision logs, after-action reviews, incident postmortems, safety analysis, and decision theory templates. A new name is not evidence of a new contribution.

## 5. Revisions recommended for the framework

The following changes are recommended and reflected in the linked working framework:

- Reclassify Cage Fluency explicitly as an integrative practice proposal.
- Treat Drift as a descriptive, operationally defined mismatch; do not imply it is a novel scientific construct.
- Add a concept crosswalk and direct citations for cybernetics, viability theory, affordances, resilience engineering, situation awareness, active inference, OODA, task switching, and SRE.
- Separate what a source actually states from the framework's interpretation and proposed application.
- Narrow novelty claims to a testable claim about integration, usability, or outcomes.
- Require comparisons with existing methods before claiming that the template is better.
- Map the Mozenrath-Pub prototype's actual mechanics to principles and user outcomes before presenting it as a demonstration.
- Preserve negative and null results; revise or retire parts that add complexity without measurable benefit.

## 6. Practical validation protocol

Choose one low-risk, bounded task. Before using the template, define:
- the goal and non-negotiable boundaries;
- baseline method and expected outcome;
- time/attention/resource budget;
- known facts, uncertainties, and evidence sources;
- a measurable success signal and failure condition;
- a stop time and reopening rule.

Run the task once with the ordinary method and, where feasible, once with the Cage Fluency review (or compare a current task with a closely matched baseline). Record time spent, completion, missed signals, number of workstream changes, quality of decision, options preserved, and any harmful side effects. Avoid claiming causation from one uncontrolled example.

**Falsification:** if the template repeatedly adds overhead without improving decisions, learning, sustainability, or option preservation relative to a simpler existing method, simplify it or stop using it for that class of problem.

## 7. Source register

1. Ashby, W. Ross. *An Introduction to Cybernetics* (1956), requisite variety. https://ashby.info/Ashby-Introduction-to-Cybernetics.pdf
2. Viability Theory. “Viability Kernel.” https://viability-theory.org/en/node/43
3. Gibson, James J. *The Ecological Approach to Visual Perception* (1979), “The Theory of Affordances.” https://patterns.architexturez.net/doc/az-cf-193204
4. Chemero, Anthony. “Affordances.” Open Encyclopedia of Cognitive Science (2024). https://oecs.mit.edu/pub/984ungzu
5. Hollnagel, Erik. “What is Resilience Engineering?” Resilience Engineering Association. https://www.resilience-engineering-association.org/what-is-resilience-engineering/
6. NASA. *Human Performance and Error*, 5.1.6 Situation Awareness. https://www.nasa.gov/reference/5-0-human-performance-and-error-vol-2/
7. “Active inference on discrete state-spaces: A synthesis.” *Neuroscience & Biobehavioral Reviews* (2020), open access. https://pmc.ncbi.nlm.nih.gov/articles/PMC7732703/
8. “Automating the OODA loop in the age of intelligent machines…” (2022). https://www.tandfonline.com/doi/full/10.1080/14702436.2022.2102486
9. “Imaginaries of omniscience: Automating intelligence in the US Department of Defense” (2023). https://pmc.ncbi.nlm.nih.gov/articles/PMC10543130/
10. Monsell, Stephen. “Task switching.” *Trends in Cognitive Sciences* 7(3), 134–140 (2003). https://pubmed.ncbi.nlm.nih.gov/12639695/
11. Kiesel, Andrea et al. “Control and interference in task switching—a review.” *Psychological Bulletin* 136(5), 849–874 (2010). https://pubmed.ncbi.nlm.nih.gov/20804238/
12. “What are we measuring when we measure task switch costs?” *Current Opinion in Behavioral Sciences* 56 (2024), 101352. https://doi.org/10.1016/j.cobeha.2024.101352
13. Google SRE. “Postmortem Culture: Learning from Failure.” https://sre.google/sre-book/postmortem-culture/
14. Google SRE Workbook. “Postmortem Practices for Incident Management.” https://sre.google/workbook/postmortem-culture/

## 8. Change log

- **v0.2 (2026-10-25):** Added an initial related-work crosswalk, short source quotations, provenance ledger for known exact Cage Fluency mentions, limitations on the artefact search, a narrower statement of possible contribution, and a practical comparison/falsification protocol.
