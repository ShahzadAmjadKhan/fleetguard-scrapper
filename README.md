# fleetguard-scrapper
1. This function scraps data from https://www.fleetguard.com
2. It takes search term as input and then navigate to site e.g for search term 'P553000' resulting url will be https://www.fleetguard.com/s/searchResults?propertyVal=P553000&hybridSearch=false&language=en_US
3. It loads the url, get data (supplier and product information) and build Json & print it.
4. Script uses Playwright library for navigation and data extraction
