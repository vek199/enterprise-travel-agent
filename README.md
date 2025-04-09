# Enterprise Travel Agent - AWS Multi-Agent GenAI System
A multi-agent GenAI-based enterprise travel assistant built using AWS Lambda, Bedrock, Streamlit, and Knowledge Bases. Agents communicate and collaborate to fulfill complex enterprise travel needs for employees.

📌 Business Use Case
This project simulates an Enterprise Travel Assistant where:

HR Agent fetches travel policy and eligibility details.

Hotel Booking Agent suggests accommodation options.

Supervisor Agent coordinates, validates, and manages communication among agents.

UI is built with Streamlit for user interaction.

🧠 Architecture

Based on the multi-agent architecture using AWS Lambda and Amazon Bedrock.

🤖 Agents
1. HR Agent
Hosted on AWS Lambda

Integrates with Amazon Bedrock Knowledge Base to fetch HR policies.

Returns employee eligibility and travel entitlements.

2. Hotel Room Booking Agent
Simple rule-based system (can be extended with external API).

Returns hotel availability based on destination and travel dates.

3. Supervisor Agent
Orchestrates the above agents.

Handles conversation flow and integrates with the Streamlit UI.
