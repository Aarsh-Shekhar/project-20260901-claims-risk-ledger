# Claims Risk Ledger

Scores synthetic insurance claims for review priority.

## What it includes

- deterministic sample data
- scoring and ranking logic
- command line report
- unit tests
- continuous validation workflow

## Run

```bash
python3 -m claims_risk_ledger.cli --input data/sample_claims.json
```

## Test

```bash
python3 -m unittest discover tests
```
