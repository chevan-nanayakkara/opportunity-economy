# GitHub Labels for Implementation Management

Copy and paste these into your GitHub repository's Labels section:

## Implementation Labels

### Jurisdiction Levels
```
implementation/federal - #2563eb - Federal level implementation
implementation/state - #1d4ed8 - State level implementation  
implementation/local - #3730a3 - Local level implementation
implementation/multi - #1e1b4b - Multi-jurisdictional coordination
```

### Implementation Status
```
status/planning - #f59e0b - In planning phase
status/introduced - #10b981 - Legislation introduced
status/committee - #059669 - In committee review
status/floor - #047857 - Floor consideration
status/passed - #065f46 - Passed/enacted
status/rulemaking - #7c3aed - Regulatory rulemaking
status/implemented - #22c55e - Fully implemented
status/stalled - #ef4444 - Progress stalled
```

### Priority Levels
```
priority/urgent - #dc2626 - Urgent action needed
priority/high - #ea580c - High priority
priority/medium - #d97706 - Medium priority
priority/low - #65a30d - Low priority
priority/long-term - #16a34a - Long-term planning
```

### Stakeholder Types
```
stakeholder/legislative - #8b5cf6 - Legislative stakeholders
stakeholder/executive - #a855f7 - Executive branch/agencies
stakeholder/coalition - #c084fc - Coalition partners
stakeholder/business - #06b6d4 - Business interests
stakeholder/advocacy - #0891b2 - Advocacy organizations
stakeholder/academic - #0e7490 - Academic/research
stakeholder/media - #155e75 - Media contacts
```

### Activity Types
```
activity/milestone - #f97316 - Implementation milestone
activity/coordination - #fb923c - Cross-jurisdictional coordination
activity/engagement - #fdba74 - Stakeholder engagement
activity/research - #fcd34d - Research/analysis needed
activity/communications - #fde68a - Communications/messaging
activity/fundraising - #fef3c7 - Coalition/campaign fundraising
```

### Content Types  
```
content/policy-proposal - #84cc16 - New policy proposal
content/policy-feedback - #a3e635 - Feedback on existing policy
content/research - #bef264 - Research contribution
content/implementation - #d9f99d - Implementation strategy
content/question - #ecfccb - General question
content/bug - #fee2e2 - Technical issue
```

### Functional Labels
```
needs/review - #fbbf24 - Needs expert review
needs/response - #f59e0b - Awaiting response
needs/decision - #dc2626 - Decision required
needs/resources - #7c2d12 - Resources needed
blocked - #ef4444 - Progress blocked
duplicate - #6b7280 - Duplicate issue
wontfix - #374151 - Will not be addressed
help-wanted - #22c55e - Community help needed
good-first-issue - #22d3ee - Good for new contributors
```

## GitHub Projects Setup

### Project Boards to Create

#### 1. Federal Implementation Pipeline
**Columns:**
- Backlog
- Planning
- Introduced
- Committee
- Floor/Final
- Enacted
- Rulemaking
- Implemented

#### 2. State Coordination Hub  
**Columns:**
- Opportunity Analysis
- Pilot Development
- Legislative Session
- Passage/Implementation
- Lessons Learned

#### 3. Coalition Management
**Columns:**
- Prospect Research
- Initial Outreach
- Engaged
- Committed
- Active Partner
- Opposition Monitoring

#### 4. Local Implementation Tracker
**Columns:**
- Opportunity Mapping
- Local Adaptation
- Introduction
- Passage
- Implementation
- Impact Assessment

## Milestone Templates

### Federal Milestones
- Congressional introduction
- Committee hearings
- Committee markup
- Floor vote
- Presidential signature
- Regulatory implementation
- Program launch

### State Milestones  
- Legislative session planning
- Bill introduction
- Committee advancement
- Floor passage
- Governor signature
- Agency implementation
- Program evaluation

### Coalition Milestones
- Stakeholder mapping
- Key endorsements
- Opposition research
- Media strategy
- Grassroots mobilization
- Legislative advocacy
- Implementation support

## Automation Rules (GitHub Actions)

### Auto-Label Rules
```yaml
# When issue title contains [FEDERAL]
if: contains(github.event.issue.title, '[FEDERAL]')
then: add-label('implementation/federal')

# When milestone is set to "Q1 Implementation"  
if: milestone == "Q1 Implementation"
then: add-label('priority/urgent')

# When stakeholder template is used
if: template == 'stakeholder-engagement'
then: add-label('stakeholder/engagement')
```

### Project Auto-Assignment
```yaml
# Federal implementation issues go to Federal Pipeline
if: has-label('implementation/federal')
then: add-to-project('Federal Implementation Pipeline')

# State coordination goes to State Hub
if: has-label('implementation/state')  
then: add-to-project('State Coordination Hub')
```

## Usage Examples

### Creating Implementation Issues
```
Title: [MILESTONE] California AB-123 Committee Hearing
Labels: implementation/state, status/committee, priority/high, stakeholder/legislative
Assigned to: @state-coordinator
Project: State Coordination Hub
```

### Cross-Jurisdictional Coordination
```
Title: [COORDINATION] Federal CBO score needed for state budget analysis
Labels: coordination, implementation/federal, implementation/state, needs/decision
```

### Stakeholder Engagement Tracking
```
Title: [STAKEHOLDER] Business coalition briefing on tax provisions
Labels: stakeholder/business, activity/engagement, priority/medium
```

This labeling system transforms your repository into a comprehensive project management system specifically designed for multi-level government implementation work!