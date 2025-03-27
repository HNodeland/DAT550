# DAT550
DAT550 Project Repo


To configure the workspace, download the data set from [this link](https://paperswithcode.com/dataset/arxiv-10). Unzip it, and rename it to data.csv. Place the file inside the data-folder. The data set is too large for git, so the data-folder has been added to gitignore.

Additionally, as we use jupyter notebook, please run `pip install nbstripout` and `nbstripout --install` inside the repo locally. This hooks into Git, so every time you commit a notebook, it strips out output cells, but leaves code & markdown intact.