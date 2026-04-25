# GitHub Pages Exploit Page

This repository hosts a reusable exploit page for the challenge.

## Usage

1. Publish this repository with GitHub Pages from the `main` branch.
2. Open the page directly, or override the webhook with:
   - `?token=<webhook-site-token>`
   - `?hook=https://webhook.site/<webhook-site-token>`
3. Send the resulting GitHub Pages URL to the challenge bot.

## Default Webhook

```text
https://webhook.site/24c8d56f-0f26-4940-88d9-fbf772754fad
```

## Example

```text
https://vvvdub.github.io/testtest/
```

## Notes

- Default target: `http://localhost:1337/`
- Optional override: `?target=http://localhost:1337/`
- Optional override: `?token=<webhook-site-token>` or `?hook=https://webhook.site/<token>`
