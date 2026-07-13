# ZATTARI — Trial Funnel Email Automation

Six-email sequence that runs the 7-day free trial funnel end-to-end: capture → build updates → urgency → checkout → win-back.

| # | File | Send | Trigger / goal |
|---|---|---|---|
| 1 | `01-welcome.html` | Instantly | Trial signup confirmed, sets expectations, links audit questionnaire |
| 2 | `02-day2-audit.html` | Day 2 | Audit delivered — “here's what's leaking” |
| 3 | `03-day4-draft.html` | Day 4 | Live draft link, asks for feedback |
| 4 | `04-day6-ending.html` | Day 6 | Trial ends tomorrow urgency |
| 5 | `05-day7-checkout.html` | Day 7 | Stripe checkout link |
| 6 | `06-day9-winback.html` | Day 9 | Didn't convert; one-question exit + save offer |

## Placeholders

`{{name}}` `{{business}}` `{{plan}}` `{{plan_price}}` `{{draft_url}}` `{{checkout_url}}` `{{audit_url}}` `{{cal_url}}`
