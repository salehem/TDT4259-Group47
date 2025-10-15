# TDT4259 – Group 47: Social Media vs Productivity

This repo contains our course project for **TDT4259 – Applied Data Science**.  
We explore the relationship between social media usage and productivity using Python.

## Repo structure
TDT4259-Group47/
├─ data/ # local only (ignored by git)
│ └─ social_media_vs_productivity.csv
├─ notebooks/
│ └─ EDA.ipynb # first exploratory notebook
├─ reports/
│ └─ figures/ # exported plots for report
├─ requirements.txt
└─ .gitignore


## Setup (VS Code recommended)
Create and activate a virtual environment:
python -m venv .venv
Windows: .venv\Scripts\activate
macOS/Linux: source .venv/bin/activate

Install dependencies:
pip install -r requirements.txt


### Add the dataset
Place the file social_media_vs_productivity.csv inside the data/ folder.
The file is ignored by git so it will not be uploaded to GitHub.

This keeps the repository small and avoids sharing large or private data files.
Each teammate should download or copy the dataset locally into their own data/ folder before running the notebook.

### Run the notebook
Open notebooks/EDA.ipynb in VS Code.
Select the .venv kernel at the top-right of the notebook and run all cells in order.
The dataset path used in the notebook is:
pd.read_csv("../data/social_media_vs_productivity.csv")





