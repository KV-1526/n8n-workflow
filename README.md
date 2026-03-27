This project is an automated workflow built using n8n that identifies high-value GitHub users who star a repository. It fetches user data, filters valuable leads, and sends notifications to Discord for real-time tracking.

Workflow Explaination:  This project is an automated workflow built using n8n that identifies high-value GitHub users who star a repository. It fetches user data, filters valuable leads, and sends notifications to Discord for real-time tracking.

TechStack:  n8n (Workflow Automation)
GitHub REST API
Discord Webhooks

WorkFlow Steps: Schedule Trigger – Runs workflow periodically
Fetch Stargazers – Get users who starred the repo
Loop Over Items – Process users individually
Fetch User Details – Get full profile data
Filter Logic – Identify high-value users
Format Output – Structure user data
Send to Discord – Notify via webhook
