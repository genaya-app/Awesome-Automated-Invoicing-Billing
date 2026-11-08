# Awesome-Automated-Invoicing-Billing

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.



I also have to flag what the search results actually support, because **"Zoho Invoicing" is not the product name**, and the open-source side is thinner than your emphasis suggests.



## The data problems



**"Zoho Invoicing" is not a distinct product.** Zoho's billing platform is **Zoho Billing** (formerly Zoho Subscriptions). Its published pricing is **Standard $39/month annual** or $50 monthly, focused on one-time billing; **Premium $79/month annual** or $100 monthly for recurring billing. Both include **$1M annual billed amount and 100K invoices/year**; above that requires Enterprise . **List Zoho Billing, not "Zoho Invoicing."**



**AvidXchange has no public list price.** The only pricing surfaced is from a county procurement contract: **$6.50 per transaction for first 12 months, $7.00 for months 13–24, $7.50 for months 25–36**, plus a **Minimum Transaction Fee** calculated as 80% of the monthly invoice/payment quantity . This is contract-specific, not a rate card.



**Stampli has no published pricing.** As of September 16, 2026, the pricing page showed no dollar amounts, tiers, or per-user rates—only a quote request . **Do not fabricate.**



**HighRadius' pricing is outcome-based, not list price.** Zero implementation fees, zero fees until go-live, then a **gain-share percentage of measured KPI improvement** . There is no per-seat or per-invoice figure.



**Zuora's edition comparison does not contain pricing.** It describes entitlements (Growth, Enterprise, Nine) but no dollar amounts . **Mark quote-only.**



## What the search results actually contain



**SaaS pricing (usable):**



| Platform | Pricing | Model |

|---|---|---|

| **Tipalti** | **Select from $99/month**; Advanced $199/month; Elevate, Accelerate, Plus custom  | Platform fee + transaction pricing; unlimited users  |

| **Bill.com** | **Team tier $650/month for 10 seats**; ACH $0.59, check $1.99, virtual card free, international USD wire $19.99, failed ACH $50  | Per-seat + per-transaction  |

| **Chargebee** | **Flow: $0 + 0.80% of invoicing** or **$99 + 0.65%**; break-even at $66K/month  | Percentage of volume  |

| **Stripe Billing** | **0.70% of billing volume** (replaced Starter/Scale tiers)  | Percentage of volume  |

| **Maxio** | **Grow $599/month** (up to $100K monthly billings); Scale quote-only  | Flat fee, unlimited users  |

| **Zoho Billing** | **Standard $39/mo annual**; **Premium $79/mo annual**  | Per-organization subscription  |

| **AvidXchange** | **$6.50–$7.50/transaction** (contract-specific)  | Per-transaction + MTF  |

| **Stampli** | **Not published**  | Quote-only  |

| **HighRadius** | **0% until go-live, then gain-share**  | Outcome-based  |

| **Zuora** | **Not published**  | Quote-only  |



**Open-source project (usable):**



| Project | What it actually does | Stars |

|---|---|---|

| **InvoiceShelf** | Open-source invoicing for individuals and businesses; PHP; **actively maintained** (pushed about 12 hours ago) | **1,558**  |



**InvoiceShelf is the only open-source invoicing project surfaced.** It is a self-hosted invoicing application, **not a billing platform** with subscription management, usage metering, or revenue recognition. Do not present it as a replacement for Chargebee or Stripe Billing.



## What I recommend



**Rename "Zoho Invoicing" to "Zoho Billing"** and use its published Standard/Premium tiers .



**Split into three honest categories:**



**1. AP Automation & Mass Payments** (proprietary): Tipalti ($99/mo) , Bill.com ($650/10 seats + per-transaction) , AvidXchange (contract-specific) , Stampli (quote-only) , HighRadius (outcome-based) .



**2. Subscription Billing & Revenue** (proprietary): Chargebee (0.80%/0.65%) , Stripe Billing (0.70%) , Maxio ($599/mo) , Zuora (quote-only) , Zoho Billing ($39–$79/mo) .



**3. Open-Source Invoicing**: **InvoiceShelf** (1,558 stars) —invoicing only, not billing platform.



**Flag the pricing model differences explicitly:** per-transaction (Bill.com, AvidXchange), percentage-of-volume (Chargebee, Stripe), flat fee (Maxio, Zoho), platform+transaction (Tipalti), and outcome-based (HighRadius) produce wildly different costs at the same invoice volume. A reader choosing between them needs that context.



If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not fabricate Stampli or Zuora pricing, present InvoiceShelf as a billing platform, or list "Zoho Invoicing" as a distinct product.
