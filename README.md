# IAT814-Visualization

After git clone, run the below commands:

pip install -r requirements.txt

#Adding this again because sometimes altair charts do not render
pip install geopandas
pip install -U altair vega_datasets notebook vega==1.3
jupyter nbextension enable vega --py --sys-prefix

jupyter notebook --NotebookApp.iopub_data_rate_limit=10000000000
