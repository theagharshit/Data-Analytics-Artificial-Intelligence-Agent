# AI-Analytics-Explainer

What this does
Analyzes website traffic data and converts raw analytics metrics into clear, business friendly explanations and recommendations.

Why this exists
Analytics tools show what happened but rarely explain why. This project bridges that gap by translating GA4 data into insights that non technical stakeholders can actually act on.

How it works 
	1.	A webhook triggers an analytics query
	2.	GA4 data is fetched for the current and previous week
	3.	Custom JavaScript logic calculates week over week changes
	4.	An LLM interprets the data to explain trends, likely causes, and next actions
	5.	A structured response is returned via the webhook

Tech stack
	•	Google Analytics 4 (GA4)
	•	LLMs for insight generation
	•	n8n for workflow orchestration
	•	Custom JavaScript for metric aggregation
	•	Webhooks for event driven execution
