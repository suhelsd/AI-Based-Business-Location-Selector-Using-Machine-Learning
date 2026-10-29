# AI-Based Business Location Selector – Café, Bhopal

**Important:** This demo uses synthetic data. Its scores are decision support, not a guarantee of profit.

## Deploy on Streamlit Community Cloud
1. Upload the contents of this folder to your GitHub repository.
2. In Streamlit Community Cloud, create/open the app and select `app.py` as the main file.
3. Ensure `app.py`, `ranked_locations.csv`, `dataset.csv`, and `requirements.txt` are committed.
4. Deploy or reboot the app.

The app checks for `outputs/ranked_locations.csv` and then `ranked_locations.csv`, so either CSV location is supported.

## Run locally
```bash
pip install -r requirements.txt
streamlit run app.py
```

If you want to regenerate model outputs, run `python pipeline.py` from the project root. This requires the dependencies in `requirements.txt`.
