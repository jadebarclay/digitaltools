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
 - **[SPSS](https://www.griffith.edu.au/student-computing/available-software)**: Griffith provided, limited support

  - **[SAS](https://www.griffith.edu.au/student-computing/available-software)**: Griffith provided, no support.

 - **[Matlab](https://www.mathworks.com/products/matlab.html)**: available through some departments

 - **[STATA](https://www.stata.com/)**
 
{% capture relatedworkshops %}

**Related workshops**

- [Statistical Training Program](https://app.secure.griffith.edu.au/events/category/statistical-training-program)

{% endcapture %}

{% include alert.html text=relatedworkshops color="warning" %}

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