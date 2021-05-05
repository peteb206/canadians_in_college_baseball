# canadians_in_college_baseball
Web scraper for Canadian Baseball Network

## [Canadians in College Baseball](https://www.canadianbaseballnetwork.com/canadian-baseball-network-canadians-in-college)
[![cbn-scrape-roster-full](https://github.com/peteb206/canadians_in_college_baseball/actions/workflows/cbn-scrape-roster-full.yml/badge.svg)](https://github.com/peteb206/canadians_in_college_baseball/actions/workflows/cbn-scrape-roster-full.yml)
- Python web scraper using pandas, requests, BeautifulSoup, json, re, numpy and other packages.
- Scan NCAA, NJCAA, NAIA, etc. schools' baseball rosters for players whose hometown references Canada or a Canadian city or province.
- Clean and format data due to differences in each school's website formats.
- Export results to Google Sheets and display nicely using gspread package.
- Links:
   - Input: [roster_pages.csv](roster_pages.csv)
   - Python script: [roster_scrape.py](roster_scrape.py)
   - Output:
      - [canadians.csv](canadians.csv)
      - [Google sheet](https://docs.google.com/spreadsheets/d/1gkPWOdC9cG6aDoJqKQNjX3Nhggc1XwpLlE6sgXa2guM/edit?usp=sharing)
   - Website view: [Canadians in College Baseball](https://www.canadianbaseballnetwork.com/canadian-baseball-network-canadians-in-college)

## [Canadians in College Baseball Stats](https://www.canadianbaseballnetwork.com/canadians-in-college-stats)
[![cbn-scrape-stat-full](https://github.com/peteb206/canadians_in_college_baseball/actions/workflows/cbn-scrape-stat-full.yml/badge.svg)](https://github.com/peteb206/canadians_in_college_baseball/actions/workflows/cbn-scrape-stat-full.yml)
- Python web scraper using pandas, requests, BeautifulSoup, json, re, numpy and other packages.
- Locate the season statistics of the players found by the Canadians in College Baseball scraper.
- Clean and format the data found from the NCAA, NJCAA, DakStats, etc. websites.
- Export results to Google Sheets and display nicely using gspread package.
- Links:
   - Input: [canadians.csv](canadians.csv)
   - Python script: [stat_scrape.py](stat_scrape.py)
   - Output:
      - [stats.csv](stats.csv)
      - [Google sheet](https://docs.google.com/spreadsheets/d/1_0ruBQeMgPGSYAtIDHKRpbA7c2jT0Fqvmk004Kon7yQ/edit?usp=sharing)
   - Website view: [Canadians in College Baseball Stats](https://www.canadianbaseballnetwork.com/canadians-in-college-stats)