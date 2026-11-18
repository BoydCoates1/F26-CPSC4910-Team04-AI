# About the Platform

## What the platform does
The Good Truck Driver Incentive Program is a web application intended to help trucking-related companies encourage safer and better on-road driving behavior through a points-based rewards program.

A company participating in the program is called a **sponsor**. Sponsors work with drivers, award or deduct points based on driving performance, and maintain a catalog of reward products. Drivers can use available points to request products from the catalog associated with their sponsor.

The project materials describe third-party product sourcing and fulfillment. The current website view alone may not establish the provider or delivery process; follow the order details and do not claim a specific provider unless confirmed there.

## Main user groups
- **Driver:** A person affiliated with a sponsor who earns and spends points.
- **Sponsor user:** A person authorized to manage a sponsor company's participation, drivers, points, products, and sponsor reports.
- **Administrator:** A platform-level user who can manage users and sponsors and access administrative functions.

The login form asks for a username and password, not a role. The current registration form offers Driver and Sponsor account types; it does not offer Administrator registration. Available menus and actions depend on the signed-in account.

## Basic program lifecycle
1. A driver creates an account and can apply to a sponsor through the dashboard's company section.
2. The sponsor reviews the application and accepts or rejects it.
3. An accepted driver is associated with the sponsor. The current dashboard can show more than one company association and lets the driver switch which company is active; do not assume there is only one association.
4. The sponsor awards or deducts points. Some point awards may be recurring or automated if that feature is available and configured.
5. The driver views the sponsor's reward catalog and chooses a product.
6. The driver uses points to place an order.
7. The driver and sponsor can review relevant point and order information. Platform administrators can review broader sales and audit information.

## Points and product value
The project brief describes a default point value of **$0.01 per point**, but that requirement alone does not confirm the value used for every sponsor or transaction. The website displays product costs and balances in points. Points are program rewards, not cash, and should not be described as withdrawable money.

## Important limitations
- A driver's catalog is tied to the driver's sponsor. Do not tell a driver that they can shop another sponsor's catalog unless the website explicitly supports that.
- The project brief describes a public third-party product source and third-party fulfillment; these requirements do not independently confirm the current provider or fulfillment process.
- A purchase made with points is an incentive-program transaction; do not make claims about payment or fulfillment beyond the website's order information.
- For current role-specific menu labels and navigation, use `website-navigation.md`; use labels currently visible in the website if they differ.

## What the chatbot should explain
The chatbot should explain the user-facing purpose and workflows in plain language. It must distinguish program rules in the project brief from features confirmed to be available in the live website.
