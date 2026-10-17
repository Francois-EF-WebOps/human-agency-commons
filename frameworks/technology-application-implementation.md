# Technology, application and implementation framework

**Status:** Initial working framework; not a claim that a specific technology is suitable or locally validated.

## Purpose

This framework extends Human Agency Commons from identifying needs and assessing evidence to designing, implementing, operating, and evaluating practical responses. It treats technology as one possible means among several, not as the default answer.

A response may combine a policy or service change, community coordination, training, physical infrastructure, an offline procedure, a digital tool, or a technical system. Choose the least complex approach that can safely meet the verified need and be maintained by the people responsible for it.

## Core rule

**Need → evidence → options → co-design → prototype → implementation → operation → evaluation → adaptation or retirement.**

Do not begin with “build an app” and work backwards to justify it. First establish the problem, who experiences it, what already exists, what constraints matter, and what a useful outcome would look like.

## Scope: what technology means here

Consider technology broadly, including:

- **Access and infrastructure:** electricity, connectivity, devices, data costs, repair, accessible public access, and service availability across locations.
- **Applications and digital services:** mobile/web apps, websites, directories, booking and referral systems, forms, maps, messaging, educational tools, and service portals.
- **Data and knowledge systems:** source registers, open data, local-language information, records, interoperability, data quality, and responsible data sharing.
- **Automation and AI:** workflow automation, decision support, translation, summarisation, assistive systems, and agentic tools, with clear limits and human accountability.
- **Appropriate physical technology:** water and energy systems, food production, repairable equipment, sensors, assistive devices, and locally maintainable infrastructure.
- **Human and organisational systems:** operating procedures, training, governance, support, procurement, maintenance, and the skills needed to use or change a system.

## Technology is cross-cutting and a research topic

Technology intersects with all pilot areas: employment, cost of living, transport, water, healthcare, housing, education, unpaid care, food, energy/waste, and media/influence. It should also be investigated as a topic in its own right where evidence supports questions about digital access, affordability, service exclusion, platform power, privacy, algorithmic decisions, digital skills, and technology dependence.

Do not assume that low digital adoption means a lack of interest or ability. Check device access, connectivity, language, disability access, confidence, trust, cost, relevance, and whether the service itself works.

## Decision gates

### Gate 1 — Verify the need

Record the affected group and place, evidence quality, current workaround, urgency, consequences of doing nothing, and uncertainty. Distinguish a locally reported need from a statistically established pattern. Seek voluntary input from affected people without implying endorsement.

### Gate 2 — Compare options before choosing technology

Compare at least:
1. improve the existing service or process;
2. a non-digital or low-tech option;
3. adapt an existing tool or open standard;
4. build or commission something new;
5. do nothing yet, if evidence or safeguards are inadequate.

For each option, estimate total cost of ownership, time to benefit, accessibility, training, staffing, maintenance, failure modes, dependencies, and reversibility. A new app is not automatically better than a phone number, paper workflow, shared directory, or improved existing service.

### Gate 3 — Specify the real operating environment

Record:
- devices and operating systems actually available;
- intermittent electricity or connectivity and offline needs;
- data and device affordability;
- local languages, literacy, disability access, and low-bandwidth requirements;
- location, climate, transport, repair and replacement options;
- staff and volunteer capacity, skills, turnover and support;
- data protection, legal obligations, safety and procurement constraints.

Treat these as questions to verify, not assumptions about Cabo Verde or any other community.

### Gate 4 — Design for agency and safety

Every system should make clear:
- who operates it and who is accountable;
- what information is collected and why;
- who can access, correct, export, and delete data where applicable;
- what decisions are automated and how a person can challenge them;
- how users can refuse, leave, switch provider, or use a non-digital alternative;
- how security incidents, complaints, outages and errors are handled.

Collect the minimum necessary data. Do not put sensitive personal information, identifiable testimony, credentials, access tokens, or unconsented records in public repositories. Avoid biometric or location tracking unless demonstrably necessary, proportionate, lawful, and independently reviewed.

