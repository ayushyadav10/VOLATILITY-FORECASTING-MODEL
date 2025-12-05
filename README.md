Implemented GARCH-family models (GJR/EGARCH) to capture asymmetric volatility and the leverage effect on daily log returns, explicitly modeling volatility clustering.
Developed a comparative framework by benchmarking GARCH models against a supervised Support Vector Regression (SVR) model trained on lagged realized volatility features.
Evaluated 3+ models using advanced loss functions (RMSE, MAE, QLIKE) and confirmed the EGARCH model's superior predictive accuracy (lowest QLIKE score) for high-stakes risk applications, including Value-at-Risk (VaR) calculations.
