# DS4002-Project1
This project explores the hypothesis that Fashion Nova, a fast fashion company, will have a higher customer satisfaction expressed in clothing reviews in terms of quality, while reviews of a mass marketing company, namely Amazon, will express greater contentment with shipping time. 

## Software and Platforms
The scripts used to clean and analyze the data were written exclusively in Python, utilizing the seaborn, pandas, matplotlib, and nltk libraries to perform sentiment analysis and graph data. Furthermore, Google Sheets and Excel were also used to transfer tabular data and create more figures. The platform used was Windows, but the Python notebooks that contain the scripts may run on any operating system that has Python and the respective dependencies downloaded.

## Documentation Map
### DATA
This folder contains the initial data sets pulled from Kaggle, namely
* [amazon_clothing_reviews.csv](http://www.kaggle.com/datasets/john88999/women-reviews-on-clothes-on-amazon)
* [fashionnova_reviews.csv](http://www.kaggle.com/datasets/syedafroz6284/fashion-nova-reviews).

There is also a Data Appendix file, which follows [this framework](https://www.projecttier.org/tier-protocol/protocol-4-0/root/data/analysisdata/data-appendixfile/) to outline and explain the process behind the variables derived in the [Analysis Data File](https://github.com/amanzanares410/DS4002-Project1/blob/main/SCRIPTS/analysis.ipynb). 

### OUTPUT
This folder contains any materials outputted as a result of data analysis. There were multiple figures created in the notebooks from the SCRIPTS folder:
* Sentiment of Quality.png
* Sentiment of Shipping.png
* Sentiment of Both.png
* Side-by-side sentiment analysis.png

Additionally, any tabular data outputted was consolidated into Sentiment Breakdowns.xlsx, and the final data sets after all preprocessing and sentiment analysis are called amazon_final.csv and fashion_nova_final.csv.

### SCRIPTS
* exploratory.ipynb: the Python notebook used in exploratory data analysis to briefly describe the data sets
* analysis.ipynb: the Python notebook that performed the data analysis, starting from cleaning the data, preprocessing it, and running the sentiment analysis.

### LICENSE.md
This is the respective license for this project.

## Reproduction Instructions
1. Open the analysis.ipynb Python notebook from the SCRIPTS folder. This file has all of the necessary information to clean, process, and perform sentiment analysis on the original data sets. For this project, the .ipynb file may be opened in [Google Colab](https://colab.research.google.com/) using a GitHub link (File > Open Notebook > GitHub > [analysis.ipynb](https://github.com/amanzanares410/DS4002-Project1/blob/main/SCRIPTS/analysis.ipynb)) or manually downloading and uploading the file into Google Colab. 

Alternatively, this can be run locally in any IDE (Visual Studio Code, IntelliJ, etc.). This operates under the assumption that the user already has a version of [Python](https://www.python.org/downloads/) downloaded onto their operating system.

1. Download the analysis.ipynb from the SCRIPTS folder.
2. Open analysis.ipynb in the IDE of choice. 
3. Run the notebook. In VS Code, there is a "Run All" button that appears in the top row of the tab where the notebook opens. The first 'pip' command listed in the notebook should download all dependencies automatically (with permission given to the kernel if there is a pop-up window), but if not, open a new terminal by clicking the three dots in the top window > Terminal > New Terminal, and type in the recommended 'pip' installation commands as suggested by the IDE. Any other modules that are not on a given user's local machine may be installed with the command "pip install {module_name}", which may happen with the nltk module.

Both of these methods will produce all of the figures as seen in the OUTPUT folder. The spreadsheet entited "Sentiment Breakdowns" was created by manually copying and pasting tabular data directly outputted by the notebook. 
