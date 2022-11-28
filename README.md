# ML5G-PS-012-Xdding
Team Xdding's solution to the Home User Network Classification problem statement by ZTE.

# Competition Data Zip Google Drive Link
https://drive.google.com/file/d/1LUT96tVeihO8YIZAPBPL3suLUFj4H2W3/view?usp=sharing

# Repository Overview
`models`: Directory storing the models that gave meaningful results: best RNN checkpoint, TSFresh + XGBoost model, and TSFresh + PCA + XGBoost model.

`notebooks`: Directory storing notebooks for each approach mentioned in the report: ROCKET classifier, LSTM RNN, manual feature extraction + XGBoost model, both TSFresh + XGBoost model variants, and `ts_regularization.ipynb` to generate preprocessed data for ROCKET/LSTM RNN notebooks from included zip file (please download from Google Drive link above and unzip first).

`ML5G-PS-012-Xdding-Presentation.pptx`: Project presentation.

`ML5G-PS-012-Xdding-Report.pdf`: Project write-up.

`requirements.txt`: Packages that need to be installed if you want to run the notebooks. GPU is highly recommended for LSTM RNN notebook.

`README.md`: You are here!
