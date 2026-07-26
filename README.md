# 🤖 AI Lead Qualification & Company Research System

An AI-powered lead qualification workflow that researches companies, evaluates business fit, classifies qualified leads, and automatically routes them to the appropriate sales team.

---

# 📌 Business Problem

Sales teams often spend valuable time manually reviewing incoming leads to determine whether they are a good fit. This process can be slow, inconsistent, and prevent sales representatives from focusing on high-value opportunities.

---

# 💡 Solution

This workflow automates the lead qualification process using AI and company research.

When a new lead submits a form, the workflow:

- Receives the lead information.
- Researches the company's website using a custom Relevance AI research tool.
- Analyzes the company's products, services, and target audience.
- Determines whether the company aligns with the business.
- Automatically qualifies or disqualifies the lead.
- Sends a personalized email if the lead is not a good fit.
- Routes qualified leads to another workflow.
- Classifies qualified leads as either **Agency** or **SaaS**.
- Notifies the appropriate internal team for follow-up.

---

# ⚙️ Workflow Architecture

Lead Form Submission

⬇️

Company Website URL

⬇️

Relevance AI Research Tool

⬇️

AI Company Analysis

⬇️

Lead Qualification Decision

⬇️

Qualified?

⬇️

Yes → Lead Classification (Agency / SaaS)

⬇️

Notify Internal Team

⬇️

Sales Follow-up

OR

No

⬇️

Personalized Email Response

---

# 🚀 Key Features

- AI-powered company research
- Automated company analysis
- Intelligent lead qualification
- Business fit evaluation
- Agency and SaaS lead classification
- Multi-workflow orchestration
- Personalized email responses
- Automated team notifications

---

# 🛠 Technologies Used

- n8n
- Relevance AI
- OpenAI
- HTTP Request
- REST APIs
- Gmail

---

# 🔄 Workflow Process

1. A lead submits a form.
2. The workflow receives the company website URL.
3. A custom Relevance AI research tool analyzes the company.
4. AI evaluates whether the company aligns with predefined business criteria.
5. Qualified leads are passed to a secondary workflow.
6. Qualified leads are classified as either Agency or SaaS.
7. The appropriate internal team is notified.
8. Non-qualified leads receive a personalized email response.

---

# 🧠 AI Decision Logic

The workflow evaluates:

- Company offerings
- Target audience
- Industry
- Business alignment
- Service compatibility

Based on this analysis, the AI determines whether the lead should move forward in the sales pipeline.

---

# 📈 Business Benefits

- Reduces manual lead qualification
- Improves sales efficiency
- Accelerates lead response times
- Ensures consistent qualification decisions
- Allows sales teams to focus on high-value prospects

---

# 📸 Workflow Screenshots

*Coming Soon*

---

# 🎥 Demo Video

*Coming Soon*

---

# 📚 Future Improvements

- CRM integration
- Lead scoring
- Calendar booking automation
- Slack or Microsoft Teams notifications
- AI-generated sales insights
