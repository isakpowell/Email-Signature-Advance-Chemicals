# Advance Chemicals — Email Signature

## Before deploying to Exclaimer

You must upload the three images below to Exclaimer's image library and replace the local file paths in `signature.html` with the hosted URLs.

### Images to upload

| File | Used for |
|---|---|
| `advance_logo.png` | Company logo |
| `advance_banner.jpg` | Footer banner |
| `linkedin_icon.png` | LinkedIn icon |

### How to update the paths

1. Log in to **Exclaimer Cloud**
2. Go to **Design > Images** and upload all three files
3. Copy the CDN URL Exclaimer generates for each image
4. Open `signature.html` and find the three `src=` lines below and replace each value with the corresponding URL:

```
src="advance_logo.png"       → src="https://img.exclaimer.net/YOUR_LOGO_URL"
src="advance_banner.jpg"     → src="https://img.exclaimer.net/YOUR_BANNER_URL"
src="linkedin_icon.png"      → src="https://img.exclaimer.net/YOUR_LINKEDIN_URL"
```

> All URLs must use `https://` — Outlook blocks mixed-content images.

---

## Exclaimer placeholders

The following fields are populated automatically from Active Directory / Azure AD:

| Placeholder | Field |
|---|---|
| `{DisplayName}` | Full name |
| `{Title}` | Job title |
| `{PhoneNumber}` | Phone number |
| `{Email}` | Email address |

---

## Disclaimer

The confidentiality notice at the bottom of the signature (`Stainguard International Pty Ltd.`) should be updated to the correct legal entity name before deployment.
