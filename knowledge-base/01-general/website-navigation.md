# Website Navigation Guide

This guide describes navigation and actions visible in the current TruckerReward website implementation. Menus are role-sensitive; if an item is missing, confirm the signed-in account and its role. Do not promise access beyond what the user's account shows.

## Public pages and sign-in

When signed out, the main bar shows **Home**, **About Us**, **Log in**, and **Create account**. The Home link is hidden for sponsor users when signed in. **Create account** currently offers **Driver** and **Sponsor** account types; it does not offer Administrator. A driver can select a sponsor during registration when sponsors are available. An administrator account must be created through an authorized administrative process.

The **Log in** form asks for a username and password. It does not ask the user to select a role. Depending on the account and site configuration, other sign-in options may appear, such as a passkey or an external provider.

## Links available to signed-in users

The main navigation for signed-in accounts includes:

| Label or control | Destination or purpose |
|---|---|
| **Products** | Opens the product page. Drivers see their current sponsor catalog; other signed-in roles can browse products. |
| **Dashboard** | Opens the account dashboard, which has different content by role. |
| Notification bell | Opens the **Notifications** page. |
| Cart icon | Opens the **Cart**. |
| Profile menu (your username) | Opens **Profile**, **Settings**, or **Logout**. |

The skip link at the start of the page moves keyboard and assistive-technology users to the main content.

## Driver navigation and tasks

- **Points** and **Achievements** appear in the main navigation for drivers.
- The heart-shaped **Wishlist** control appears for drivers.
- **Announcements** appears for drivers and sponsors.
- The dashboard contains the driver's company/application information and points summary. Use **Apply To Company** or **Apply To Another Company** in that section to start an application. A pending application is shown there.
- **Past Orders** is linked from the driver dashboard. From **Past Orders**, a pending order can be changed, and a refund option appears only when the order is eligible.
- Select **Products** to search and sort the current catalog. Selecting a product opens its details. **Buy** adds it to the cart; use **Cart** to change quantities, remove items, or send an order.
- **Settings** includes appearance, account, notification, and security/privacy links. **Notification settings** is also linked from **Notifications**.

## Sponsor navigation and tasks

- **Announcements** appears in the main navigation. Sponsors can post an announcement to their drivers from that page.
- The sponsor **Dashboard** contains **Drivers** and **Sponsors** sections. The Drivers section includes driver search/filtering, point changes, removal, and an account-creation control. The applications icon in the Drivers heading opens **Applications**; the medal icon opens the **Leaderboard**.
- The Sponsors section lists sponsor users and has an **Add sponsor** control. Sending an invite emails the new sponsor user a link to set a password.
- Dashboard quick actions are labeled **Report**, **Catalog**, **Order**, and **Montly Points** (the last label is spelled that way in the current interface).
- **Report** opens the sponsor's **Driver Point Tracking** report. **Catalog** opens catalog management. **Order** opens **Driver orders**. **Montly Points** opens the sponsor's monthly-points settings.
- On the **Catalog** page, use **Add products** to browse products, then open a product and choose **Add to catalog**. The product page's back link returns to the catalog.

## Administrator navigation and tasks

Administrators see **Security**, **Accounts**, and **Banner** in the main navigation. The dashboard also has quick actions for **Manage Accounts**, **Driver Points**, **Edit Banners**, **Security**, **Audit Logs**, **Sales Reports**, and **Applications**.

- **Accounts** supports account search/filtering and administrator account actions. Open **Applications** to review sponsor or driver applications using the tabs on that page.
- **Audit log** has category, account, maker, and date filters; administrators also have a company filter.
- **Sales Report** has sponsor, date, and Summary/Detailed filters.
- An administrator's **View as** action is read-only and displays a banner with a way to return to the administrator account.

## Account and support links

- **Profile** shows account details and security activity; choose **Edit** to update editable profile fields.
- **Settings** includes **Edit account**, **Notification settings**, **Face ID and passkeys**, **Sign-in codes**, **Devices**, and **Your data**.
- From **Log in**, choose **Forgot your password?** to request a reset link.
- If a route or control described here does not appear, use the links visible in the current site and avoid guessing at a hidden menu.
