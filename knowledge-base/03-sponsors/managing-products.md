# Managing the Sponsor Product Catalog

## Overview
Each sponsor maintains its own catalog of incentive products. Drivers can browse and redeem points only against the catalog associated with their sponsor.

The project requirements specify that catalog products must be G- or PG-rated and that product information must come from a publicly accessible product API.

## Product information
The catalog may include:
- Product name.
- Description.
- Images.
- Current price or points required.
- Availability.
- Other information supplied by the provider.

Product pricing and availability can change at the third-party provider. The website is expected to retrieve current information and refresh it in real time. It should check current price and availability when a product is added to a driver's purchase set or cart.

## Adding a product
1. Sign in as a sponsor user.
2. Open the product catalog management area.
3. Search or browse the available provider products.
4. Review the product details, rating/content suitability, price, and availability.
5. Add the desired product to your sponsor catalog using the website's available action.
6. Confirm that the product appears in the sponsor catalog.

[CONFIRM IN WEBSITE: Product provider, search interface, add flow, and whether the website prevents duplicate catalog entries.]

## Updating or removing a product
Use the catalog-management options to edit or remove products where available. Review the effect on existing orders before removing a product.

[CONFIRM IN WEBSITE: Which fields can be edited manually and which are synchronized from the provider.]

## Price and availability
Do not rely on an old price or availability value. The current provider information shown during the purchase process should be treated as authoritative. A sponsor should not promise a product that the provider reports as unavailable.

## Content restrictions
The project requirements limit products to G- or PG-rated content. If a product's rating is missing or unclear, do not assume it qualifies; follow the program's catalog review policy.

## Third-party fulfillment
Products are supplied and delivered through a third party. Sponsors should use the order information and provider process available in the website for fulfillment questions.