### Gate 5 — Prototype safely

Start with the smallest test that can answer a meaningful question. Use synthetic or non-sensitive data where possible. Test with intended users only through voluntary, informed participation. Define success measures, harm indicators, support arrangements, rollback steps, and stop criteria before launch.

A prototype is not a production service. Label its status, limitations, data handling, and support expectations.

### Gate 6 — Prepare implementation and operations

An implementation plan must identify:
- accountable owner and decision rights;
- users, operators, affected non-users, and support contacts;
- workflow changes and service boundaries;
- build/configuration, testing, migration and rollout steps;
- training and accessible documentation;
- hosting, devices, connectivity, licences and recurring costs;
- backups, recovery, updates, security, maintenance and incident response;
- procurement, vendor and platform dependencies;
- accessibility, language and non-digital fallback;
- acceptance criteria and who signs off;
- handover, funding continuity and eventual retirement.

If no person or organisation can responsibly operate and maintain a proposed solution, do not describe it as implementation-ready.

### Gate 7 — Evaluate actual outcomes

Measure more than downloads, registrations, logins or feature completion. Select indicators tied to the original need, such as:
- time, money or travel saved;
- successful access to a service or resource;
- error, delay, abandonment and failure rates;
- user understanding, control and satisfaction;
- outcomes across relevant locations and groups;
- staff workload and maintenance burden;
- incidents, complaints, exclusion, coercion and unintended harms;
- total cost per meaningful successful outcome.

Record baseline, method, timeframe, sample limitations, adverse results and alternative explanations. Do not claim causation from a simple before/after comparison without considering other factors.

### Gate 8 — Continue, change, scale or retire

Scale only when evidence, user consent, safety, operating capacity, and recurring costs justify it. Preserve portability and documented exit options. Provide a transition plan if the tool becomes unaffordable, insecure, obsolete, unsupported, or harmful.

## Minimum technical quality checklist

- [ ] The problem and intended users are defined.
- [ ] Alternatives were compared, including non-digital options.
- [ ] Requirements are testable and traceable to the need.
- [ ] Accessibility, language, low bandwidth and offline use were assessed.
- [ ] Data minimisation, permissions, retention and deletion are documented.
- [ ] Security, backup, recovery and incident handling are considered.
- [ ] Dependencies, licence terms, hosting and recurring costs are recorded.
- [ ] Tests cover ordinary use, errors, poor connectivity and recovery.
- [ ] User-facing instructions and operator runbooks exist.
- [ ] A named operator, support route, maintenance plan and fallback exist.
- [ ] Evaluation measures and stop criteria were set before the test.
- [ ] Results, limitations, incidents and changes are documented.

Not every item applies identically to every intervention; any exception should be explained, not silently ignored.

## Evidence and transparency

Use the project source register and claim ledger for factual claims about a place, population, service, or technology. Keep separate:
- **verified fact** — supported by traceable evidence;
- **reported experience** — attributed and contextualised;
- **design assumption** — to be tested;
- **hypothesis** — plausible but unconfirmed;
- **implementation status** — proposed, prototype, pilot, operational, evaluated, paused, or retired.

A technical demonstration establishes that something ran in a particular setting. It does not establish usefulness, equitable access, safety, affordability, community acceptance, or sustained impact.

## Cabo Verde pilot: responsible application

For the Cabo Verde case, investigate digital access and service delivery by island and community rather than assuming one national user environment. Potential research questions include connectivity and device/data costs; language and accessibility; digital public-service access; information quality; local maintenance capacity; and whether digital tools reduce or add travel, time, expense, or exclusion.

These are research questions, not findings. Add claims only after sourcing them; map existing services and initiatives before proposing a new tool. Seek local-language evidence and voluntary local review. Do not present a pilot as representative of all islands.

## Related working template

Use [the implementation plan template](../templates/implementation-plan.md) for any proposed tool, service, workflow or technical intervention. For early-stage work, a concise, phone-friendly Markdown record is sufficient; a complex database or elaborate architecture is not a prerequisite.
