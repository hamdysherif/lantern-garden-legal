# Legal documents — Lantern Garden

Store-ready drafts. Fill the placeholders, host them, and paste the URLs into both
stores. **Not legal advice** — consider a lawyer review for a paid, ad-supported app.

Files:
- `privacy-policy.md` — **required** by Apple & Google.
- `terms-of-use.md` — Terms of Use / EULA (optional for Apple if you use its
  standard EULA; recommended for Google).
- `app-ads.txt` — authorized-sellers file (host at your domain root; set your
  AdMob publisher ID).

## 1. Fill these placeholders (both docs)

| Placeholder | What to put |
|---|---|
| `<Legal entity or developer name>` | Your company or personal developer name |
| `<privacy@yourdomain.com>` / `<support@yourdomain.com>` | A real, monitored email |
| `<YYYY-MM-DD>` | The effective date you publish |
| `<your country/state>` | Governing-law jurisdiction (Terms §12) |

## 2. Host them at public HTTPS URLs

Both stores need **live, login-free web pages** (not a bare file download).

Free via **GitHub Pages**:
1. Create a public repo (e.g. `lantern-garden-legal`).
2. Add `privacy.html` and `terms.html` (convert the `.md` — GitHub Pages renders
   Markdown too if you enable Jekyll, or paste into a minimal HTML page).
3. Settings → Pages → Source = `main` / root → Save.
4. URLs: `https://<you>.github.io/lantern-garden-legal/privacy.html` (and `/terms.html`).

Alternatives: a Google Site, a public Notion page, or your own domain.

## 3. Where each URL goes

| URL | App Store Connect | Play Console | In-app |
|---|---|---|---|
| Privacy Policy | App Privacy → **Privacy Policy URL** | App content → **Privacy policy** | Settings link (task **B1**) |
| Terms of Use | (optional) EULA field, or leave blank for Apple's standard EULA | Store listing / in-app | Settings link (task **B1**) |

Give me the two hosted URLs and I'll wire the in-app Settings links (task **B1**).

## 4. Keep them in sync (avoids rejection)

The policy text **must match** your **Play Data Safety** form and **Apple App
Privacy** labels. If the policy lists the advertising ID / analytics / crash logs /
purchases, declare the same in both consoles — and vice versa. Update all three
together whenever you add or remove an SDK.
