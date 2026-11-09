# Product Availability Manager for CS-Cart

**🛑 PREMIUM ADD-ON: This repository does not contain the open-source code. It serves as the official listing and documentation page for the WebGraphiq premium add-on.**

**Product Availability Manager** is an automated catalog-lifecycle and urgency-countdown add-on for CS-Cart and Multi-Vendor. You set when a product becomes available and when that window ends; the add-on activates the product inside the range, applies an after-availability status when time is up, and can show an auction-style countdown before expiry.

## [🛒 Buy & View Live Demo](https://www.webgraphiq.com/product-availability-manager.html)

One-time license. The current price and the live demo are on the product page.

## Why store owners use it

- Schedule **Avail since** and **Avail until** with date and hour — pre-launch and limited-time items without manual status flips every morning.
- Inside the window the product is set to **Active**; after Avail until it takes the **After availability status** you chose (Active, Hidden, or Disabled).
- Storefront countdown shows days, hours, minutes, and seconds left — scarcity without rewriting the theme.
- Bulk-edit Availability on the products list so many SKUs get the same window and post-expiry rule.
- Leave Countdown Days empty to hide the counter; set it (default 3) to show only near the end.
- Optionally show the counter only on the product details page (hide it on category/list views).
- No CS-Cart core file edits.

## How the availability window works

1. On the product (or bulk Availability editor) you enter Avail since, Avail until, and After availability status.
2. While “now” is inside that range, the product is Active.
3. After Avail until, the after-availability status is applied automatically.
4. The storefront status pass runs at most once a minute (session timer) — use a private window when testing.

If until is earlier than since, the range is corrected so it stays valid.

## Countdown

- **Countdown Days to date expiry** — how many days before Avail until the counter appears. Empty disables it.
- **Display the counter only on the product details page** — list/category countdowns stay off when this is on.
- Product page uses the full time-left counter; list pages use the compact countdown when enabled.

## What you control

- Per-product Avail since / Avail until (date + hour) and After availability status.
- Global countdown day window and product-details-only display.
- License key on the add-on settings screen.

## Requirements

- CS-Cart or Multi-Vendor **4.12.1** or newer, including **4.21**
- PHP **8.3** or a current 8.x release used by that shop

## This repository

<p align="center">
  <a href="https://www.webgraphiq.com/product-availability-manager.html">
    <img alt="Buy and view the live demo" src="https://img.shields.io/badge/CS--Cart-Buy%20%26%20View%20Live%20Demo-28a745?style=for-the-badge&labelColor=1A365D">
  </a>
</p>

<p align="center"><strong>One-time license · availability window and urgency countdown</strong></p>

This is the public product listing. The add-on package, license checks, and source files are not published here. After purchase, the package is readable PHP under the WebGraphiq commercial license, installed from your WebGraphiq account.

Support: [webgraphiq.com](https://www.webgraphiq.com) · webgraphiq@gmail.com

© WebGraphiq. All rights reserved. [License](https://www.webgraphiq.com/license.html)

## Other Premium CS-Cart Add-ons by WebGraphiq

More CS-Cart and Multi-Vendor add-ons are listed on the [WebGraphiq GitHub profile](https://github.com/webgraphiq).
