# Example-for-visualization-track
For the visualization track you can take a look in this repository to get some
inspiration!


Good luck! 

![logo](https://raw.githubusercontent.com/asreview/asreview-artwork/e2e6e5ea58a22077b116b9c3d2a15bc3fea585c7/SVGicons/IconELAS/ELASeyes24px24px.svg
"ASReview")

## Content
This reposity contains multiple scripts, used for plotting and visualizing the
records based on semantic analysis, created using a dutch BERT model
(robbert-v2-dutch-base).

The semantic analysis script
[`visualize_clusters.ipynb`](/scripts/visualize_clusters.ipynb) formats the
preprocessed data into a format that can be used by the ASReview
semantic_clustering extension. Output of this script is stored in the
`clustered.csv` file.

[`start_app.bat`](/scripts/start_app.bat) contains the command that starts the
ASReview semantic_clustering dashboard server, and opens the dashboard in a
browser.