# Paywall Audit — Billdu

**Live:** https://bterzic123.github.io/billdu-paywall-audit/ · prototype only: https://bterzic123.github.io/billdu-paywall-audit/?open=proto

Four ranked paywall ideas for Billdu, each backed by a number from Adapty's State of Paywalls 2026, a scorecard of the live paywall against the report, and a clickable rebuild of the paywall and the close moment in Billdu's own design (Today / Proposed switch, report pins, light/dark, EN / SK / FR, 30-second walkthrough).

## The ideas

| # | Idea | Report anchor | Outcome |
| :-- | :-- | :-- | :-- |
| 1 | Catch the close with one more offer (your own Lite annual, 4,99 € / month) | 4.5: only 4% of apps show a second paywall after close; it converts at 0.88× the main one and beats it in 45% of apps | ARPU +10–15% · based on Adapty data |
| 2 | Tell them where they are in their trial (day 1 of 7, expiry date, "Cancel anytime") | 5.3 trial explainer; Europe trial → paid 18.4% vs US 26.2%; 3.4: 74% of trial paywalls have reassurance near the CTA | ARPU +12–36% · observed in winning A/B tests |
| 3 | Put your 4.8 stars next to the price | 5.3 social proof; 3.1: only 27% of top paywalls use it | CR +10–30% · observed in winning A/B tests |
| 4 | Write the headline for the person reading it | 5.3 onboarding personalization; 3.5: only 2% personalize | CR +8–17% · observed in winning A/B tests |

**Slice used:** all categories (App Store category Business is not one of the report's eight) · Europe (largest App Store revenue region) · App Store data, Oct 2025–Sep 2026.

**Report:** [State of Paywalls 2026](https://adapty.io/state-of-paywalls/?utm_source=paywall-audit&utm_medium=github-pages&utm_campaign=sop_2026&utm_content=billdu)

## Grounding

Prices, plan names, features and screen layout come from Billdu's live iOS paywall (recorded October 2026). The rating (4.8 from 26,000+ ratings) is from the US App Store listing; the two reviews are quoted verbatim from the App Store. Light mode is an approximation, since only dark-mode frames were captured. Impact ranges are observed lifts from winning A/B tests in State of Paywalls 2026 and Adapty's own data, not measured results for Billdu.

## Run locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000. `?for=<name>` changes the first name used in the prototype.
