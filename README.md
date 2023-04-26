# Final Project
Our goal with this project is to build multiple models which can sort out human
written news articles from articles written by OpenAI’s ChatGPT. These AI generated
articles will be created using a real headline scraped from various news sites.

Included in this repo are three python notebook files. The first one, `gather-data.ipynb` contains the code we used to build our dataset, mostly commented out, as we have that saved in a csv. It also includes our Naive Bayes model. Next is `data_vis.ipynb` which includes our data exploration, looking at, analyzing and visualizing several different attributes of the articles. Lastly there is `random_forest.ipynb`, which contains our Random Forest model.

Python libraries that are required to run these three files are:
*   Pandas
*   Scikit-learn
*   NumPy
*   Seaborn
*   Matplotlib
*   SciPy
*   nltk
*   openai
*   wordcloud
*   readability

The last of which can be install by running the following commands
`pip install py-readability-metrics`
`python -m nltk.downloader punkt`




