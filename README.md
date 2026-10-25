# Social Media Data Collection

Jupyter notebooks that collect Persian text from social media platforms and forums for research on offensive language. Collection is based on a Persian offensive word lexicon (`Only_Persian_Offensive_lexicon.json`), and each notebook saves its results as a CSV file.

## Notebooks

`X_DataCollection1.ipynb` searches X through Nitter for Persian tweets containing each lexicon word.

`Instagram_DataCollection2.ipynb` collects the captions, comments and replies of the posts listed in `instagram_post_links.txt`.

`TikTok_DataCollection3.ipynb` collects the captions, comments and replies of the posts listed in `tiktok_post_links.txt`.

`Ninisite_DataCollection4.ipynb` collects posts from the newest topics of selected Ninisite forums and marks the lexicon words each post contains.

`Reddit_DataCollection5.ipynb` searches Reddit comments for each lexicon word with Selenium and keeps up to three Persian comments per word.

`Steam_DataCollection6.ipynb` collects the reviews, discussion posts and comments of the Steam pages listed in `steam_links.txt` and keeps the Persian texts.

Collected data is not included in this repository.
