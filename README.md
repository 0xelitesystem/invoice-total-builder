# Invoice Total Builder

This tool builds an invoice from line items, applies a discount and a tax rate, and totals it. Discount applies to the subtotal first, then tax applies to the discounted amount. It copies a clean plain-text summary you can paste anywhere.

**Live demo:** https://0xelitesystem.github.io/invoice-total-builder/

## What it does

Add line items with a description, quantity, and unit price. Set a tax rate and an optional discount, either a percent or a flat amount. The tool shows the subtotal, the discount, the tax, and the total, updating as you type, and copies a plain-text summary of the whole invoice.

Discount is taken off the subtotal, then tax is calculated on what remains, which is the common order. Add and remove rows freely; nothing is saved.

## Aesthetic

A letterpress type tray: compartmented slots, a typewriter heading, two-color ink, and figures set in a monospace that lines up like a printed bill.

## Privacy

Everything runs in your browser. Nothing you type is sent anywhere, stored, or saved. Closing the tab clears it.

## Use it

Open `index.html` in any modern browser, or host it as a static page. No build step, no dependencies, no network calls.

## License

MIT. Copyright (c) 2026 0xelitesystem.
