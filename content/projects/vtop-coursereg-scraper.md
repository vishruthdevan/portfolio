---
title: VTOP Course Registration Scraper
disableshare: true
summary: 
draft: false
hidemeta: true
---

**VTOP Course Registration Scraper** is a Python script designed to scrape course registration information from the university website and save it into a CSV file. This extracted data can then be used for further integration with timetable creation software.

## Usage
- `pip install -r requirements.txt`
- Enter the required values in the `config` dictionary and add course codes of the required courses in the `courses` list
- Leaving the list empty will scrape all courses visible to you (BEWARE, YOU CAN GET SOFTLOCKED OUT FOR 15 MINUTES IF YOU DO THIS)
- `python scrape.py`

## Output
- A courses.csv file will be created.

## Related Links

- [GitHub Repository](https://github.com/vishruthdevan/vtop-coursereg-scraper/)