---
section: Analysis
nav_order: 2
title: Stats
topics: Quantitive analysis; Qualitative analysis
description: >
    Most research will involve data of some sort that you will need to analyse and represent.
# youtubeid: moJgWrD6dwg
---

### Statistical analysis

{% capture text %}
The boundaries between qualitative and quantitative tools are becoming blurred. Some tools are specific to certain fields or use cases. [Seek methodological advice](https://www.griffith.edu.au/research/research-services/researcher-education-development/statistical-advice) before you start!
{% endcapture %}

{% include alert.html text=text color="warning" %}

{% capture outofscope %}
**Note:** an explanation of how these tools work is beyond the scope of this workshop.
{% endcapture %}

{% include alert.html text=outofscope color="info" %}

{% capture quant %}
 - **[RStudio](https://rstudio.com)**: Just learn R and RMarkdown. It's worth the learning curve. It does so much so easily. I'll put that cool 1 min RMarkdown video here. [RStudio.cloud](https://rstudio.cloud) is brilliant for the basics, with a built-in tutorial -- no software to download, just login and go. Simple [Teach Yourself R guide](https://www.maths.usyd.edu.au/u/UG/JM/DATA1001/r/current/guides/RGuide.html) from Usyd maths faculty, then check out the more detailed [R4DataScience](https://r4ds.had.co.nz/). And the [oxforddown](https://github.com/ulyngs/oxforddown) thesis template is my absolute favourite.
 
 - **[BlueSky Statistics](https://www.blueskystatistics.com/)**: Free open source app created by the SPSS creators for SPSS users who are transitioning to R. The windows and menus work just like SPSS, and it gives you the R code for every command you run. 

 - **[Intellectus Statistics](https://www.intellectusstatistics.com/)**: 7 days free trial might be enough. Intellectus was designed for nursing students who need to do statistics well but aren't mathematicians at heart. It tells you what hypothesis tests to run, and gives you the tables, charts and the written paragraphs that go with them (complete with $R^2$ and $p$-values). They also have a [free introductory stats course](https://www.intellectusstatistics.com/introductory-statistics-course/).

 - Provided by the uni, but not intuitive and poorly supported:
   - SPSS
   - SAS
   - Matlab
   - STATA
 


 {% endcapture %}

{% include card.html header="<i class='fas fa-sort-amount-down'></i> Quantitative analysis" text=quant %}

----

{% capture moretools %}

{% capture biotools %}

### bio.tools

[bio.tools](https://bio.tools) is a community driven effort to be a comprehensive, standards-based registry of software and resources related to bioinformatics and life sciences.

{% endcapture %}

{% include accordion.html title1="Bio.tools" text1=biotools %}

{% endcapture %}
{% include card.html header="Looking for more?" text=moretools %}