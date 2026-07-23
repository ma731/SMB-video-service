# Carrete — Communication-Channels Setup (Madrid, 2-founder MVP)

Everything below is free or near-free, optimized for two non-technical founders. Split into **Founder A = Sales/Comms** and **Founder B = Production**, but both can see everything.

## Layer 1 — Customer-facing channels

**WhatsApp Business app (the spine).** In Spain, WhatsApp is where SMB owners actually reply. Use the **free WhatsApp Business app** (not the Platform/API — the API needs a provider, per-conversation fees, and template approval, overkill until ~50+ active chats). The free app gives you: a business profile, a **catalog** (showcase the €149/€499/€799 tiers with sample reels), **quick replies** (`/precios`, `/trial`, `/brief`), **labels** (your CRM — see Layer 2), and **greeting/away messages**. Limits: broadcasts cap at **256 saved contacts**, no scheduling/automation, one phone per account (link ~5 devices via WhatsApp Web so both founders reply from laptops). Use **one shared business SIM**, not a personal number.

**Instagram.** Your reels are the portfolio, so IG is lead-gen too. Use a **Business/Professional account** (free), enable the native **WhatsApp button** on the profile, keep DMs open. Link-in-bio: free native IG links or a free **Linktree** → (1) WhatsApp, (2) landing page, (3) Calendly.

**Email — `hola@carrete.studio`.** Start with **Zoho Mail Forever Free** (custom domain, 5 users, 5 GB, no card; caveat: webmail/app only, no IMAP/POP on free). Cheapest fallback: a **registrar forwarding alias** to a Gmail. Upgrade to **Google Workspace Business Starter (~€6.90/user/mo + VAT)** when volume grows.

**Landing-page CTA routing.** Primary button → prefilled WhatsApp: `https://wa.me/34XXXXXXXXX?text=Hola%2C%20quiero%20ver%20ejemplos%20y%20una%20propuesta` (currently mailto until the number exists). Secondary → `#precios`.

**Booking call (optional).** **Calendly Free** allows **only one active event type** — make it "Carrete — 15-min llamada." Fine for an MVP.

## Layer 2 — Lead → client intake flow (dead simple)

Use **WhatsApp labels as the pipeline** — no separate CRM needed:

`1 Nuevo lead` → `2 Brief enviado` → `3 Recibiendo material` → `4 En edición` → `5 Entregado` → `6 Pitch venta` → `7 Cliente recurrente` → `Perdido`

1. **First contact** (WhatsApp/IG/email) → tag `1 Nuevo lead`, send the offer quick-reply.
2. **First-video brief** (once they sign) → send a **Google Form** (business name, location, what to highlight, vibe, deadline). Responses land in a **Google Sheet** (your client log). Tag `2 Brief enviado`.
3. **Asset collection** → venue sends photos/clips in the WhatsApp chat, or via a **Google Drive upload link**. Tag `3 Recibiendo material`.
4. **Delivery** → upload finished reel to the client's Drive folder + send on WhatsApp. Tag `5 Entregado`.
5. **Ask for the sale** → scripted quick-reply pitching the monthly plan. Tag `6 Pitch venta` → `7 Cliente recurrente` on yes.

Skip Notion/Trello at first — labels + one Sheet is lighter.

## Layer 3 — Internal founder coordination

- **Roles:** A = Sales/Comms (WhatsApp, IG, email, intake, Calendly). B = Production (briefs → editing → delivery). Both logged into the shared phone.
- **Shared storage — one Google Drive (free 15 GB; Google One 100 GB ~€1.99/mo later):**
  `Carrete/` → `00_Plantillas` · `01_Clientes/[Negocio]/(Material crudo, Entregables, Brief)` · `02_Ventas` (lead Sheet, pricing PDF) · `03_Admin` (facturas, contratos).
- **Task tracking:** one free **Trello board** (Backlog / Esta semana / Editando / Entregar / Hecho) *or* the WhatsApp labels — pick one, not both.
- **Weekly cadence:** **Mon 30-min** (pipeline review, who owns what) + **Fri 15-min** (delivered, follow-ups, money in). Daily coordination in a private 2-person chat separate from the business number.

## Set this up today — 6-step checklist
1. Cheap business SIM + **WhatsApp Business app**: profile, catalog (3 tiers), greeting/away/quick replies, the 8 pipeline labels; link WhatsApp Web on both laptops.
2. Convert Instagram to **Business**, add the WhatsApp button, set up free Linktree/IG links.
3. Set up **Zoho Mail Free** for `hola@carrete.studio` (or registrar forward to Gmail).
4. Point the landing-page primary CTA to the prefilled **wa.me** link; keep mailto secondary.
5. Create the **Google Form brief**, the **Google Drive** `Carrete/` tree, and one **Calendly** event.
6. Open a 2-person founders chat; book the recurring **Mon 30-min / Fri 15-min** syncs.

## Sources
- WhatsApp Business app guide 2026 — aisensy.com/blog/whatsapp-business-app-the-complete-guide
- WhatsApp broadcast limits 2026 — zepic.com/article/whatsapp-broadcast-limits-2026
- Calendly free plan 2026 — meetergo.com/en/magazine/free-calendly
- Zoho Mail free custom domain — zoho.com/mail/custom-domain-email.html
- Google Workspace pricing Europe 2026 — medhacloud.com/blog/google-workspace-pricing-in-europe
