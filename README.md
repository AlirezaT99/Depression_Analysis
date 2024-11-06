# Depression_Analysis
An Analysis on Depression using Actigraphy data. Conducted as the Digital Health and Human Behavior course project at Aalto University.

## Data
The dataset used in this study is obtained from [The Depression Dataset](https://www.kaggle.com/datasets/arashnic/the-depression-dataset) on Kaggle. For more detailed description refer to my `Report.pdf`.

## Repository Structure
The notebooks inside /notebooks include:
- `preprocessing.ipynb`: which includes code for the preprocessing step and plotting various aspects of the data.
- `analysis.ipynb`: which contains code for feature selection, decision tree classification, k-means clustering, and t-SNE visualization.

Finally, the [Report](./Report.pdf) file contains my analysis report including a comprehensive literature review, methodology, and the results.

## How to run
1. Obtain the data from the link above.
2. You can set up a virtual environment and install the usual requirements using the following command (No unusual package installation is required):
3. Run a jupyterlab server and simply run the cells in order.

```bash
pip install -r requirements.txt
```

