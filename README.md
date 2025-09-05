**📝 Sentiment Analysis of ServiceNow Incidents**
This project leverages Google Gemini AI and ServiceNow REST APIs to perform sentiment analysis on incident descriptions. The system helps IT service teams and support engineers understand the emotional tone of incidents (negative, neutral, or positive) and prioritize tickets more effectively.

**🔍 Project Overview**
Designed an AI-powered sentiment analysis pipeline that evaluates incident short descriptions and returns a sentiment score (-1 to 1).

-1 → Negative sentiment

0 → Neutral sentiment

+1 → Positive sentiment

Integrated with ServiceNow APIs to fetch incident/request data securely.

Utilized Google Gemini AI (Generative AI) for NLP-driven analysis of unstructured text.

Output presented in structured JSON and tabular DataFrames for easy visualization.

**🚀 Key Features**
ServiceNow API Integration

Connects to ServiceNow instance using REST API with authentication.

Retrieves incident/request data automatically.

Sentiment Analysis with Gemini AI

Uses Google Gemini AI models (gemini-pro / gemini-1.5-flash) for NLP.

Analyzes the short description of each incident/request.

Returns standardized sentiment scores.

Data Processing & Transformation

Converts raw API results into structured Pandas DataFrames.

Supports JSON exports for downstream usage.

Secure Credential Management

Uses .env file to store API keys and ServiceNow credentials securely.

Prevents exposure of sensitive information.

Error Handling

Handles invalid responses, missing descriptions, and API failures gracefully.

Logs meaningful error messages for debugging.

Scalable & Extensible

Can be extended for requests, changes, or custom ServiceNow tables.

Modular design to integrate with dashboards or BI tools.
