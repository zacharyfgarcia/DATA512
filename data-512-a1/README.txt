This folder data-512-a1 contains all the files required for submission of assignment 1 in DATA 512. The goal of assignment 1 was to construct, analyze, and publish a dataset of monthly traffic on English Wikipedia from January 1 2008 through August 30 2019.  Besides this README.txt, the files are as follows:

hcds-a1-data-curation.ipynb
pagecounts_desktop-site_200712-201608.json
pagecounts_mobile-site_201410-201608.json
pageviews_desktop_201507-201909.json
pageviews_mobile-app_201507-201909.json
pageviews_mobile-web_201507-201909.json
en-wikipedia_traffic_200712-201809.csv
Final_Visualization.png
LICENSE



Note: for these five files I mention in the notebook that I removed the wrapping "items" from the JSON files before doing further data processing.  I have chosen to upload the versions before doing this extra step. 





Data was gathered from the Wikimedia REST API, Wikimedia Foundation, 2019. CC-BY-SA 3.0

Page Counts API: https://wikimedia.org/api/rest_v1/#!/Pagecounts_data_(legacy)/get_metrics_legacy_pagecounts_aggregate_project_access_site_granularity_start_end

Page Views API: 
https://wikimedia.org/api/rest_v1/#!/Pageviews_data/get_metrics_pageviews_aggregate_project_access_agent_granularity_start_end

Wikimedia Foundation REST API terms of use: https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions

