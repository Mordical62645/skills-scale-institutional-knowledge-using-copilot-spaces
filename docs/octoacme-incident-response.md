# OctoAcme — Incident Response & Post-Mortems

## Purpose
Provide guidance for rapid incident triage, response, and post-incident learning.

## Incident Classification

### Severity Levels

**Critical (Sev 1)**
- Production outage or data loss
- All customers affected or revenue impacted
- Immediate response required
- Escalate to Sponsor

**High (Sev 2)**
- Significant functionality unavailable
- Multiple customers affected
- Degraded experience or workaround available
- Response within 30 min

**Medium (Sev 3)**
- Limited functionality impact
- Single customer or feature affected
- Workaround available
- Response within 2 hours

**Low (Sev 4)**
- Minor issue or cosmetic bug
- No customer impact or minimal workaround
- Can be addressed in normal sprint

## Incident Response Workflow

### 1. Detection & Triage (First 5-15 min)
- Alert triggers monitoring system
- On-call engineer or Support Lead notified
- Severity assigned using classification above
- Incident channel opened (Slack, PagerDuty, etc.)

### 2. Response Team Assembly
- On-call engineer (Incident Commander)
- Support/Operations Lead
- Relevant Tech Lead or Engineer
- Security Lead (if security-related)
- Product Manager (kept informed)

### 3. Rapid Triage (First 15-30 min)
- Confirm incident scope and customer impact
- Check recent deployments, config changes, or anomalies
- Attempt quick remediation or rollback if safe
- Communicate status to stakeholders

### 4. Investigation & Remediation (30 min – ongoing)
- Root cause investigation
- Document timeline and actions taken
- Implement fix or workaround
- Prepare rollback plan if needed
- Communicate progress to stakeholders

### 5. Deployment & Verification (Ongoing)
- Deploy fix to staging, verify
- Deploy to production when ready
- Post-deployment verification and monitoring
- Confirm customer impact resolved

### 6. Communication
- Initial notification: "Incident declared at [time], investigating"
- 30-min updates: progress and ETA
- Resolution: "Issue resolved at [time], investigating root cause"
- Post-incident: summary and action items

## Incident Communication Template

## Blameless Post-Incident Retrospective

### Timing
- Schedule within 24-48 hours of resolution
- Include: Incident Commander, on-call engineer, Tech Lead, Support Lead, Product Manager

### Agenda (60 min)
1. Timeline review (15 min)
   - When did monitoring alert?
   - When was incident declared?
   - What actions were taken and when?

2. Root cause analysis (20 min)
   - What triggered the incident?
   - Why did detection/response take [X] time?
   - What made it difficult to resolve?

3. Action items (15 min)
   - What can we do to prevent recurrence?
   - What can we do to detect faster?
   - What can we do to resolve faster?
   - Assign owner and due date to each

4. Celebrate learnings (10 min)
   - What did we do well?
   - Thank participants for rapid response

### Action Item Template
- **Title:** [Brief description]
- **Root Cause:** [What incident revealed]
- **Owner:** [Name]
- **Due Date:** [Target]
- **Success Criteria:** [How we'll know it's done]
- **Priority:** [High/Medium/Low]

## Post-Incident Follow-up
- Add action items to project backlog with "incident" label
- Follow up on action items in weekly PM sync
- Track and celebrate completed improvements
- Share summary and learnings with team (anonymized if needed)

## Escalation Paths

**For Production Incidents:**
- Level 1: On-call engineer + Support Lead + Tech Lead
- Level 2: Incident Commander + Product Lead
- Level 3: Sponsor (for Sev 1 critical issues)

**For Security Incidents:**
- Follow Security Incident Runbook
- Notify Security Lead and on-call immediately
- Escalate to Security Officer and Legal if breach or compliance issue

## References
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)