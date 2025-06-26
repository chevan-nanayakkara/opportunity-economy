# GitHub Issue Templates

You'll need to create a `.github/ISSUE_TEMPLATE/` folder in your repository with these template files:

## 1. Policy Proposal Template
**File: `.github/ISSUE_TEMPLATE/policy-proposal.md`**

```yaml
---
name: Policy Proposal
about: Suggest a new policy area or specific policy mechanism
title: '[POLICY] '
labels: ['policy-proposal', 'needs-review']
assignees: ''
---

## Policy Area
<!-- Which section does this belong in? (Economic Policy, Social Infrastructure, etc.) -->

## Problem Statement
<!-- What market failure or policy gap does this address? -->

## Proposed Solution
<!-- Describe your policy mechanism in detail -->

## Evidence Base
<!-- What research, data, or real-world examples support this approach? -->

## Implementation Pathway
<!-- How could this policy realistically be enacted? -->
- [ ] Legislative action required
- [ ] Administrative/regulatory action possible
- [ ] State/local implementation viable
- [ ] Requires constitutional amendment

## Coalition Potential
<!-- Who would support this policy? What interests align? -->

## Technical Expertise Needed
<!-- What kinds of subject matter experts should review this? -->

## Related Policies
<!-- Link to existing policies or issues this connects with -->

## Additional Context
<!-- Any other relevant information -->
```

## 2. Policy Feedback Template
**File: `.github/ISSUE_TEMPLATE/policy-feedback.md`**

```yaml
---
name: Policy Feedback
about: Suggest improvements to existing policy proposals
title: '[FEEDBACK] '
labels: ['policy-feedback', 'improvement']
assignees: ''
---

## Policy Document
<!-- Link to the specific policy file or section -->

## Section/Area of Focus
<!-- Which part of the policy are you commenting on? -->

## Type of Feedback
- [ ] Technical correction
- [ ] Implementation concern
- [ ] Evidence update
- [ ] Coalition-building suggestion
- [ ] Legal/regulatory issue
- [ ] Economic impact analysis
- [ ] Other: ___________

## Detailed Feedback
<!-- Explain your suggested changes -->

## Supporting Evidence
<!-- Research, examples, or data that supports your suggestion -->

## Alternative Approaches
<!-- If suggesting changes, what alternatives should be considered? -->

## Impact Assessment
<!-- How significant is this change? -->
- [ ] Minor clarification
- [ ] Moderate improvement
- [ ] Major revision needed
- [ ] Fundamental rethinking required

## Expert Review Needed
<!-- What kind of expertise should evaluate this feedback? -->

## Additional Context
<!-- Any other relevant information -->
```

## 3. Research Contribution Template
**File: `.github/ISSUE_TEMPLATE/research-contribution.md`**

```yaml
---
name: Research Contribution
about: Share research, data, or case studies relevant to policy development
title: '[RESEARCH] '
labels: ['research', 'evidence-base']
assignees: ''
---

## Research Type
- [ ] Academic study
- [ ] Government report
- [ ] International comparison
- [ ] Case study
- [ ] Data analysis
- [ ] Industry report
- [ ] Other: ___________

## Policy Relevance
<!-- Which policy areas does this research inform? -->

## Key Findings
<!-- Summarize the most important insights -->

## Policy Implications
<!-- How should this research influence our policy recommendations? -->

## Research Source
<!-- Full citation and link if available -->

## Quality Assessment
<!-- Why is this research credible and relevant? -->

## Suggested Integration
<!-- Where and how should this research be incorporated? -->

## Additional Research Needed
<!-- What gaps does this highlight? -->

## Expert Perspective
<!-- If you have domain expertise, share your analysis -->
```

## 4. Implementation Strategy Template
**File: `.github/ISSUE_TEMPLATE/implementation-strategy.md`**

```yaml
---
name: Implementation Strategy
about: Suggest approaches for enacting or improving policy implementation
title: '[IMPLEMENTATION] '
labels: ['implementation', 'strategy']
assignees: ''
---

## Policy Focus
<!-- Which specific policy or policy area? -->

## Implementation Pathway
- [ ] Federal legislation
- [ ] Federal regulatory action
- [ ] State legislation
- [ ] State regulatory action
- [ ] Local ordinance
- [ ] Ballot initiative
- [ ] Executive action
- [ ] Judicial strategy

## Current Political Context
<!-- What makes this approach viable now? -->

## Required Resources
<!-- What would implementation require? -->
- [ ] Legislative champions
- [ ] Agency capacity
- [ ] Funding mechanisms
- [ ] Technical expertise
- [ ] Coalition support

## Timeline
<!-- Realistic timeline for this approach -->
- [ ] Immediate (0-6 months)
- [ ] Short-term (6-18 months)
- [ ] Medium-term (1-3 years)
- [ ] Long-term (3+ years)

## Key Stakeholders
<!-- Who needs to be involved? -->

## Potential Obstacles
<!-- What challenges should be anticipated? -->

## Success Metrics
<!-- How would we measure successful implementation? -->

## Precedents
<!-- Examples of similar policies being successfully implemented -->

## Next Steps
<!-- What specific actions should be taken? -->
```

## 5. General Question Template
**File: `.github/ISSUE_TEMPLATE/question.md`**

```yaml
---
name: General Question
about: Ask questions about policies, the framework, or how to contribute
title: '[QUESTION] '
labels: ['question', 'help-wanted']
assignees: ''
---

## Question Type
- [ ] Understanding existing policy
- [ ] How to contribute
- [ ] Framework application
- [ ] Technical clarification
- [ ] Process question
- [ ] Other: ___________

## Question
<!-- Ask your question clearly and specifically -->

## Context
<!-- What prompted this question? What are you trying to accomplish? -->

## What I've Already Tried
<!-- What research or exploration have you already done? -->

## Relevant Experience
<!-- Any background that might help us provide a better answer -->

## Urgency
- [ ] Just curious
- [ ] Planning to contribute
- [ ] Urgent for current work
- [ ] Time-sensitive decision
```

## 6. Bug Report Template
**File: `.github/ISSUE_TEMPLATE/bug-report.md`**

```yaml
---
name: Bug Report
about: Report technical issues with the repository, links, or formatting
title: '[BUG] '
labels: ['bug', 'needs-fix']
assignees: ''
---

## Problem Description
<!-- What's not working correctly? -->

## Location
<!-- Which file, page, or section has the issue? -->

## Expected Behavior
<!-- What should happen instead? -->

## Steps to Reproduce
1. 
2. 
3. 

## Screenshots or Links
<!-- If applicable, add screenshots or specific URLs -->

## Browser/Device Info
<!-- If relevant for web-related issues -->

## Additional Context
<!-- Any other information that might help -->
```

## Setup Instructions

1. Create the folder structure:
```
.github/
└── ISSUE_TEMPLATE/
    ├── policy-proposal.md
    ├── policy-feedback.md
    ├── research-contribution.md
    ├── implementation-strategy.md
    ├── question.md
    └── bug-report.md
```

2. Copy each template into its respective file

3. Commit and push to your repository

4. GitHub will automatically use these templates when people create new issues

## Template Benefits

- **Guides quality contributions** by asking for specific information
- **Reduces back-and-forth** by collecting necessary details upfront  
- **Categorizes issues** automatically with labels
- **Maintains standards** consistent with your technical mastery approach
- **Encourages evidence-based** submissions
- **Streamlines review process** for maintainers