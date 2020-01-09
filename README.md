# Web scrapper python

This is a scrapper I did just for practice and testing with the `Pandas` library. I'm not responsible to whatever you do with this scripts. Do not use this for real investigations.

## Usage:

1. Add the news website you wish to scrap in the `extract/config.yaml` file following the examples there
2. Add the query selectors for the title, body and URL of the news
3. Add the `news_sites` variable you created from `extract/config.yaml` to the `news_sites_uids` array variable in the `pipeline.py` file
4. Run the scrapper with `pipeline.py`
5. The result will be saved in `load/newspapers.db` sqlite file

## Recomendations:
- Use Anaconda 3 for this scrapper to not install all the dependencies manually
- Suggestions are welcome
