# WikipediaFRNetwork
Network of page-to-page links in FR version of Wikipedia, along with communities assignement. The communities of each page are the portals to which there is a link on the page

## Files
This repository contains the following files:

### pages.csv
List of the pages in the network. Each line contains first the id we have attributed to the page, and then its name on Wikipedia.

### portails.csv
List portals used in the pages. Each line contains first the id we have attributed to each portal, and then its name on Wikipedia.

### graph.csv
List of edges in the network. Each edge is represented by a source page id and a destination page id.

### page2portail.csv
List of belonging of pages to portals. Each line contains a page id followed by the id of a portal it belongs to.

## Method
This dataset has been built by parsing the 20/05/2023 dump of frwiki (freely available at https://dumps.wikimedia.org/frwiki/20230520/).

## Cite
This dataset has been introduced as part of the paper \[paper to come\]. If you use it, please cite

\[citation to come\]
