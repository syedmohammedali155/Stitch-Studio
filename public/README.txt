Make ONLY the following changes in the existing application. Do not change, remove, redesign, reposition, or break anything else.
1. Top Banner Text
Wherever the top banner currently says:
"🚚 Free Delivery across Rawalpindi"
Replace it with exactly:
"Perfect Fit, Every Time"
2. Remove Free Delivery Text
Remove "Free Delivery across Rawalpindi" from EVERYWHERE in the application.
Make sure there is no remaining "Free Delivery" text anywhere.
3. Gender Labels
Replace every occurrence of:
"Ladies" → "Ladies"
"Gents" → "Gents"
Apply these changes consistently everywhere in the UI, forms, dropdowns, filters, invoices, receipts, reports, tables, and any other relevant sections.
4. Payment Method Label
Replace every occurrence of:
"Cash on Counter" → "Cash / Online"
Apply this change consistently everywhere it appears, including UI, forms, dropdowns, invoices, receipts, reports, tables, and filters.
5. Select Garment / Suit Type
Update the existing Select Garment / Suit Type options to exactly:
Gents
Kameez Shalwar
Kameez Only
Shalwar Only
Waistcoat
Ladies
Simple Suit
Suit with Piping/Lace Palta
Shirt Only
Shalwar Only
Trouser Only
Do not add any other garment/suit types.
6. Additional Requirements & Fitting Options
The section:
"Additional Requirements & Fitting Options"
must be REMOVED ONLY FROM THE A5 INVOICE/PDF.
It must remain available in the Vault exactly as it is.
Important:
Keep this section and its data/functionality in Vault.
Do NOT show this section or its contents on the A5 invoice/PDF.
Do NOT delete its database/data functionality.
Do NOT remove it from customer records or Vault.
7. Logo CSS
Add/update the following CSS exactly as specified:
code
CSS
.login-logo-img {
    max-width: 300px;
    max-height: 100px;
    object-fit: contain;
    filter: drop-shadow(0 6px 14px rgba(0, 0, 0, 0.4));
}.inv-logo-img {
    max-width: 300px;
    max-height: 100px;
    object-fit: contain;
    display: block;
}
Apply .login-logo-img to the login logo and .inv-logo-img to the invoice logo where those classes are used.
Do not change the logo itself or distort its aspect ratio.
IMPORTANT — DO NOT CHANGE ANYTHING ELSE

Do not change any functionality.
Do not change database structure or field names unless absolutely required for displayed labels.
Do not remove any existing features.
Do not change PDF/invoice layout except removing "Additional Requirements & Fitting Options" from the A5 invoice.
Do not change A5 invoice size or formatting.
Do not change styling, spacing, colors, fonts, buttons, icons, or UX except for the exact CSS specified above.
Do not change measurement functionality.
Do not change invoice calculations.
Do not change PDF generation/download functionality.
Do not delete existing customer data.
Do not modify anything unrelated to the changes listed above.
Keep all existing data and functionality intact.
Implement ONLY these requested changes and preserve everything else exactly as it currently works.