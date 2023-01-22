# Power Automate Flows

This repo for tracking and documenting my [power automate flows](https://make.powerautomate.com/environments/Default-7b326d24-41ad-4f57-bc60-89e4a6ac721b/flows).

# Production flows

1. [Recurring Automatic Outlook Reply - Slower email response times than I would like](https://make.powerautomate.com/environments/Default-7b326d24-41ad-4f57-bc60-89e4a6ac721b/flows/242e6949-a800-401b-b9a8-a4e9fc058e4e/details). Each morning, this flow creates an automatic replies in Office 365 Outlook. It tells senders that my email response times are currently slower than I would like, gives them the names of others they can contact, and tells them how to contact me for urgent matters.

2. [Create Planner Task From Email - To-do Trigger](https://make.powerautomate.com/environments/Default-7b326d24-41ad-4f57-bc60-89e4a6ac721b/flows/d5d6a613-0c88-4ed5-9b78-7dce4dd30b82/details). When I flag an email in outlook, this flow will create a planner task. The title of the task will be set to the subject line of the email and the notes section of the task will have a link to the email embedded.

3. [Send a daily email of incomplete Planner tasks with no due date](https://make.powerautomate.com/environments/Default-7b326d24-41ad-4f57-bc60-89e4a6ac721b/flows/40ee45b0-edd5-4ee7-a12a-d44d51f6fe99/details). On a daily basis, receive an email with incomplete Planner tasks in HTML table format. Incldues tasks from the WIP and Next buckets only.
