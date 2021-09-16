# Installation
```
git clone https://github.com/mirusu400/Pinterest-infinite-crawler.git
cd Pinterest-infinite-crawler
pip install -r requirements.txt
```

# Usage
```
usage: main.py [-h] [-e EMAIL] [-p PASSWORD] [-d DIRECTORY] [-l LINK] [-g PAGE]

optional arguments:
  -h, --help                            show this help message and exit
  -e EMAIL, --email EMAIL               Your Pinterest account email
  -p PASSWORD, --password PASSWORD      Your Pinterest account password
  -d DIRECTORY, --directory DIRECTORY   Directory you want to download
  -l LINK, --link LINK                  Link of Pinterest which you want to scrape
  -g PAGE, --page PAGE                  Number of pages which you want to scrape
```

**Example:**
> main.py -e pkccr@naver.com -p qlalfqjsgh -d download_image -l https://www.pinterest.co.kr/pin/187321665740796468/ -g 2
