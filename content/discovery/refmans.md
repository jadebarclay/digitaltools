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
- **[EndNote](https://libguides.library.usyd.edu.au/endnote)** is The university supported option. The library had guides to help you with this one. It's not my favourite.
  
- **[Zotero](https://www.zotero.org)** is free and open-source, with a dedicated community of developers and packages that help keep your references seamlessly synced across devices, collaborative collections and integrations with ResearchRabbit. Zotero has built-in PDF annotations and highlihgting, DOI and metadata validation, and realtime [integrations with Notion](https://youtu.be/8IC8-mPbjCo), Obsidian, Word, Google Docs, RStudio, VSCode -- wherever you do your writing + citing.
  
- **[Mendeley](https://www.mendeley.com)** was popular until Elsevier bought it and started dismantling everything that made it good. In the last year they have removed public groups, private groups, and other functionality. They jsut announced that desktop app is being retired 1 September 2022, with online as the only option. The web version has no export function at this time, and many people are migrating to Zotero before their PDFs and notes get trapped.

**Alternative options**

These options are popular, but don't come with any support from the University. 

- [Papers](https://www.papersapp.com)
- [F1000](https://f1000workspace.com/?lg)
- [BibTex](https://www.bibtex.org)
- [JabRef](https://docs.jabref.org/)
- [Citavi](https://www.citavi.com/en)

{% capture bestrefman %}
**Our recommendation: Zotero**

Zotero is Free and Open Source Software (FOSS), has a committed community of users and developers and has plugins that allow it to integrate with other useful apps. While there is no support from the University, there is endless support on twitter and the Zotero forums (and all the Logseq, Obsidian, RoamResearch, Notion forums and YouTube channels where you'll find folks who integrate their notes with Zotero).

{% endcapture %}

{% include alert.html text=bestrefman color="primary" %}


{% capture rurefman %}
**Runner up: EndNote**

Not everybody loves using EndNote, but you can get a free copy along with technical support through the University. 


{% endcapture %}

{% include alert.html text=rurefman color="info" %}

{% endcapture %}
{% include card.html header="<i class='fas fa-paperclip'></i> Most popular reference managers" text=text %}