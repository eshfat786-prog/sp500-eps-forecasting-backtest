S&P 500 Quarterly EPS Forecasting Backtest (2020Q1–2026Q3)
This repository evaluates out-of-sample quarterly Earnings Per Share (EPS) forecasts across 20 S&P 500 companies (540 company-quarters) across 5 sectors using expanding-window cross-validation:
• Models Tested: Human Consensus (estimatedEPS), AutoARIMA (SARIMA), Meta Prophet, and equal-weighted hybrids (Human + SARIMA, Human + Prophet).
• Evaluation Metrics: MAE, RMSE, sMAPE (%), and Newey-West adjusted Diebold-Mariano (DM) tests with Holm-Bonferroni p-value corrections across sectors and macro regimes (Pandemic Shock vs. Post-Pandemic).
• Key Files: backtest_results_full.csv (full panel predictions and actuals) and backtest_imputation_log.txt (training-only imputation audit log).
Let me know once you have the files downloaded—if you'd like, we can inspect specific companies inside backtest_results_full.csv or write up the conclusions for your report!
