# Good Truck Driver Incentive Program — Chatbot Knowledge Base

This folder contains customer-facing help documentation for people using the Good Truck Driver Incentive Program website.

## Intended audience
- Drivers
- Sponsor users (people working for a sponsoring company)
- Platform administrators

This is a user-support knowledge base, not developer documentation. It intentionally excludes source code, database schemas, deployment instructions, test procedures, credentials, and internal development workflows.

## How to use these files
Load the Markdown files into the chatbot's knowledge source. If the chatbot platform supports metadata or tags, preserve the folder/category names so content can be retrieved by audience and topic.

Start with:
1. `06-chatbot/chatbot-instructions.md`
2. `01-general/about-the-platform.md`
3. `01-general/getting-started.md`
4. The relevant role-specific documents.

## Important accuracy note
The source project brief describes required behavior. The supplied work-item export contains 139 records: 60 marked New, 59 marked Active, and 20 marked Removed. It contains no records marked Completed or Closed. Work-item states and assignments do not prove that a feature is or is not working in the deployed website.

For that reason, these documents explain intended workflows while clearly identifying details that must be confirmed in the live website. They do not claim that every requirement has been implemented. Before publishing the chatbot, replace any `[CONFIRM IN WEBSITE]` notes with verified, current instructions or retain them as guidance for the chatbot not to overstate.

## Document map
- `01-general/`: shared platform information and terminology.
- `02-drivers/`: driver account, points, products, orders, and notifications.
- `03-sponsors/`: sponsor account, driver management, points, products, reports, and notifications.
- `04-administrators/`: administrator account and platform-management tasks.
- `05-support/`: login help and general troubleshooting.
- `06-chatbot/`: behavior and response instructions for the chatbot.

## Maintenance
Update the relevant help document whenever the user-facing website workflow changes. Keep instructions aligned with the live interface. Never add passwords, API keys, access tokens, private customer data, or other secrets to this knowledge base.
