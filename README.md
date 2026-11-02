# Load Shedding Risk Bangladesh

A web app that estimates the chance that tomorrow's highest hourly load shedding in Bangladesh exceeds 100 MW, explains the estimate with SHAP, and shows the results of the study "Two Crises, Nine Zones: Explainable Early Warning of Load Shedding in Bangladesh".

- Everything runs in the browser: the XGBoost model (600 trees) is embedded in `index.html`, and SHAP values are computed exactly in JavaScript.
- No server, no database, no tracking.

Author: Md. Shoyaif Rahman (UITS). Supervisor: Shad Ahmed. Research prototype for education, not an official forecast.
