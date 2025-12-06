# Lumi Hub.CropAI

Remote sensing early warning system for maize farms.

## Analytics page (farm-specific AI Forecasting & Alerts)

A new `Analytics` page was added to host the Forecasting & Alerts UI (Crop Health, Soil Moisture, SMS alerts). Use the Analytics page to run model-based analysis for a single selected farm (rather than running across all farms). Steps:

- Start the Flask app: `python app.py`
- Open the site (`http://127.0.0.1:5000/`) and click `Analytics` or go to `/analytics`.
- Select a farm, choose start/end dates, enable the options you want, and click `Run Analysis`.

Notes:
- The analysis uses Google Earth Engine assets; make sure EE is authenticated and initialized.
- SMS integration is not implemented; enabling alerts will only prepare the alert message returned by the model.

## Dependencies

Install dependencies (use the provided `requirements.txt`):

```
pip install -r requirements.txt
```

Make sure you have authenticated Google Earth Engine prior to running the analytics (see Earth Engine docs).
# agritech
# agritech
# agritech
