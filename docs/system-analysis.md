# System Analysis

## 1. Problem framing

The challenge is not simply that graduates lack jobs. It is that employers often have incomplete, expensive-to-verify evidence of candidates' capability, while formal work history is an accessible but imperfect screening proxy.

The target users are graduates with limited formal employment history and employers seeking junior talent. Reviewers are the operational link between them.

## 2. Stakeholders and incentives

- Graduates: want a fair chance to demonstrate capability; may be tempted to exaggerate or copy work if rewards depend heavily on scores.
- Employers: want credible signals of ability while minimising screening time and hiring risk.
- Reviewers: need consistent criteria, manageable workloads and clear evidence standards.
- Universities and training providers: want graduates' skills recognised, but may have unequal resources and project support.
- Hackathon organisers: need a feasible, explainable intervention and evidence of independent reasoning.

## 3. Root causes

1. Many entry-level vacancies request prior experience, reducing access for first-time job seekers.
2. Repository links vary in quality and are costly to inspect consistently at scale.
3. CVs and university reputation are easy to screen but do not directly demonstrate practical competence.
4. Personal networks and access to equipment, data and mentoring are unevenly distributed.
5. Employers have limited time to create individual trial tasks for every applicant.

These are problem hypotheses informed by the challenge brief, not claims that every employer behaves this way. They require validation with graduates and hiring teams.

## 4. System relationships and feedback loops

A reinforcing loop can occur:

Limited formal experience -> fewer interviews -> fewer opportunities to gain experience -> continued limited formal experience.

A second loop concerns employer risk:

Uncertain project quality -> reliance on familiar screening proxies -> overlooked candidates -> less diverse evidence about alternative talent pipelines -> continued reliance on the same proxies.

ProofOfWork aims to interrupt these loops by making evidence easier to compare. It cannot itself create jobs or guarantee that employers will change their hiring practices.

## 5. Intervention comparison

### Option A: Structured project-based assessment — selected

Assess a candidate's existing project against a fixed rubric and add a short, standardised practical task.

Benefits:
- Reuses work already completed.
- Makes evaluation criteria visible.
- Can be piloted with synthetic data.
- May reduce the time required for initial screening.

Costs and limitations:
- Reviewers still need time.
- Existing projects may have been copied or heavily assisted.
- Project polish can reflect unequal resources.
- Rubric scores may create false confidence if reviewers disagree.

### Option B: Employer-sponsored micro-internships

Candidates complete short, employer-defined work tasks.

Benefits:
- More directly connected to workplace requirements.
- Can reveal collaboration and task execution.

Costs and limitations:
- Requires employer supervision and task design.
- Can create unequal access to opportunities.
- Poorly designed trials may amount to unpaid labour.
- Harder to scale and demonstrate in the initial prototype.

Option A is selected for feasibility, not because it is proven more accurate.

## 6. Proposed system boundary

Included:
- Project submission.
- Rubric-based human review.
- Evidence-linked scores.
- Pseudonymous employer profiles.
- Shortlisting workflow.

Excluded from the initial prototype:
- Automated hiring decisions.
- Production identity verification.
- Direct employer integrations.
- Claims of verified authorship without a verification procedure.
- Job placement guarantees.

## 7. Assumptions to test

- Employers will consider evidence beyond formal experience.
- A shared rubric will improve consistency.
- Graduates will submit projects and complete a practical task.
- Employers can understand evidence summaries quickly.
- Pseudonymous review will reduce the influence of some irrelevant identity cues.

## 8. Risks and safeguards

- Copied work: use a practical task and reviewer questions; disclose remaining uncertainty.
- Reviewer inconsistency: use anchored criteria and compare independent ratings.
- Bias: hide unnecessary identity information during initial review and audit outcomes.
- Privacy: collect minimal data, restrict identity access and define retention periods.
- Accessibility: offer clear instructions, reasonable time limits and accessible task formats.
- Gaming: avoid publishing hidden answer keys; refresh practical tasks and review unusual patterns.
- False precision: display category scores and evidence, not just a single ranking.
- Security: validate submissions, protect accounts and enforce server-side role permissions.

## 9. Expected impact and measurement

Potential outcomes include more evidence-based shortlists and identification of candidates who would otherwise be overlooked. These outcomes are not yet demonstrated.

Measure:
- Time spent per review.
- Agreement between independent reviewers.
- Completion and abandonment rates.
- Number of candidates shortlisted after reviewing evidence.
- Candidate and employer feedback.
- Differences in outcomes across relevant groups, where lawful, ethical and adequately sampled.

## 10. Conclusion

ProofOfWork is a proposed intervention in the graduate-to-employer information gap. Its value depends on credible evidence, consistent review, privacy safeguards and employer adoption. A prototype can test usability and scoring consistency; a larger pilot is needed to assess hiring outcomes.
