---
section: Discovery
nav_order: 3
title: Referencing
topics: Reference managers
description: >
    Choosing the right reference manager for your workflow can make a big difference to your experience.
# youtubeid: moJgWrD6dwg
---
 
 {% capture text %}
- [EndNote](https://www.griffith.edu.au/library/study/referencing) is Griffith's supported option. [Workshops](https://www.griffith.edu.au/research/research-services/researcher-education-development/workshop-calendar) and [video resources](vimeo.com/user/82369617/folder/1569944) are available too.
- [Zotero](https://www.zotero.org) is free and open-source. This makes it a popular option among FOSS enthusiasts.
- [Mendeley](https://www.mendeley.com) is popular in part because of its inbuilt social network.

**Alternative options**

These options are popular, but don't come with any support from the University. 

- [Papers](https://www.papersapp.com)
- [F1000](https://f1000workspace.com/?lg)
- [BibTex](https://www.bibtex.org)

{% capture bestrefman %}
**Our recommendation: EndNote**

Not everybody loves using EndNote, but you can get a free copy along with technical support through the University. That makes it worth the price of admission. 

{% endcapture %}

{% include alert.html text=bestrefman color="primary" %}


{% capture rurefman %}
**Runner up: Zotero**

Zotero is Free and Open Source Software (FOSS), has a committed community of users and developers and has plugins that allow it to integrate with other useful apps. The only downside is that there is no support fro the University.

{% endcapture %}

{% include alert.html text=rurefman color="info" %}

{% endcapture %}
{% include card.html header="<i class='fas fa-paperclip'></i> Most popular reference managers" text=text %}