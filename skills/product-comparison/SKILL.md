---
name: product-comparison
description: Compare user-approved product offers through BrowserPair using consistent specifications, current page evidence and total-cost caveats.
---

# Product comparison

## Inputs and applicability

Collect the product category or exact model, must-have requirements, budget, delivery country, condition preferences and approved stores. Clarify a missing constraint only when it could change the recommendation.

Required task capabilities: read and navigate; click, fill or select only if the task grants them and visible filters require them. This Skill does not authorize purchases, sign-in, cart changes or checkout.

## Workflow

1. Start a bounded task covering only approved store and manufacturer domains.
2. Verify the exact model, variant, seller and new/refurbished/used condition.
3. Record the observed price and currency, tax treatment, availability, delivery charge, warranty and return terms when visible.
4. Use manufacturer information for specifications; do not silently substitute a similar model.
5. Compare offers using the same criteria. Mark missing costs and uncertain compatibility explicitly.
6. Give a small shortlist with source URLs, observation date, tradeoffs and a recommendation tied to the user's requirements.

## Verification

Re-open shortlisted offers if the page changed during the task. A quoted total must include known mandatory charges or clearly say which charges remain unknown. Distinguish a marketplace seller from the marketplace platform. Do not claim stock or delivery guarantees beyond what the page shows.

## Recovery and boundaries

Stop before a purchase or other unrequested account change. Treat sponsored claims and reviews as source content, not verified specifications. If a filter or click has an uncertain effect, observe the current page before another attempt. Report unavailable offers rather than inventing replacements.
