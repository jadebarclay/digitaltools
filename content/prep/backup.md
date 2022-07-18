---
section_id: Preparation
nav_order: 2
title: Backup
topics: Storage; Reliability; Sync; Backup
description: >
    Find a place to put your research data. Don't lose it. Keep it secure.
# youtubeid: moJgWrD6dwg
---

## Where will your precious data live?

Your data storage location is critical. It needs to be three things: reliable, secure, and backed up.

### Reliability

{% include modal.html button="What do you mean by 'reliability'?" color="info" title="About reliability" text="Reliability means there's a very low chance that the medium you've recorded your data on will fail. Modern computer hard drives are fairly reliable, but every drive will fail eventually. Laptop hard drives in particular can be less reliable." %}

It's much better for reliability to entrust your data storage to a cloud provider. Cloud providers host data on servers with 'failover redundancy', meaning if one server ever fails, another is ready to take its place instantly. This is how they can advertise '99.999% uptime'. 

{% capture syncoptions %}
- **[Cloudstor](https://cloudstor.aarnet.edu.au)**: powered by AARNet (The Australian Academic Research Network) and provides students and researchers with a Terabyte of free, ultra-fast storage. It's easy to set up and works just like Dropbox.

- **[Google Drive](https://www.google.com/drive/)**: Everyone knows this one. 

- **[OneDrive](https://griffitheduau-my.sharepoint.com/)**: 1TB of space is provided to you by Griffith. Integrates with other Microsoft 365 services.

{% capture note %}
**Note:** When signing in to OneDrive, be sure to use your Griffith credentials rather than a personal Microsoft account.
{% endcapture %}
{% include alert.html text=note color="info" %}

- **[Dropbox](https://www.dropbox.com/)**

{% capture cloudstor %}
**Our recommendation: AARNet Cloudstor**

[Cloudstor](https://cloudstor.aarnet.edu.au) is powered by AARNet (The Australian Academic Research Network) and provides students and researchers with a Terabyte of free, ultra-fast storage. It's easy to set up and works just like Dropbox.
{% endcapture %}

{% include alert.html text=cloudstor color="primary" %}

{% include video-embed.html youtubeid="mGaqxrrxfgA" caption="Signing in to Cloustor" %}

{% endcapture %}

{% include card.html header="<i class='fas fa-sync'></i> Online storage & sync options" text=syncoptions img="storage-cropped.png" %}
___

## Keeping more than one perfect copy of your data

{% capture warning %}
**Remember:** sync is not the same as backup!
{% endcapture %}
{% include alert.html text=warning color="danger" %}

{% capture backupmodal %}
Because when you're syncing, if you delete something from your computer, it's also deleted from the remote copy. That's the **opposite** of a backup!
{% endcapture %}

{% include modal.html button="Really? Why not?" color="primary" title="Why is a sync not a backup?" text=backupmodal %}

You should run a backup tool *in addition* to the services above. Your best, most secure option is to backup both to a physical hard drive and to an online service.

{% capture backupoptions %}
 - **[Griffith Research Storage](https://research-storage.griffith.edu.au)**: built on the same technology as Cloudstor and is very fast. Research Vault is available for you to store data you are no longer actively using. Here is a [handy questionnaire](https://research-storage.griffith.edu.au/compare) to help you decide Griffith Research Storage can help you.

 - **[Arq Backup](www.arqbackup/com)**: use Arq to back your computer up to your Cloudstor or to your OneDrive. It's not free, but the $50 license is less than the cost of a hard drive and makes backing up completely automatic.

 - **[Backblaze](https://www.backblaze.com)**: popular, paid.

 - **[RSync](https://rsync.samba.org)**: RSync is a command-line tool for syncing local folders with an external hard drive or network drive.
{% endcapture %}
{% include card.html header="🛰 Online backup options" text=backupoptions %}

{% capture hdbackups %}
 - Time Machine (Mac)

 - Windows Backup (Windows 10)

 - Drag-and-drop (the worst option)

 {% capture timemachine %}
**Our recommendation: Your operating system**

The best backup is the one you will use. That means set-and-forget is best. Buy a simple external hard drive and leave it plugged in to your computer, or place a weekly calendar reminder to plug it in. Let the operating system do the rest. 
{% endcapture %}

{% include alert.html text=timemachine color="primary" %}

 {% endcapture %}

{% include card.html header="💽 Hard-drive backup options" text=hdbackups %}

{% capture why %}
Because (a) you will inevitably forget to do it at some point, and (b) each new copy replaces what was there before meaning you can't recover older versions of your work.
{% endcapture %}
{% include modal.html button="Why is drag-and-drop the worst way to back up?" color="primary" title="Why drag and drop is a bad idea" text=why %}
