# coop-order-sorter
Help to sort our frontier order.

Open the app: https://real-raven575.github.io/coop-order-sorter/

- Orders arrive by link: a private Claude reader page reads the invoice and box slip scans, then its "Open sorter" button opens this app with the order loaded.
- Tabs: Start, Order, one tab per box, + Box, Finish. Every change saves at once in this browser, with a change log and a backup file option.
- Scan with a USB scanner, the live camera, or a photo. The app shows whose pile each item goes in, flags items that are not on the box's slip, and offers Google Lens when a barcode is unknown.
- All order data stays in your own browser (localStorage). Nothing is uploaded, and this repo holds no order data.
- Installable: in Chrome on Android, menu > "Add to Home screen" (or "Install app"). It then opens like an app and works offline.
