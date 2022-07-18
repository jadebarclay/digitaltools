---
section: Preparation
nav_order: 2
title: Security 
topics: Password managers; Passkeys
description: >
    Just like backups, the best security protocol is the one you will use. 
# youtubeid: moJgWrD6dwg
---

## Security

{% capture passphrase %}
The best way to keep your passwords *different and secure* is to use a password manager. ⭐️ The best *password* to use is a *passphrase*.
{% include figure.html img="password_strength.png" alt="Comic explaining why passphrases are superior to complex passwords" caption="This comic by XKCD (https://xkcd.com/936/) explains it best. Published under a CC-BY-NC 2.5 License." width="100" %}
{% endcapture %}
{% include alert.html text=passphrase color="info" %}

{% capture pwmanagers %}

Getting used to using a password manager is a great investment in your overall experience of using the Internet. Most password managers have browser plugins that can fill login forms automatically. 

 - **[LastPass](https://www.griffith.edu.au/passwords/lastpass)**: Griffith's supported password manager. It is available to all staff. 

 - **[Bitwarden](www.bitwarden.com)**: free and open source, multiplatform, simple to use. Very modern and well-regarded.

 - **[1Password](https://1password.com)**: high quality commercial (paid) option. It's been around along time and has a good reputation.

 - **[Dashlane](https://www.dashlane.com)**

{% capture pwrecommended %}
**Our recommendation: Bitwarden**

Although LastPass is a partner of Griffith and is offered free to staff, the app is not as seamless as Bitwarden, and your license will not come with you if you leave Griffith. For that reason, we recommend going with Bitwarden. 
{% endcapture %}
{% include alert.html text=pwrecommended color="primary" %}

{% endcapture %}
{% include card.html header="<i class='fas fa-key'></i> Password managers" text=pwmanagers %}

{% capture browser %}
You could, but you would be missing out on a few of the key benefits of password managers, like checking that your passwords aren't being reused across services, generating new passwords for you and syncing your passwords across mobile and desktop devices.
{% endcapture %}
{% include modal.html button="Why can't I just let my browser remember my passwords?" color="info" title="Why not save in a browser" text=browser %}

