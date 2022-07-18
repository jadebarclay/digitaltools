---
section_id: Discovery
nav_order: 4
title: Capture
topics: Document scanners
description: >
    Optical scanners and OCR (optical character recognition) have come a long way. You can get just as good quality results from a smartphone app as from most flatbed scanners.
# youtubeid: moJgWrD6dwg
---

{% capture scanners %}

The following apps all scan photos, documents and whiteboards, automatically straighten and crop the image and optionally read the text. They can all create multi-page PDFs. This is incredibly helpful if you are dealing with physical manuscripts or other written material.


- **[Genius Scan](https://thegrizzlylabs.com/)** ([Android](https://play.google.com/store/apps/details?id=com.thegrizzlylabs.geniusscan.free) and [iOS](https://apps.apple.com/us/app/genius-scan-pdf-scanner/id377672876)): Scans multi-page documents as PDFs. High resolution, low file size, save and email direclty from the app. An excellent free option for all devices.

- **Adobe Scan** ([Android](https://play.google.com/store/apps/details?id=com.adobe.scan.android&hl=en_US) and [iOS](https://apps.apple.com/us/app/id1199564834)): Scans documents and saves them as PDFs to Adobe Document Cloud. Requires a Creative Cloud subscription to save PDFs. 

- **Microsoft Lens** ([Android](https://play.google.com/store/apps/details?id=com.microsoft.office.officelens&hl=en_AU&gl=US) and [iOS](https://apps.apple.com/au/app/microsoft-office-lens-pdf-scan/id975925059)): Microsoft's scanner tool. Also scans documents and saves as images or PDF. Can annotate scans with text. Requires Microsoft 365 subscription to save to OneDrive. 

- **SwiftScan** ([Android](https://play.google.com/store/apps/details?id=net.doo.snap&hl=en_AU&gl=US) and [iOS](https://apps.apple.com/us/app/swiftscan-document-scanner/id834854351)): Connects with several cloud services. Requires monthly subscription. 

- **Apple Notes**: The Notes app on iPhone scans multi-page documents as PDFs. An excellent free option if you have an iPhone.

{% capture bestscanner %}
**Our recommendation: Genius Scan**

Adobe Scan is more polished and has more features, great if you have a Creative Cloud subscription. Microsoft Lens has annotation features, great is you have OneDrive connected to your phone/device. Genius Scan is a reliable intuive scanning app (even my mum uses it) that doesn't require any cloud storage subscription.

{% endcapture %}

{% include alert.html text=bestscanner color="primary" %}

{% endcapture %}
{% include card.html header="<i class='fas fa-file-pdf'></i> PDF and document scanners" text=scanners %}