# Startup Success Forecasting

This project analyzes funding data for over 60,000 startups to understand key factors influencing their success and builds a model to forecast startup receptivity. 

## Data

The dataset contains information on:

- Startup companies - name, category, location, founding year etc.

- Funding rounds - type, amount raised, valuation etc. 

- Acquisitions - acquiring company, acquired company etc.

- Investors - name, number of investments etc.

Data is collected from public sources on startups, their funding and acquisitions.

## Analysis

Exploratory Data Analysis is conducted to understand:

- Funding trends over time and regions

- Top funded companies and industries 

- Impact of location and category on success

- Most active investors

- How funding rounds affect capital raised 

- Major acquisitions 

- Timeline from founding to acquisition

## Model

A CatBoost model is built to predict the market receptivity of a startup based on:

- Location
- Category

Oversampling handles class imbalance.

The model achieves 76.4% accuracy and 75.8% AUC score.

## Usage

The Jupyter notebook can be run with:

```
jupyter notebook startup_success.ipynb
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
