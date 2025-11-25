# Support / Tip Snippet — Cash App (safe)

If you'd like to include an optional, low-friction way for people to tip or support this project, you can add this snippet to a README, website, or social bio. These examples explicitly call out safety and best practices so contributors and donors understand the intent.

---

### Tip via Cash App

Markdown (simple):

```md
[Support the project — Tip via Cash App ($1kingdomkid81)](https://cash.app/$1kingdomkid81)
```

HTML (button):

```html
<a href="https://cash.app/$1kingdomkid81" target="_blank" rel="noopener noreferrer">Tip via Cash App — $1kingdomkid81</a>
```

Prefill a small amount (may not work on all platforms — test first):

```
https://cash.app/$1kingdomkid81/1
https://cash.app/$1kingdomkid81?amount=1
```

QR code (image embed):

```md
![Tip QR — $1kingdomkid81](https://api.qrserver.com/v1/create-qr-code/?size=300x300&data=https%3A%2F%2Fcash.app%2F%241kingdomkid81)
```

---

### Safety & Best Practices (BP)

- **Always double-check the Cashtag** before publishing: a single typo redirects funds. Confirm publicly visible Cashtag matches the intended recipient exactly.
- **Use small default amounts** when pre-filling (e.g., $1). Avoid encouraging large pre-filled amounts.
- **Make tips optional** — include a short, clear purpose so donors know what their money supports (e.g., "Support maintenance and hosting costs").
- **Avoid coercion** — never require or gate essential project features behind payments.
- **Privacy** — do not publish or store sensitive payment data in your repo or issue trackers (API keys, receipts, or private identifiers). Use secure channels for private support conversations.
- **Transparency** — briefly document how you’ll use funds (if you plan to use them for project costs, charity, etc.). This builds trust.

---

If you want I can add this snippet to `README.md` as a small "Support" section, create a QR image file in `assets/`, or add an optional `SUPPORT.md` link from the README. Tell me which you'd prefer and I'll commit that next.
