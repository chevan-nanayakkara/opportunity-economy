# Label Usage Guide
*How to use labels effectively in the Opportunity Economy repository*

## Overview

Our labeling system helps organize policy development, track progress, and enable community collaboration across the Four Pillars of Opportunity Economics. This guide explains how to use labels consistently for maximum effectiveness.

## Label Categories

### 🏛️ Four Pillars Labels (Primary Organization)

Use exactly **one** pillar label per issue to indicate which part of the framework it belongs to:

- **`building`** - Pillars 1 & 2: Federal capacity deployment and wealth-building for all Americans
- **`community-power`** - Pillar 3: Community control over economic development  
- **`market-accountability`** - Competition and corporate accountability policies
- **`democratic-inclusion`** - Pillar 4: Economic security and political inclusion

### 🏛️ Government Level Labels

Use **one or more** government level labels to indicate implementation scope:

- **`federal`** - Congressional legislation, agency rules, executive actions
- **`state`** - State legislation, regulations, pilot programs
- **`local`** - Municipal ordinances, county policies, community organizing  
- **`multi-level`** - Coordination across multiple government levels

### 📋 Development Stage Labels

Use **one** development stage label to track progress:

- **`policy-development`** - New policy creation and framework development
- **`research-needed`** - Requires more research, analysis, or evidence gathering
- **`coalition-building`** - Focus on stakeholder engagement and cross-partisan support
- **`implementation`** - Ready for legislative drafting or regulatory development

### ⚡ Priority Labels

Use **one** priority label to indicate urgency and resource allocation:

- **`priority-high`** - Top development priorities, immediate focus needed
- **`priority-medium`** - Important but not urgent, medium-term development
- **`priority-low`** - Good ideas for later, long-term consideration

### 🤝 Community Engagement Labels

Use when community input is needed:

- **`help wanted`** - Extra attention needed, seeking community expertise
- **`good first issue`** - Good for newcomers to the project
- **`question`** - Further information needed from community

### 🔧 Repository Management Labels

Use for repository maintenance:

- **`documentation`** - Improvements or additions to documentation
- **`enhancement`** - New features or improvements to existing policies

## Label Combinations Guide

### For New Policy Proposals
**Required**: One pillar + one government level + `policy-development`
**Optional**: Priority level, `help wanted`, `research-needed`

**Example**: `building` + `state` + `multi-level` + `policy-development` + `research-needed`

### For Research Requests
**Required**: One pillar + `research-needed` 
**Optional**: Government level, `help wanted`

**Example**: `market-accountability` + `research-needed` + `federal` + `help wanted`

### For Implementation Ready Policies
**Required**: One pillar + government level(s) + `implementation`
**Optional**: Priority level, `coalition-building`

**Example**: `community-power` + `local` + `implementation` + `priority-high`

## Practical Examples

### Financial Literacy Education Initiative
- **Pillar**: `building` (education falls under Pillars 1 & 2)
- **Government**: `state` + `multi-level` (state education with federal coordination)
- **Stage**: `policy-development` + `research-needed`
- **Priority**: `priority-medium` (let community reactions determine urgency)

### Consumer Depreciation Reform Implementation
- **Pillar**: `building` (federal capacity for wealth-building)
- **Government**: `federal` (IRS and tax policy)
- **Stage**: `implementation` (policy framework complete)
- **Priority**: `priority-high` (flagship policy)

### Local Cooperative Development
- **Pillar**: `community-power` (local economic control)
- **Government**: `local` + `state` (local implementation with state legal framework)
- **Stage**: `policy-development`
- **Community**: `help wanted` (seeking local organizer input)

### Antitrust Enforcement Reform
- **Pillar**: `market-accountability` (corporate accountability)
- **Government**: `federal` (antitrust is federal law)
- **Stage**: `research-needed` (analyzing current enforcement gaps)
- **Priority**: `priority-high` (market concentration is urgent)

## When to Update Labels

### Stage Progression
Update development stage labels as work progresses:
1. `research-needed` → `policy-development` → `coalition-building` → `implementation`

### Priority Changes
Update priority based on:
- **Community reactions** (👍 votes on issues)
- **Strategic importance** to overall framework
- **Political opportunities** for advancement
- **Resource availability** for development

### Government Level Refinement
Add or modify government level labels as implementation strategy develops:
- Start broad (`multi-level`)
- Refine to specific levels as strategy clarifies (`federal` + `state`)

## Filtering and Search Examples

### Find All Building Pillar Policies
Filter: `label:building`

### Find High Priority Items Needing Research
Filter: `label:priority-high label:research-needed`

### Find Federal Action Items Ready for Implementation
Filter: `label:federal label:implementation`

### Find Community Power Policies Needing Help
Filter: `label:community-power label:help-wanted`

### Find Multi-Level Coordination Opportunities
Filter: `label:multi-level`

## Label Management Guidelines

### Who Can Apply Labels
- **Repository maintainers**: Can apply any label
- **Community contributors**: Suggest labels in issue comments
- **Issue creators**: Can apply development stage and priority labels to their own issues

### Label Hygiene
- **One pillar per issue**: Never use multiple pillar labels on the same issue
- **Update as needed**: Change labels as issues evolve and progress
- **Be specific**: Use the most specific government level labels possible
- **Remove outdated labels**: Clean up labels that no longer apply

### Creating New Labels
Before creating new labels, consider:
- **Does it fit existing categories?** (pillar, government, stage, priority, community)
- **Will it be used frequently?** (avoid one-off labels)
- **Does it help organization?** (labels should aid filtering and workflow)

Suggest new labels in [Discussions](../../discussions) before creating them.

## Integration with Project Boards

Labels automatically sort issues into project boards:
- **Four Pillars Boards**: Filter by pillar labels
- **Government Level Boards**: Filter by federal/state/local labels  
- **Development Pipeline**: Filter by stage labels
- **Priority Boards**: Filter by priority labels

## Best Practices

### For Issue Creators
1. **Start with pillar + government + stage** (minimum viable labeling)
2. **Add priority if you have strong opinion** (otherwise let community decide)
3. **Use `help wanted` if seeking input** (encourages community engagement)
4. **Update labels as issue evolves** (especially stage progression)

### For Community Contributors
1. **Comment with label suggestions** if you can't apply them directly
2. **React with 👍 to vote for priority** (influences priority label decisions)
3. **Use filters to find relevant issues** for your expertise and interests
4. **Respect existing label structure** (suggest changes in Discussions)

### For Repository Maintainers
1. **Apply labels promptly** to new issues (within 24-48 hours)
2. **Monitor label consistency** across similar issues
3. **Update priority labels** based on community engagement
4. **Archive or close** issues that no longer fit the framework

---

*This labeling system enables effective collaboration across the Four Pillars of Opportunity Economics while maintaining clear organization and progress tracking.*

**Questions about labeling?** Ask in [Discussions](../../discussions) or comment on specific issues.