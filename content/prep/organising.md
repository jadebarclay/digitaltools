---
section: Preparation
nav_order: 3
title: Organising your thoughts
topics: Personal knowledge management; Note taking; Mind maps
description: >
    It can help clarify your thinking enormously if you have a trusted system to keep, organise and connect your notes.
# youtubeid: moJgWrD6dwg
---

{% include figure.html img="taking-shape.jpg" alt="Lego stormtroopers building a starship" caption="Getting everything together (image by Reiterlied, licensed under CC BY-NC-SA 2.0)" width="75" float="left" %}

{% capture connectednotes %}
A new stable of lightweight apps designed to help researchers connect their thoughts together have begun to emerge. The idea behind their popularity is that knowledge tends to work associatively rather than hierachically. Most or all of them use Markdown syntax for writing. 

- **[Notion](http://www.notion.so)**: Notion is an all in one workspace. It allows you to make any number of pages, tables, links, databases and link them all together in just about any way imaginable. It was pretty slow, but speed and performance has improved recently. The main downside is that Notion is only available online, It's free for education (sign in with Google using Unikey). Notion has just released an API making it more interoperable with other apps, like automatically updating Notion with your Zotero references with the ['Notero' template](https://youtu.be/8IC8-mPbjCo). 

- **[Obsidian](https://obsidian.md)**: Obsidian is free (not open-source) and is developing rapidly. This is as flexible as Notion (a little less intuitive at first). All files are local markdown files, and Obsidian works offline which is perfect for privacy and security. The Dataview queries and automations save so much time, and now I never lose my notes or todo lists! Obsidian is how I sync all my PhD and other notes with my phone realtime.

- **[Roam Research](https://roamresearch.com)**: Roam Research popularised backlinks and nonlinear note-taking and became popular with academics. It is a paid service and web-only at this stage. It has a strong tribe around the app (follow #roamcult on twitter for tips), but performance can be pretty slow at times.
  
- Free and/or open source knowledge graph solutions that mimic the functionality of RoamResearch or Obsidian are available via [Logseq](https://logseq.com) github-hosted and accessed via desktop or browser, [AmpleNote]() online only with brilliant calendar integration, or [Foam](https://foambubble.github.io/foam/) locally-hosted accessed via VSCode. As I spend more time in VSCode (thanks to brilliant advances like GitHub CoPilot and Serenade.ai, and of course, Awesome Power Mode), I've been accessing my Obsidian notes with Foam more often. 

- **[RemNote](https://www.remnote.io/invite/P7gc4fQFcaGe9MpBX)**: RemNote is the lovechild of Anki and RoamResearch. It's particularly good with PDF annotations and flash cards. RemNote automatically populates your morning flash card cue from the notes you took in class -- lightning fast and seamless. Then they built the other non-linear note taking into it. RemNote is accessed via browser or desktop. When you google anything, your own notes also show up in the search results (pretty cool). It's freemium, and the PDF Annotation is in the paid tier. Education can get a [50% discount](https://www.remnote.io/invite/P7gc4fQFcaGe9MpBX).

- **[Microsoft OneNote](https://www.onenote.com/hrd)**: This is helpful if you want to use Office365 for shared project documentation. While OneNote can technically do linked notes, it is not specifically built for it.

{% capture bestconnected %}
**Our recommendation: Notion**

Notion is free for educational users. It is the easiest to get started with and the most visually attractive (if you like that sort of thing).  But it's only available online. There is a large and active community sharing Obsidian and Notion dashboards and templates, and many YouTube accounts describing how they use Obsidian and/or Notion to manage their study, research, and life.

{% endcapture %}

{% include alert.html text=bestconnected color="primary" %}

{% capture runnerup %}
**Runner up: Obsidian and RemNote**

Obsidian is free (and not open source) and your files are stored locally on your own machine for privacy and offline use. It is an interlinked folder of plain Markdown (.md) text files, meaning it's extremely easy to migrate to and from the app to any other. Obsidian has an active developer community and a growing library of open source plug-ins that extend its capability. 

When Obsidian is linked with Zotero, the Zotero 6 PDF Annotation features made me move away from RemNote for PDFs. Now Obsidian and Zotero both have stellar mobile apps.

{% endcapture %}
{% include alert.html text=runnerup color="info" %}

{% endcapture %}

{% include card.html header="<i class='fas fa-project-diagram'></i> Connected note taking apps" text=connectednotes img="Roam-Group-min.png" %}

___

{% capture notes %}
There are many other note-taking apps to suit every fancy.

 - [Airtable](www.airtable.com) - online relational database
 - [Evernote](https://evernote.com) - a venerable classic
 - [Rocketbook](https://getrocketbook.com.au/) is a new tool introduced by a previous attendee at this workshop. It captures your written notes in a paper book and converts it to digital text.
 - [DEVONThink](https://www.devontechnologies.com) (Mac only): A unified document, note, file and thought storage, management and linking database.
 {% endcapture %}
 {% include card.html header="<i class='fas fa-sticky-note'></i> Other note taking apps" text=notes %}

{% capture mindmaps %}
A mind map is a fantasic way to see and develop your ideas. You can mind maps to your connected notes app (above) to get the best of both worlds. 

 - ⭐️ [Diagrams.net](https://app.diagrams.net/) Fully free, with web and desktop versions. A wide range of templates. Integrates with OneDrive and Google Drive.
 - [MindMeister](https://www.mindmeister.com) - mind mapping tool. connect through O365 at Griffith
 - [MindNode](https://mindnode.com) is a popular Mac and iOS option.
 - [Scapple](https://www.literatureandlatte.com/scapple/overview)
 - [MindJet](https://www.mindjet.com)

 {% capture bestmind %}
**Our recommendation: Diagrams.net**

Free and open-source, fully-featured, highly integrated. What's not to like?
{% endcapture %}

{% include alert.html text=bestmind color="primary" %}

{% endcapture %}
{% include card.html header="<i class='fas fa-brain' color='pink'></i> Mind-mapping" text=mindmaps %}

{% include alert.html text="Now that you're completely organised, it's time to look at some tools for capturing data." color="success" %}