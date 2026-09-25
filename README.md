# Ezovion newsletter - send-ready handoff

## Use this file to send

Use `newsletter-email.html` in your email marketing platform. It is minified to about 81 KB and uses absolute image URLs hosted on the public GitHub Pages preview.

Do not attach the HTML or ZIP to recipients. Instead, import or paste the HTML into your email platform's custom HTML editor, then send a test email before the campaign.

## Recommended process

1. Download `newsletter-email.html` from this repository.
2. In Mailchimp, Brevo, HubSpot, Zoho Campaigns, or your approved sender, create a custom HTML campaign.
3. Import or paste the complete HTML file.
4. Send a test to Gmail and Outlook on desktop and mobile.
5. Add the sender's required unsubscribe link and mailing address if the platform does not add them automatically.
6. Schedule or send the campaign.

## Editing the newsletter

`newsletter.mjml` is the editable source. Make content or layout changes there, compile it to HTML, then regenerate the minified send-ready HTML before sending.

## Image hosting

The send-ready HTML uses image URLs from:

`https://johnlim9922.github.io/ezovion-newsletter-preview/assets/`

For a long-term production workflow, upload the images to the approved email platform or company CDN, then update the image URLs in the send-ready HTML.
