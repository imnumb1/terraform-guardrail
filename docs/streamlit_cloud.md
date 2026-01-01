# Streamlit Cloud Deployment

## Prerequisites

- GitHub repo is public or connected to your Streamlit account.
- `streamlit_app.py` exists at repo root.
- `requirements.txt` contains `-e .` (already included).

## Step-by-step

1. Go to https://streamlit.io/cloud and sign in.
2. Click **New app**.
3. Select your GitHub repo: `Huzefaaa2/terraform-guardrail`.
4. Set **Main file path** to `streamlit_app.py`.
5. Choose **Deploy**.
6. Wait for the build to finish and open the app.

## Troubleshooting

- If imports fail, ensure the repo has `requirements.txt` at the root.
- If schema checks fail, disable schema mode or ensure Terraform CLI is available.
