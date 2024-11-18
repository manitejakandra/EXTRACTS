Project Overview:

This project involves creating an AI-powered agent that can take a dataset (in CSV or Google Sheets format) and, for a specified column, perform web searches to retrieve relevant information for each entry in that column. Leveraging an LLM (Large Language Model), the agent will parse web search results to find targeted information based on a user-defined query, format it in a structured format, and present the findings in a simple, user-friendly dashboard.
Key Capabilities:

Data Processing: Allows users to upload a dataset (CSV or Google Sheets) and select a specific column for data extraction.
Custom Web Searches: Users define search queries for each entry in the dataset column, and the agent retrieves relevant information using an LLM.
Result Summarization: The LLM parses web results, structuring them in a user-friendly format that links back to the original dataset.
Dashboard Interface: The user-friendly dashboard provides file upload functionality, search query customization, and downloadable results.

Usage Guide

Uploading a Dataset
Go to the dashboard and select "Upload File" to upload a CSV file or connect to Google Sheets.
For Google Sheets, enter the sheet URL or ID and connect using your Google Sheets API key.
Select Column for Search
After uploading, you’ll see a list of columns. Select the column you’d like to analyze and specify any additional search parameters.
Define Search Queries
Use the dashboard to define a search query template (e.g., "latest news on {entity}").
The AI will replace {entity} with each entry in the selected column and perform web searches accordingly.
View and Download Results
Once the search is complete, the dashboard will display the summarized results.
You can download the results as a CSV file or export it as a report.

Optional Features
Pagination and Error Handling: Added pagination in the dashboard for easier data navigation. Error handling displays messages if an entry fails to retrieve data.
Data Filtering and Sorting: Allows users to filter and sort results based on parameters like date or relevance.
Additional Output Formats: Users can choose between CSV, JSON, or Excel for output format.
Bulk Query Editing: Added functionality for users to edit or delete multiple queries at once.
Scheduling Searches: Users can schedule regular searches and have the data automatically updated on the dashboard.

