# Enterprise Product Feedback Loop

A framework for steering feedback from customers → GTM → Product → Engineering → back to customers.

## Live Demo

**[View the Framework](https://joannapedrina.github.io/product-feedback-loop/)**

## What This Covers

### The Flow
Customer feedback → GTM team (Sales/CS) → Product triage → Engineering build → Close the loop back to customers

### Key Sections

1. **By Audience** - What Leadership, PMs, Engineers, and Sales/Marketing each need to see
2. **Segmentation** - Slicing enterprise customers by industry, use case, region, tier, lifecycle
3. **Feedback Types** - Taxonomy: general feedback, requests, bugs, pain points, behavioral signals
4. **Models & Products** - Tracking feedback by model (Large, Small, Codestral) and product (API, Le Chat, betas)
5. **Automations** - Where to implement automations using Slack, Salesforce, Notion, Linear, GitHub
6. **Implementation** - How to roll this out and get buy-in from stakeholders
7. **Discovery Tools** - Supporting PMs in understanding what to build next
8. **Targeted Collection** - Time-based and usage-based feedback maturity, plus organic collection methods
9. **Verify Before Build** - Treating feedback clusters as hypotheses; statistical significance per segment
10. **Data Collection (Airtable)** - Centralizing all feedback enriched with customer data

## Core Philosophy

### Don't Survey - Collect Organically

Customers are constantly sharing feedback—just not in survey form:
- Shared Slack channels
- Sales & CS call notes (Granola transcripts)
- Error moments in the product
- Support tickets
- Renewal conversations
- Behavioral signals (usage drops, feature abandonment)

### Feedback Matures Over Time

- **Day 7**: What's confusing?
- **Day 30**: What's frustrating?
- **Day 120**: What's limiting?
- **Day 365+**: What keeps them here?

### Usage-Based Maturity

- **1st use**: Is it obvious?
- **20th use**: What slows them down?
- **50th use**: What are the limits?

### Verify Before You Build

The plural of anecdote is not data—it's a hypothesis:
- 5 users ask for X → **Hypothesis**, not feature
- Talk to 20 more users in that segment
- Look for unprompted mentions
- Only build if pain is validated and sized

### Statistical Significance

Ensure enough data per segment before acting:
- 10-50 customers → 5-10 data points (directional)
- 50-200 customers → 15-30 data points (~80% confidence)
- 200-1000 customers → 50-100 data points (~90% confidence)

### Airtable as the Central Hub

Collect, organize, and enrich all feedback:
- **Feedback Items**: Verbatim, source, category, product/model
- **Customers**: Industry, region, tier, lifecycle, use case
- **Themes**: Clustered feedback with status and ARR impact
- Role-based views for Leadership, PM, Engineering, Sales

## Tech Stack (Current)

This framework is designed to work with:
- Slack
- Salesforce
- Notion
- Linear
- GitHub
- Google Suite

## Related Projects

- [Product Ops Hub](https://joannapedrina.github.io/mistral-product-ops-hub-demo/) - Feedback dashboard, launch checklists
- [Design Program Framework](https://joannapedrina.github.io/design-program-framework/) - Running design partner programs

---

Built to be lightweight and practical. Start simple, prove value, then add complexity only where needed.
