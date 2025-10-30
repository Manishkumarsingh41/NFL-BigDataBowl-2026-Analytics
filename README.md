# NFL Big Data Bowl 2026 - Air-Time Defense Closure (ATDC) Metric

## Overview

This repository contains a complete analysis of the **Air-Time Defense Closure (ATDC)** metric for the NFL Big Data Bowl 2026 competition. The ATDC metric quantifies defensive effectiveness during passing plays by measuring how quickly defenders close the distance to receivers while the ball is in the air.

## Metric Definition

**ATDC (Air-Time Defense Closure)** = (Initial Distance - Final Distance) / Air Time

Where:
- **Initial Distance**: Distance from defender to receiver when ball is thrown
- **Final Distance**: Distance from defender to receiver when ball arrives
- **Air Time**: Time the ball is in the air (seconds)

Higher ATDC values indicate better defensive coverage - defenders closing distance faster during ball flight.

## Repository Contents

- `public_notebook.ipynb` - Complete Jupyter notebook with ATDC analysis
- `requirements.txt` - Python package dependencies

## Notebook Sections

1. **Setup and Imports** - Load required libraries (pandas, numpy, matplotlib, scikit-learn)
2. **Data Loading** - Generate synthetic NFL tracking data for demonstration
3. **ATDC Calculation** - Compute the metric for each play
4. **Visualizations** - Distribution plots, scatter plots, and play diagrams
5. **Feature Engineering** - Create derived features for modeling
6. **Machine Learning Models** - Linear Regression, Random Forest, Gradient Boosting
7. **Model Comparison** - Performance evaluation and cross-validation
8. **Results Export** - CSV files with metrics and summary statistics

## Getting Started

### Prerequisites

- Python 3.8 or higher
- pip package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Manishkumarsingh41/NFL-BigDataBowl-2026-Analytics.git
cd NFL-BigDataBowl-2026-Analytics
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook public_notebook.ipynb
```

4. Run all cells to execute the complete analysis

## Key Features

### Data Analysis
- Synthetic tracking data generation simulating NFL plays
- Distance calculations between defenders and receivers
- Event-based tracking (pass_forward, pass_arrived)

### Visualizations
- ATDC distribution histograms
- Air time vs ATDC scatter plots
- Closure distance analysis
- Play-by-play tracking diagrams with pursuit paths

### Machine Learning
- Three regression models (Linear, Random Forest, Gradient Boosting)
- Feature importance analysis
- Cross-validation with performance metrics
- Model comparison visualizations

## Output Files

The notebook generates:
- `atdc_analysis.png` - Overview visualizations
- `play_1_tracking.png` - Sample play diagram
- `model_comparison.png` - ML model performance
- `cross_validation_results.png` - CV analysis
- `atdc_metrics_with_features.csv` - Complete metrics dataset
- `atdc_summary_report.csv` - Summary statistics

## Applications

- **Player Evaluation**: Assess defensive back performance quantitatively
- **Coverage Analysis**: Compare effectiveness of different coverage schemes
- **Scouting**: Identify defenders with superior closing ability
- **Game Planning**: Develop strategies based on opponent ATDC profiles

## Future Enhancements

- Integration with actual NFL tracking data
- Analysis by coverage type and route combinations
- Player-specific ATDC profiles and trends
- Correlation with pass completion probability and EPA

## License

This project is part of the NFL Big Data Bowl 2026 submission.

## Author

Manish Kumar Singh

## Acknowledgments

- NFL Big Data Bowl for providing the platform and data
- Python data science community for excellent libraries