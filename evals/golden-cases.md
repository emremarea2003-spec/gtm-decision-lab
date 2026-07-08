# Golden Evaluation Cases

Use these cases after changing the skill. The goal is not identical wording; the goal is preserving decision behavior.

## Case 1: Sparse Founder Idea

Input:

> I have an AI productivity app for startup teams. Help me make a GTM plan.

Expected behavior:

- Do not generate a full GTM strategy immediately.
- Ask for or infer only minimal missing information.
- State that the buyer, pain, urgency, and evidence are unclear.
- Offer an intake path using `assets/intake-template.md`.
- Produce a validation-first plan if the user wants to proceed without more data.

Failure mode:

- Outputs a polished multi-channel campaign plan.

## Case 2: Pre-Revenue B2B SaaS With Weak Evidence

Input:

> We have a prototype, 20 waitlist signups, 3 interviews, no revenue, and three possible segments. Choose our first market.

Expected behavior:

- Use beachhead scoring.
- Mark willingness to pay and urgency assumptions.
- Recommend a validation direction, not a high-confidence strategy.
- Include rejected/deferred segments.
- Include a 14-day experiment and evidence ledger.

Failure mode:

- Treats waitlist signups as strong demand proof.

## Case 3: Developer Tool With Usage But No Payment

Input:

> Five open-source maintainers use our analytics prototype for free. We need a GTM motion.

Expected behavior:

- Recognize usage as stronger than pure interest but weaker than payment.
- Consider developer-led and content-led motion.
- Test the paid unit or stakeholder/reporting use case.
- Avoid claiming PLG scale until activation and payment are clearer.

Failure mode:

- Recommends broad PLG because the product is developer-facing.

## Case 4: Enterprise Segment Temptation

Input:

> Our tool could help enterprise RevOps teams. We have no enterprise customers, no security review, and no integrations. Should we target enterprise?

Expected behavior:

- Flag enterprise as likely premature.
- Identify missing proof: security, integrations, reference customers, buyer access, implementation support.
- Recommend a smaller reachable segment or validation interviews.

Failure mode:

- Builds an enterprise campaign calendar.

## Case 5: Evidence-Heavy GTM Audit

Input:

> We have 12 sales calls, 4 paid pilots, CRM notes, competitor review links, and two segments. Audit our GTM motion.

Expected behavior:

- Treat paid pilots and sales calls as strong evidence.
- Use competitor reviews as context, not primary proof.
- Produce a decision audit with confidence level.
- Identify motion risks and validation gates for scaling.

Failure mode:

- Ignores internal evidence and relies on public competitor data.
