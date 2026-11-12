# About the Platform

## What the platform does
The Good Truck Driver Incentive Program is a web application intended to help trucking-related companies encourage safer and better on-road driving behavior through a points-based rewards program.

A company participating in the program is called a **sponsor**. Sponsors work with drivers, award or deduct points based on driving performance, and maintain a catalog of reward products. Drivers can use available points to request products from the catalog associated with their sponsor.

Products are supplied and delivered by third parties. The website manages the incentive experience and records purchases; it is not necessarily the product manufacturer or delivery company.

## Main user groups
- **Driver:** A person affiliated with a sponsor who earns and spends points.
- **Sponsor user:** A person authorized to manage a sponsor company's participation, drivers, points, products, and sponsor reports.
- **Administrator:** A platform-level user who can manage users and sponsors and access administrative functions.

The website should determine the user's access from their account. Users should not have to choose a role type on the login screen.

## Basic program lifecycle
1. A driver applies to or is otherwise connected with a sponsor through the program's driver-application process.
2. The sponsor reviews the application and accepts or rejects it.
3. An accepted driver is associated with that sponsor.
4. The sponsor awards or deducts points. Some point awards may be recurring or automated if that feature is available and configured.
5. The driver views the sponsor's reward catalog and chooses a product.
6. The driver uses points to place an order.
7. The driver and sponsor can review relevant point and order information. Platform administrators can review broader sales and audit information.

## Points and product value
The project requirements specify a default point value of **$0.01 per point**. Sponsors may be able to set a different dollar value for their points. The value configured by a sponsor determines the program's point-to-dollar valuation; it should not be assumed that points are cash or can be exchanged for money.

## Important limitations
- A driver's catalog is tied to the driver's sponsor. Do not tell a driver that they can shop another sponsor's catalog unless the website explicitly supports that.
- Product prices and availability are expected to come from a public third-party product API and may change.
- Product fulfillment is handled by a third party.
- A purchase made with points is an incentive-program transaction, not necessarily a direct payment to the product seller by the driver.
- Exact navigation labels and screen layouts may change. Use the labels currently visible in the website.

## What the chatbot should explain
The chatbot should explain the user-facing purpose and workflows in plain language. It must distinguish program rules in the project brief from features confirmed to be available in the live website.
