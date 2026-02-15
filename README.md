# Hackathon 3.0

This repository contains `job_market_data.json`, a simple dataset of in-demand skills and technology career paths.

## Data consistency fix

The `required_skills` master list has been aligned with the skills used in each role under `career_paths`.
Missing items that were added:

- HTML/CSS
- React
- Node.js
- Deep Learning

## Quick validation

```bash
python -m json.tool job_market_data.json > /dev/null
```
