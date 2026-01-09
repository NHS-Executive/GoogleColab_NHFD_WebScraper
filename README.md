# GoogleColab_NHFD_WebScraper

There are currently two versions of the webscraper, they download the same data (latest extracts from the NHFD website) but in different formats:

## V2_GoogleColab_NHFD_WebScraper.ipynb (Latest version of the webscraper)
Run this webscraper by clicking on this link: 

https://githubtocolab.com/NHS-Executive/GoogleColab_NHFD_WebScraper/blob/main/V2_GoogleColab_NHFD_WebScraper.ipynb

The most recent version of the webscraper downloads all data for all sites for a specific metric into 4 distinct files (denoms, LOS, KPI and OP). You can upload these files in the new bucket for the project (currently, UAT version only): [nhsexec-nhfd-uat]() (add link!)

## GoogleColab_NHFD_WebScraper.ipynb (Legacy version of the webscraper)
Run this webscraper by clicking on this link: 

https://githubtocolab.com/NHS-Executive/GoogleColab_NHFD_WebScraper/blob/main/GoogleColab_NHFD_WebScraper.ipynb

This earlier version downloads more distinct data files divided by site and metric. 

You can currently upload these files in the relevant buckets of the project:

- [nhsexec-nhfd-denoms-prod](https://console.cloud.google.com/storage/browser/nhsexec-nhfd-denoms-prod;tab=objects?forceOnBucketsSortingFiltering=true&authuser=0&inv=1&invt=Ab1rmw&project=nhsexec-dataupload-prod&supportedpurview=project&prefix=&forceOnObjectsSortingFiltering=false)
    
- [nhsexec-nhfd-lengthofstay-prod](https://console.cloud.google.com/storage/browser/nhsexec-nhfd-lengthofstay-prod;tab=objects?forceOnBucketsSortingFiltering=true&authuser=0&inv=1&invt=Ab1rmw&project=nhsexec-dataupload-prod&supportedpurview=project&prefix=&forceOnObjectsSortingFiltering=false)
    
- [nhsexec-nhfd-keyperformanceindicator-prod](https://console.cloud.google.com/storage/browser/nhsexec-nhfd-keyperformanceindicator-prod;tab=objects?forceOnBucketsSortingFiltering=true&authuser=0&inv=1&invt=Ab1rmw&project=nhsexec-dataupload-prod&supportedpurview=project&prefix=&forceOnObjectsSortingFiltering=false)
    
- [nhsexec-nhfd-overall-performance-prod](https://console.cloud.google.com/storage/browser/nhsexec-nhfd-overall-performance-prod;tab=objects?forceOnBucketsSortingFiltering=true&authuser=0&inv=1&invt=Ab1rmw&project=nhsexec-dataupload-prod&supportedpurview=project&prefix=&forceOnObjectsSortingFiltering=false)
