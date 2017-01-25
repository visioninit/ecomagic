# ecomagic

This is an early work in progress (2nd day of effort), please keep that in mind.  The goal is to port the current site into Drupal 8 on a 1:1 basis and provide a responsive interface

Steps so far:

1. Site indexed using xml-sitemaps spidering tool to get a list of urls https://www.xml-sitemaps.com/
2. Ran python script 'scraper.py' (included) to pull html content from pages and generate CSV
3. Some tweaking is applied to the CSV to adjust various fields such as URLS, aliases (still in progress)
4. Installed and configured Drupal 8 migrate modules: migrate plus, migrate tools, migrate_source_csv https://www.mtech-llc.com/blog/lucas-hedding/migrating-using-csv

