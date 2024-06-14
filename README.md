<!DOCTYPE html>
<html>
<head>
    <title>AutoMPG Data Analysis Project</title>
</head>
<body>
    <h1>AutoMPG Data Analysis Project</h1>
    <p>This is a data analysis project on the AutoMPG dataset using an IPython Notebook for exploratory analysis, data preprocessing, and machine learning modeling to predict the fuel consumption in km/l of vehicles.</p>

    <h2>File Description</h2>
    <ul>
        <li><code>autompg.ipynb</code>: The main project file containing the Python code for data analysis and modeling.</li>
        <li><code>autompg.csv</code>: The dataset used in the project, containing information about vehicles and their fuel consumption.</li>
    </ul>

    <h2>Requirements</h2>
    <ul>
        <li>Python 3</li>
        <li>Jupyter Notebook</li>
        <li>Python libraries: pandas, numpy, scikit-learn, matplotlib</li>
    </ul>

    <h2>Usage Instructions</h2>
    <ol>
        <li>Clone the repository to your computer:</li>
    </ol>
    <pre><code>git clone https://github.com/your-username/your-repository.git</code></pre>
    <ol start="2">
        <li>Open the <code>autompg.ipynb</code> file in a Jupyter Notebook environment.</li>
        <li>Execute the code cells in the notebook to perform data analysis and modeling.</li>
    </ol>

    <h2>Results</h2>
    <ul>
        <li>The linear regression model achieved an R² of 0.898, indicating that it explains about 89.8% of the variability in the data.</li>
        <li>The single-layer MLP model obtained a negative R², suggesting that it is performing worse than a model that predicts only the mean of the response variable.</li>
        <li>The MLP model with two hidden layers achieved an R² of 0.948, indicating that it explains about 94.8% of the variability in the data.</li>
    </ul>

    <h2>Conclusion</h2>
    <p>Based on the results, the MLP model with two hidden layers seems to be the most suitable for this problem, as it has the highest R² and appears to be capturing the patterns in the data better.</p>

</body>
</html>
