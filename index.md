---
title: Spreelet Privacy Notice
---
# Spreelet privacy notice

Last updated: October 2, 2026

Spreelet lets users simulate purchases and time-limited rentals with a virtual USD wallet. It does not place real orders or bookings. Supported sites are Amazon, Walmart, Cars.com, Zillow, Airbnb, Expedia (including expedia.net), Booking.com (including its booking.kayak.com flight partner), DoorDash, and Ticketmaster. Users can also enter virtual purchases manually.

## Information processed and stored

On supported pages, Spreelet reads listing and selected-offer information to detect the name, current price, currency, image URL, and source page URL. It also reads relevant quantities, rental durations, departure/return or check-in/check-out dates, origin and destination locations, and guest or traveler counts when available. It uses page text, structured listing data, site currency settings, and relevant page URL parameters to check the offer. It does not read passwords, payment card details, or browser history outside supported pages.

Spreelet stores the virtual wallet amount and its creation date, virtual purchase and rental records, and recent submission identifiers in Chrome's local extension storage. Records include the item name, shop, price, quantity, total, transaction date, image and source URLs, and any associated rental period or travel details. The extension uses this information to display the wallet balance, expense history, and listing details, and to prevent duplicate submissions. Local storage is not synchronized through Chrome Sync.

## Network requests and sharing

Spreelet has no server, account system, advertising, or analytics. It does not upload the wallet, transaction history, or travel details to Spreelet or sell that information.

To display listing and expense images, the browser requests the saved image URLs from the relevant website or image provider. These requests can disclose the user's IP address, requested image URL, and ordinary browser request information to that provider. Spreelet sets the image referrer policy to `no-referrer`, so those image requests do not include a Referer header. A saved image can be requested again when expense history is displayed. The image provider's own privacy policy applies to those requests.

When a user opens a supported site or a saved listing link, Chrome navigates to that website, which handles the visit under its own privacy policy.

## Permissions

- **Storage:** save the virtual wallet and transaction history locally.
- **Side panel:** show Spreelet beside the current browser page.
- **Scripting:** restore listing detection on supported pages when needed, such as after an extension reload.
- **Access to supported website domains:** read listing, offer, currency, and travel information for the virtual purchase or rental feature.

## User controls and retention

Information stays in local extension storage until the user deletes it or uninstalls Spreelet. Users can undo individual transactions or reset all Spreelet data from Settings. Export backup creates a JSON file containing the wallet and transaction records, including saved URLs and travel details; import backup replaces the local wallet and history with the selected backup. Exported files remain wherever the user saves them and must be deleted separately. Uninstalling the extension removes its Chrome local extension storage but does not delete exported backups.

Spreelet's use of information received from Google APIs adheres to the Chrome Web Store User Data Policy, including the Limited Use requirements.
