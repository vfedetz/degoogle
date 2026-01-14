# List of Privacy Focused Software I Use

Having control over your data and digital privacy is increasingly important in today's world. Consumer data privacy rights are basically non-existant in the United States, and closed-source commercial software is [enshittifying](https://en.wikipedia.org/wiki/Enshittification) at an alarming rate. In a hostile anti-consumer environment such as this, the only logical option is focusing on self hosted and community-driven open source software projects as much as you can.

My goal was to be more intentional with the software I chose to trust with my data and rely on daily. I have slowly replaced as much of the closed-source commercial software as I can with open-source, privacy-focused alternatives.

[Privacy Guides](https://www.privacyguides.org/) is an excellent resource for finding privacy-focused software alternatives which I referenced heavily when exploring software options. Please treat this list as a supplementary guide, showcasing what I ultimately chose for my own journey towards digital independance.

| <span style="color: rgb(45, 194, 107);">Function</span> | <span style="color: rgb(45, 194, 107);">App</span> | <span style="color: rgb(45, 194, 107);">Open Source?</span> | <span style="color: rgb(45, 194, 107);">Notes</span> |
| --- | --- | --- | --- |
| Mobile OS | GrapheneOS | yes |     |
| Launcher | Lawnchair 2 | yes |     |
| Desktop OS | Linux Mint | yes |     |
| Maps | CoMaps | yes | Alt: Magic Earth (not open source) Alt: Organic Maps (shady devs) |
| Business Search | GMapsWV | yes | WebView wrapper for accessing the web version of Google Maps. <br />Search destination and import into CoMaps for navigation. |
| YouTube | Grayjay | yes | Supports sponsor block and dislike. Does not support dearrow. Alt: LibreTube (Mobile) Alt: FreeTube (Desktop) Alt: Revanced |
| Secure Messaging | Signal | yes |     |
| SMS | QUIK | yes |     |
| App Store | GrapheneOS App Store > <br />Accescent > <br />Obtainium > <br />Aurora Store | yes | Listed in order of preference. Obtainium can pull F Droid releases. |
| Email Server | Fastmail.com | no  |     |
| Email Client (Mobile) | Thunderbird | yes |     |
| Email Client (Desktop) | Thunderbird | yes |     |
| Email Aliasing | Addy.io | yes |     |
| Email Domain | Cloudflare | N/A | purchased @surname.com |
| Search | SearXNG | yes | selfhosted search aggregator placed behind VPN proxy to hide IP |
| DNS | LAN: AdGuard Home <br />Mobile: Tailscale Exit Node | yes | AGH forwards to Unbound recursive resolver |
| Tasks | CalDAV Server: radicale <br />Mobile: Tasks.org/Davx5 <br />Desktop: Thunderbird | yes |     |
| Translate | DeepL | yes |     |
| Calendar | CalDAV Server: Radicale <br />Mobile: Fossify Calendar/Davx5 <br />Desktop: Thunderbird | yes |     |
| Contacts | CalDAV Server: Radicale <br />Mobile: Fossify Contacts/Davx5 <br />Desktop: Thunderbird | yes |     |
| Notes | Joplin | yes |     |
| Browser | Mobile: Vanadium <br />Desktop: Librewolf | yes |     |
| Photo Storage/Backup | Immich | yes |     |
| Mobile Keyboard | FUTO Keyboard | yes |     |
| Music Player | Findroid | yes | doesn't have auto transcode when roaming, no smart playlist downloading |
| Push Notifications | Gotify | yes |     |
| Password Manager | Vaultwarden | yes |     |
| Authenticator | Bitwarden Authenticator/Aegis | yes | Aegis holds TOTP for Bitwarden itself and email account to avoid circular dependency |
| Location Tracking | OwnTracks | yes | publishes to self hosted MQTT server
| File Manager | Material Files | yes |     |
| Gallery | Aves Gallery Libre | yes |     |
| Smart Home | Home Assistant | yes |     |
| Weather | Breezy Weather | yes |     |
| Location Tracking | OwnTracks | yes |     |
| Chromecast | Fcast | yes |     |
| Media Server | Jellyfin | yes |  |
