# Risk Explanation

Domain: healthcare finance

This note records an implementation detail for Claims Risk Ledger. The current operating
threshold is `0.58` and review should happen within `12` hours
for records above that level.

## Checks

- confirm input fields are present
- verify score ordering is stable
- compare high exposure records against the review queue
