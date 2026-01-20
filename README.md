[![Python CI](https://github.com/shreyapatil9480/ba-analysis-demo/actions/workflows/python-ci.yml/badge.svg)](https://github.com/shreyapatil9480/ba-analysis-demo/actions/workflows/python-ci.yml)
![Python](https://img.shields.io/badge/python-3.11-blue)
![pytest](https://img.shields.io/badge/tested%20with-pytest-0A9EDC)

# Ba Analysis Demo

Which programs are at funding risk?

**Stakeholder:** Program Director

## Key Insights

- Three or more missed milestones precede at-risk funding reviews.
- Burn rate above 1.15x plan correlates with stakeholder escalation.
- Programs with 8+ stakeholders recover slower from milestone slips.

## Dataset

Primary file: `data/program_funding.csv`  
Target variable: `at_risk`

## Getting Started

```bash
pip install -r requirements.txt
jupyter notebook notebooks/exploratory_analysis.ipynb
```


## Testing

```bash
pip install -r requirements.txt
pytest tests/ --cov=src
```

## CLI Usage

```bash
python src/train.py
python src/predict.py --input data/sample_input.csv
```

## Next Steps

Containerize training pipeline for scheduled retraining.

---
*Analytics portfolio project — 2025-10*

<!-- build 8 -->

### Implemented

```bash
pip install -r requirements.txt
docker build -t train . && docker compose run train
```
