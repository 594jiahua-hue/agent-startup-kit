# ship-billing checklist

Use this checklist after generating or updating the billing flow.

## Core pages
- pricing page exists
- checkout flow exists
- subscription status page or section exists
- success page exists
- cancel page exists
- webhook handling is included

## Flow quality
- pricing to checkout flow is clear
- subscription state is shown correctly
- success and cancel states are handled clearly
- billing state is handled consistently

## Project safety
- unrelated pages were not broken
- missing API keys are clearly marked
- webhook secrets are not hardcoded
- product IDs and price IDs are documented
- manual setup steps are documented

## Final review
- explain what was added
- explain what still needs manual setup
- explain how to test the billing flow
