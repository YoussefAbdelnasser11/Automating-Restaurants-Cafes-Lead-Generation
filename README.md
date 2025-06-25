# Automating-Restaurants-Cafes-Lead-Generation with n8n & AI
This project automates the process of finding, enriching, and generating personalized outreach messages for restaurants in Cairo using n8n, AI agents, and Google Maps data.

📦 Project Overview
Tired of manually collecting leads and crafting sales messages? This workflow solves that by:

✅ Automatically scraping restaurant details from Google Maps.
✅ Enriching the data with additional details like menus and pricing.
✅ Using AI to generate personalized sales pitches for each restaurant.
✅ Saving all results neatly to Google Sheets — ready for outreach or CRM integration.

🔄 How It Works
1. Data Input

The workflow reads search categories (e.g., Cairo - Restaurant) from a Google Sheet.

2. Google Maps Scraping

Uses HTTP Requests to pull addresses, names, ratings, and contact details for matching restaurants.

3. Data Cleaning & Processing

Removes duplicates.

Formats fields.

Loops through each restaurant individually.

4. Data Enrichment

Sends additional HTTP Requests to scrape business pages (e.g., Facebook).

Cleans the scraped data to extract key insights.

5. AI-Powered Personalization

An AI agent summarizes the restaurant's key selling points.

Another AI agent drafts a hyper-personalized outreach message for each business.

6. Output to Google Sheets

Final data and AI-generated messages are saved to a Google Sheet.

Sales teams can simply copy-paste the messages or integrate the sheet with a CRM.

⚡ Tech Stack
n8n (Workflow Automation)

Google Maps API

Google Sheets API

AI Agents (for summarization & message generation)

Web Scraping

JavaScript (for data manipulation)

💡 Why Use This
✔ Eliminate repetitive manual lead research.
✔ Generate personalized sales messages at scale.
✔ Combine low-code tools and AI to save time and boost efficiency.

🚀 Getting Started
Clone the repo.

Import the workflow to your n8n instance.

Set up your Google API and Facebook scraping configurations.

Add your AI agent credentials (if required).

Run the workflow and check your Google Sheet for results.

📢 Contributions
Feel free to open issues, suggest improvements, or submit pull requests to enhance the project!

🧑‍💻 Author
Yousef Abdelnasser

📜 License
This project is for educational purposes. Please ensure compliance with scraping policies and terms of service for third-party platforms.

