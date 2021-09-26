## Oilfield production forecast using LSTM algorithm

### What is this?

This is an algorithm built using Long Short-Term Memory Network (LSTM) with Keras Python package as an alternative to conventional Arps Decline Curve Analysis for future oil rate forecasting.

### Dataset
Dataset is available  from Volve field production data at https://www.equinor.com/en/what-we-do/digitalisation-in-our-dna/volve-field-data-village-download.html.
Raw Data consists of 24 columns of various numerical and categorical features and 15634 rows of samples. The data is simplified so only the chosen features used are the columns in the attached csv file.

### Output Example
From the image below, it can be seen that the blue line is the simulated data obtained from the model, while the actual gas production data is red (training data) and green (testing data) in color.

<a href="https://drive.google.com/uc?export=view&id=1lNINv5cvE8pFla_QjXo1tV1nr9ENZ4J7">
    <img src="https://drive.google.com/uc?export=view&id=1lNINv5cvE8pFla_QjXo1tV1nr9ENZ4J7"
    style="width: 500px; max-width: 100%; height: auto"
    title="Click for the larger version." />
</a>
