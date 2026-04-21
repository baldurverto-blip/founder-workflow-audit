# Checkout Configuration — Founder Workflow Audit

**Product:** Founder Workflow Audit  
**Price:** $97  
**Goal:** Simple async purchase with instant intake form delivery

---

## Current Setup

**Status:** Deprecated config | Checkout pending

### Live Page
**URL:** DEPRECATED

**Hard rule:** do not use here.now for zero-to-MRR landing pages or intake flows.
Use GitHub Pages or another explicitly approved surface instead.

The old here.now URL and intake path are intentionally retired and must not be reused.

---

## Option 1: Gumroad (Recommended)

### Steps:
1. Create Gumroad account: https://gumroad.com
2. Create product: "Founder Workflow Audit"
3. Set price: $97
4. Enable "Email delivery" with post-purchase redirect to intake form
5. Copy product link

**Product link format:**
```
https://gum.co/founder-workflow-audit
```

---

## Option 2: Lemon Squeezy (Better rates)

### Steps:
1. Create account: https://lemonsqueezy.com
2. Create product with price $97
3. Enable instant download
4. Copy checkout link

---

## Temporary Solution (Email-based)

Until checkout is wired, use Formspree for intake + manual invoice:

**Intake form:** https://formspree.io/f/mpwzgvjq

**Manual flow:**
1. Customer emails mads@vertostudios.com
2. Mads sends Stripe invoice or PayPal link
3. Upon payment, Mads sends intake form
4. Customer fills intake → audit delivered

---

## Post-Purchase Redirect

After payment succeeds, redirect to:
`https://verto.studio/workflow-audit/intake`

(Will load intake-form.html)

---

## Verification Checklist

- [ ] Gumroad/Lemon Squeezy product created
- [ ] Checkout link works
- [ ] Post-purchase redirect configured
- [ ] Test purchase flow completed