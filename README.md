# DAT550
DAT550 Project - Bag of Words Document Classification using Feedforward Neural Network and Recurrent Neural Network


## Reproducability
All data sets are too large for git, so the data-folder has been added to .gitignore.


To configure the workspace, download the arXiv100 data set from [this link](https://paperswithcode.com/dataset/arxiv-10) and unzip it. Place the file inside the data-folder. 


Additionally, download the [glove.6B.zip](https://nlp.stanford.edu/projects/glove/) data set, unzip it and place it in the data-folder.


All utalized libraries have been placed in `requirements.txt`, so you can simply run `pip install -r requirements` to configure it.


We have configured the implementation to be able to be run using [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html), we you want to run it on your GPU.



### For the authors
Additionally, as we use jupyter notebook, please run `pip install nbstripout` and `nbstripout --install` inside the repo locally. This hooks into Git, so every time you commit a notebook, it strips out output cells, but leaves code & markdown intact.