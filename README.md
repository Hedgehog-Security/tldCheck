# tldCheck
Author: Peter Bassill
Version: 1.0
Date: 10 October 2017

---
Usage tldCheck domainname "Brand Search Term"

for example: ./tldCheck hedgehogsecurity "Hedgehog Security"

Three output files will be created:
1. dns-hits.log - this file contains all the domain names that have a DNS entry.
2. brand-hits.log - this file contains all the domain names with a web server running on the url.
3. manual-review.log - this file is the urls that require a manual review.
