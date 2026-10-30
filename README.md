# n8n AI Automation Workflows

Four AI-powered automation workflows built with n8n, Google Gemini and Google Workspace, as part of my Generative AI and Prompt Engineering course.

## Workflows

| # | Workflow | Trigger | AI model | Output |
|---|----------|---------|----------|--------|
| 1 | Lead Generation Agent | Manual | Google Gemini | Scored leads and outreach messages in Google Sheets |
| 2 | CV Screening | Google Drive (new file) | Google Gemini | Candidate score and summary in Google Sheets |
| 3 | AI Personal Assistant | Chat message | Google Gemini | Replies and actions on Gmail, Calendar and Sheets |
| 4 | LinkedIn Auto Poster | Schedule | Google Gemini | Published LinkedIn post |

## Screenshots

### 1. Lead Generation Agent
![Lead Generation Agent](screenshots/01-lead-generation.png)

### 2. CV Screening
![CV Screening](screenshots/02-cv-screening.png)

### 3. AI Personal Assistant
![AI Personal Assistant](screenshots/03-ai-personal-assistant.png)

### 4. LinkedIn Auto Poster
![LinkedIn Auto Poster](screenshots/04-linkedin-auto-poster.png)

## How to use
1. Open n8n and create a new workflow.
2. Click the three dots menu and choose **Import from file**, then select a `.json` file from the `workflows` folder.
3. Add your own credentials (Google Gemini, Google Sheets, Gmail, Google Calendar, LinkedIn).
4. Update the Google Sheet or Drive folder in each node to your own.

## Tools used
n8n, Google Gemini, Google Sheets, Google Drive, Gmail, Google Calendar, LinkedIn

## Notes
- Sample data was used for the lead generation demonstration.
- Free-tier API limits applied during testing.
