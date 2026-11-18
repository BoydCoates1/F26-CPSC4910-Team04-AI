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
4. `01-general/website-navigation.md`
5. The relevant role-specific documents.

## Important accuracy note
The website's current interface and behavior are the source for exact navigation and implemented workflows. The project brief describes requirements, not proof that a requirement is available in the website. Articles identify uncertain or policy-dependent details rather than presenting them as confirmed. Where a user reports that their live interface differs, direct them to the controls currently visible to them and do not invent steps.

## Document map
- `01-general/`: shared platform information and terminology.
- `01-general/website-navigation.md`: role-based menu labels and paths through the current interface.
- `02-drivers/`: driver account, points, products, orders, and notifications.
- `03-sponsors/`: sponsor account, driver management, points, products, reports, and notifications.
- `04-administrators/`: administrator account and platform-management tasks.
- `05-support/`: login help and general troubleshooting.
- `06-chatbot/`: behavior and response instructions for the chatbot.

## Maintenance
Update the relevant help document whenever the user-facing website workflow changes. Keep instructions aligned with the live interface. Never add passwords, API keys, access tokens, private customer data, or other secrets to this knowledge base.
