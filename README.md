# jatin-b26.github.io

Public homepage for jatin-b26.github.io.

Google's OAuth consent screen uses this site as the app homepage and privacy
policy for Reminder Bot. The pages are identical to the ones in
reminder-bot-site; this repo serves them at the domain root so Search Console
can verify subdomain ownership.

## What is here

- `index.html` - one-page overview of what the bot does.
- `privacy.html` - privacy policy, including the contact address.
- `logo.png` - app mark. Upload the same file in the Google consent screen
  under Branding.

## Editing

Push to `master`. GitHub Pages rebuilds in about a minute.

Do not commit credentials, tokens, phone numbers, or private server details.
This repo is public.

## Search Console

`index.html` carries a `google-site-verification` meta tag for the URL-prefix
property `https://jatin-b26.github.io/`. Deleting the tag breaks verification,
and Google will reject the consent screen homepage again.
