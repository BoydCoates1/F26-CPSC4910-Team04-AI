# Audit Logs

## What an audit log is
An audit log records important events and changes so authorized users can understand what happened and when. It supports accountability and helps investigate questions about account activity.

## Events specified in the project requirements
The system is required to maintain information about:

| Event category | Information to record |
|---|---|
| Driver application decisions | Date, sponsor, driver, decision status (accepted or rejected), and reason. |
| Point changes | Date, sponsor, driver, number of points, and reason. |
| Password changes | Date, user, and type of change. |
| Login attempts | Date, username, and whether the attempt succeeded or failed. |

## Who can view logs?
- Sponsor users: sponsor audit reporting is restricted to their own sponsor's drivers and relevant records.
- Administrators: administrative audit reports can be filtered across sponsors or for an individual sponsor.

Drivers should not be told that they can view administrative audit logs unless the live website explicitly provides that feature.

## Viewing audit information
1. Sign in with an authorized sponsor or administrator account.
2. Open the relevant audit-log report or area.
3. Select the available date range and category filters.
4. For administrators, select all sponsors or an individual sponsor if offered.
5. Run the report and review the results.

[CONFIRM IN WEBSITE: Exact navigation, categories, displayed columns, and export options.]

## Interpreting an event
Use the recorded date, user, sponsor, driver, status, point amount, and reason where available. An audit record describes what the system recorded; it does not necessarily explain the full circumstances behind the event.

## Privacy
Login and password records are sensitive. Share audit information only with people authorized to review it. Never include passwords, reset tokens, or secret credentials in a report or chatbot response.
