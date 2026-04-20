AI Lead Qualifier
An intelligent lead qualification system that uses AI to instantly analyze incoming business leads and determine whether they are worth pursuing — automatically.
Built with n8n and Groq.
What It Does
A prospect fills out a form with their name, work email, company name, and a description of the process they want to automate. The system sends that data to an AI model which scores the quality of their reasoning on a scale of 1 to 10. Only leads that meet the score threshold receive a follow up — unqualified leads are filtered out automatically.
No manual review. No wasted outreach.
How It Works

Prospect submits the form on the landing page
Form data is sent to an n8n webhook
n8n passes the submission to Groq for AI scoring
Groq evaluates the lead's response and assigns a score
If the score meets the threshold, an automated follow up email is triggered
Low quality leads are filtered out silently

Tech Stack

Frontend — HTML/CSS hosted on GitHub Pages
Automation — n8n (webhook, logic, email routing)
AI Scoring — Groq (fast LLM inference)
Hosting — GitHub Pages + ngrok for local testing

Live Demo
https://bjohnsonsatact.github.io/lead-qualifier
Use Case
Built for automation agencies and freelancers who receive inbound leads and need to filter serious prospects from low intent inquiries before spending time on outreach.
Author
Brian Johnson — CS Junior at Alabama A&M University, concentrating in AI.
Building automation systems at the intersection of AI and business operations.
LinkedIn
