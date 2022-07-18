---
section: Discovery
nav_order: 2
title: Automated search
topics: Citation trees; 
description: >
    This text is a 'section description'. Directly below this is an example section video embed. This demonstrates the front matter options in action.
# youtubeid: moJgWrD6dwg
---

{% capture citationtools %}
You can use tools to recommend similar or related papers to those you have. Some of them also help to visualise connections between the papers in your field or research project. 

- **[Google Scholar](https://scholar.google.com/scholar_alerts?view_op=list_alerts&hl=en)**: Create alerts in Google Scholar so you can be emailed when papers mathching specific keywords are published. A broad approach that might result in some irrelevant papers, but highly automated and convenient. 

- **[Connected Papers](https://www.connectedpapers.com)**: A visual tool to help researchers and applied scientists find and explore papers relevant to their field of work. Papers are arranged according to their similarity. Even papers that do not directly cite each other can be strongly connected and very closely positioned. Connected Papers is not a citation tree.

- **[Open Knowledge Maps](https://openknowledgemaps.org)**: This free visualisation tool groups related topics together and presents papers on those topics in a packed-bubble type graph. Can filter for open access journal articles. 

- **[ResearchRabbit](https://www.researchrabbit.ai)**: Billing itself as 'Spotify for researchers', ResearchRabbit is one of the newest tools here. It generates recommendations based on your library and your preferences. ResearchRabbit has recently added Zotero import/export and shareable public links, and private collaborative collections, so you can seamlessly share literature with nerdy friends and teammates. It can also email you with new relevant research, like Google Scholar.

- **[Inciteful](https://inciteful.xyz)**: This is my favourite. This generates citation maps like other tools, drilling down into detailed queries, and saving the citations, bibtex, or csv is so intuitive.

- **[LitMaps](https://litmaps.com)**: Plant a few papers and click `seed map` and the AI will generate a map of suggested papers you should read based on your preferences. Another Spotify radio for researchers.

- **[Bibliometrix](https://www.bibliometrix.org/home/)**: Biblioshiny is an interactive online app for the {bibliometrix} package in R, or you can run the same bibliometric analysis with the R code it generates. The website has a growing library of journal articles written using the package/app. This is pretty special. The citation maps and visualisations are among my favourites.

- **[VOSViewer](https://www.vosviewer.com/)**: Visualising scientific landscapes. VOSViewer takes the search results from SCOPUS or WebOfScience or PubMed and creates citation networks and other bibliometric visualisations. Heatmaps, co-citation networks, and other text mining functionality. Possibly the oldest well-maintained app on the list, this is the older cousin to Bibliometrix, great visualisations without giving you the R code.

- **[CitNet Explorer](https://www.citnetexplorer.nl/)**: CitNetExplorer is a software tool for visualizing and analyzing citation networks of scientific publications. It has not been updated in some time. 

- **[ORCID API]()** With the ORCID API you can scrape all the ORCIDs and DOIs and other details for all the people in your lab or your faculty or your institution. This is particularly helpful to grab DOIs that you then import into one of the 

{% capture bestcitengine %}
**Our recommendation: All of them!**

No one of these tools does everything the others do. Why not set them all up so you have the best chance of locating the latest and most relevant papers in your field? Just make sure to define your Google Scholar alert keywords narrowly so you don't get swamped!

{% endcapture %}

{% include alert.html text=bestcitengine color="primary" %}

{% endcapture %}
{% include card.html header="<i class='fas fa-tree'></i> Automating your paper discovery" text=citationtools img="connected-papers-cropped.png" %}