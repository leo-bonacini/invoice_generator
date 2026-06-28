# Invoice Generator

A zero-dependency, browser-based invoice generator that runs entirely in a single HTML file — no server, no build step, no installation required.

## Features

- **Fully editable** — click any field (company name, address, client details, line items, notes) to edit in place
- **Live calculations** — subtotal, tax, and total update automatically as you type
- **Multi-currency** — switch between USD, EUR, GBP, JPY, BRL, CHF, CAD, and AUD
- **Line item management** — add or remove rows on the fly
- **Bank / payment details** — dedicated section for transfer instructions
- **Print to PDF** — clean print stylesheet hides all editing controls
- **New invoice** — reset the form with one click

## Usage

1. Download or clone this repository
2. Open `invoice-generator.html` in any modern browser
3. Fill in your company details, client info, and line items
4. Adjust the tax rate if needed
5. Click **Print / Save PDF** to export

No internet connection required after the file is downloaded.

## Customisation

All styling lives inside the `<style>` block at the top of the file. The accent colour (`#4f8ef7`) and dark header (`#1a1a2e`) can be changed to match your brand in seconds.

## Browser support

Works in all modern browsers (Chrome, Firefox, Safari, Edge). The print-to-PDF feature works best in Chrome/Edge via **File → Print → Save as PDF**.
