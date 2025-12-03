# GoogleColab_NHFD_WebScraper

Run the webscraper by opening the relevant jupyter notebook (`*.ipynb`) and clicking on the button at the top `Open in Colab`

There are currently two versions of the webscraper, they download the same data (latest extracts fr=om NHFD website) but in different formats:

- `GoogleColab_NHFD_WebScraper.ipynb`: legacy webscraper, it downloads data files divided by site and metric. You can currently upload these files in the relevant buckets of the project:

    - [nhsexec-nhfd-denoms-prod](https://console.cloud.google.com/storage/browser/nhsexec-nhfd-denoms-prod;tab=objects?forceOnBucketsSortingFiltering=true&authuser=0&inv=1&invt=Ab1rmw&project=nhsexec-dataupload-prod&supportedpurview=project&prefix=&forceOnObjectsSortingFiltering=false)

    - [nhsexec-nhfd-lengthofstay-prod](https://console.cloud.google.com/storage/browser/nhsexec-nhfd-lengthofstay-prod;tab=objects?forceOnBucketsSortingFiltering=true&authuser=0&inv=1&invt=Ab1rmw&project=nhsexec-dataupload-prod&supportedpurview=project&prefix=&forceOnObjectsSortingFiltering=false)

    - [nhsexec-nhfd-keyperformanceindicator-prod](https://console.cloud.google.com/storage/browser/nhsexec-nhfd-keyperformanceindicator-prod;tab=objects?forceOnBucketsSortingFiltering=true&authuser=0&inv=1&invt=Ab1rmw&project=nhsexec-dataupload-prod&supportedpurview=project&prefix=&forceOnObjectsSortingFiltering=false)

    - [nhsexec-nhfd-overall-performance-prod](https://console.cloud.google.com/storage/browser/nhsexec-nhfd-overall-performance-prod;tab=objects?forceOnBucketsSortingFiltering=true&authuser=0&inv=1&invt=Ab1rmw&project=nhsexec-dataupload-prod&supportedpurview=project&prefix=&forceOnObjectsSortingFiltering=false)

- `V2_GoogleColab_NHFD_WebScraper.ipynb`: new version of the webscraper. It downloads all data for all sites for a specific metric into 4 distinct files (denoms, LOS, KPI and OP). You can upload these files in the new bucket for the project (currently, UAT version only): [nhsexec-nhfd-uat]() (add link!)
