This folder data-512-a1 contains all the files required for submission of assignment 1 in DATA 512. 
The goal of assignment 1 was to construct, analyze, and publish a dataset of monthly traffic on English Wikipedia 
where data is available: from December 1 2007 through August 30 2019.  Besides this README.txt, the files are as follows:

hcds-a1-data-curation.ipynb
	A Jupyter notebook that contains all commented code and walkthrough for reproducing all analysis done in this assignment. 

pagecounts_desktop-site_200712-201608.json
	A JSON file with monthly page count data from desktop English wikipedia from December 2007 until August 2016. Does not
	exclude web crawler traffic. 

pagecounts_mobile-site_201410-201608.json
	A JSON file with monthly page count data from mobile English wikipedia from October 2014 until August 2016. Does not
	exclude web crawler traffic.

pageviews_desktop_201507-201909.json
	A JSON file with monthly page count data from desktop English wikipedia from July 2015 until September 2019. 
	User agent traffic only.

pageviews_mobile-app_201507-201909.json
	A JSON file with monthly page count data from mobile app English wikipedia from July 2015 until September 2019. 
	User agent traffic only.

pageviews_mobile-web_201507-201909.json
	A JSON file with monthly page count data from mobile web English wikipedia from July 2015 until September 2019. 
	User agent traffic only.

en-wikipedia_traffic_200712-201809.csv
	Final processed data for use in page count visualization. Includes the fields:
		year - string year in which the month took pace
		month - string month in which the counts were calculated
		pagecount_all_views - int sum of all page counts as reported by pagecounts API
    	pagecount_desktop_views - int page counts from desktop as reported by pagecounts API
    	pagecount_mobile_views - int page counts from mobile as reported by pagecounts API
    	pageview_all_views - int sum of all page views from user agents as reported by pageviews API
    	pageview_desktop_views - int page views from desktop users as reported by pageviews API
    	pageview_mobile_views - int page views from all mobile users as reported by pageviews API 
	
Final_Visualization.png
	Image of final visualization of all English Wikipedia traffic counts

LICENSE
	MIT license for all code present	

Note that for the five JSON files, even though I mention in the notebook that I removed the wrapping "items" 
manually before doing further data processing, the versions included here are as they were immediately after the API calls.

Data was gathered from the Wikimedia REST API, Wikimedia Foundation, 2019. CC-BY-SA 3.0

Legacy Pagecounts API Documentation: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts
Pageviews API Documentation: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews

Wikimedia Foundation REST API terms of use: https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions
