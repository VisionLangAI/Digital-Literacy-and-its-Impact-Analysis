# Zero-Day Attack Detection in Airport Logistics Networks

## Overview
This repository contains the dataset **"Zero-Day Attack Detection in Airport Logistics Networks"**, which consists of 400,000 network traffic entries collected from airport logistics networks in major U.S. airports (Texas and Washington). The dataset includes both benign and malicious traffic, designed for research in cybersecurity, anomaly detection, and network analysis.

## Dataset Description
- **Total Entries:** 400,000
- **Attributes (26 total):**
  - Timestamps
  - Source IP
  - Destination IP
  - Protocols
  - Flags
  - Packet sizes
  - Attack families (labeled malicious traffic)
  - Anomaly scores
  - Predictions (benign or malicious)
  - And other relevant network traffic attributes

The dataset aims to help researchers design, evaluate, and benchmark models for detecting **zero-day attacks** in critical infrastructures, specifically in airport logistics.

## File Information
- **Dataset.csv** – Contains all traffic entries with 26 attributes.

## Applications
This dataset can be used for:
- Intrusion Detection System (IDS) development
- Zero-day attack prediction
- Anomaly detection in logistics networks
- Machine learning model training & evaluation
- Cybersecurity benchmarking

## Usage
```python
import pandas as pd

# Load dataset
df = pd.read_csv("Dataset.csv")

# Display basic info
print(df.head())
print(df.info())
```

## Citation
If you use this dataset in your research, please cite it as:

```
@dataset{zero_day_airport_2025,
  title     = {Zero-Day Attack Detection in Airport Logistics Networks},
  author    = {Anonymous},
  year      = {2025},
  publisher = {Self-published},
  url       = {https://example.com/zenodo-link}
}
```

## License
This dataset is released for **academic and research purposes only**. Commercial use is prohibited without prior permission.

---
**Maintainer:** Research Team on AI & Cybersecurity
