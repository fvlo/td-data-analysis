ReadMe

Data collected on 5.5.2020

Retrieved as API calls in browser.

Data API exposed at:
https://www.randomtriviagenerator.com/questions?limit=6&page=1
limit: objects requested. Does not seem to be a maximum, seems to return duplicates (?) if limit>count
page: # of api calls - corresponds to scrolling down in browser for more questions

Data count API at:
https://www.randomtriviagenerator.com/questions/count
count=20522 when collected

datafile naming:
rtg[objects requested]-[number in request sequence].json

Assumptions TBC: [rtg20522-1 contains full data set], [rtg10000-1 & rtg10000-2 rtg522-3 also contain full data set, no duplicates], [rtg21000-1 contains full data set with some duplicates]