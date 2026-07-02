# Customer Health & Customer Success Automation

Production AI workflows for monitoring customer health, identifying churn risk, analyzing customer responses, and generating actionable insights for Customer Success teams.

## Workflows

### Customer Health Monitoring Agent
**File:** `customer-health-monitoring-agent.json`

**Purpose**
- Monitors customer activity and product usage.
- Calculates customer health metrics.
- Aggregates engagement signals.
- Updates customer health records.

**Technologies**
- n8n
- OpenAI
- JavaScript
- REST APIs
- HubSpot
- Amplitude

---

### AI Customer Response Classifier
**File:** `ai-customer-response-classifier.json`

**Purpose**
- Monitors customer email replies.
- Uses AI to classify responses by relevance, sentiment, and risk.
- Filters out auto-replies and spam.
- Escalates meaningful responses to the Customer Success team via Slack.

**Technologies**
- n8n
- OpenAI (GPT)
- Gmail API
- Slack API
- Structured AI Output

---

### Weekly Customer Health Reporting Agent
**File:** `weekly-customer-health-reporting-agent.json`

**Purpose**
- Generates weekly customer health reports.
- Identifies high-risk customer accounts.
- Produces AI-generated executive summaries.
- Sends Slack and email reports.

**Technologies**
- n8n
- OpenAI
- Slack API
- Gmail API
- Data Processing

---

## Skills Demonstrated

- AI Workflow Automation
- Customer Success Automation
- Customer Health Monitoring
- Churn Risk Detection
- AI-Powered Email Classification
- Prompt Engineering
- API Integrations
- Enterprise Workflow Orchestration
