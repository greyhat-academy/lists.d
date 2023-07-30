# lists.d
### listings for known devices, device identifiers, public servers and more.

---

#### These identifiers are device data are provided as-is with no guarantee of accuracy or reliability, and are meant for ITsec-related education & training purposes only!

Lists are provided as [TSV files](https://en.wikipedia.org/wiki/Tab-separated_values) with [POSIX-compliant line endings](https://en.wikipedia.org/wiki/Newline#Representation) in order to make them easily searchable and interpretable for applications whilst retaining human readability and editability with text editors, scripts and spreadsheet programs.

## INPORTANT NOTICE:
### All info has been taken from publicly available sources, not from private data or leaks.
#### We will reject all pull requests with data that have been obtained from non-public data and without proper source deeplinking to verify that these are not attempts at d0xxing or other actions that are not only violating GibHub's ToS but also might have serious legal remifications attached to them!
###### Being listed is not an explicit endoresement of said services, sites and/or their maintainers. Tho we will take reports seriously and will act accordingly in case some will act against our values and common interests.
Knowledge is Free!

---
## Currently Existing Lists:
- Devices
  - [IMEI](./imei.devices.list.tsv)
  - [MAC](./mac.devices.list.tsv)
  - [default logins](./default.logins.list.tsv) - for various devices and systems
- Services
  - [Dialup Internet Access](./dialup.providers.list.tsv)
- Public Servers
  - [DNS](./dns.servers.list.tsv)
  - [NTP](./ntp.servers.list.tsv)
  - [eMail](./email.servers.list.tsv)
  - [XMPP / Jabber](./xmpp.servers.list.tsv)
  - [IRC Networks](./irc.networks.list.tsv) 
  - [BitTorrent Trackers](./bittorent.trackers.list.tsv)
  - [Bona-fide Onion Services](./onion.domains.list.tsv)
  - [ActivityPub Servers](./activitypub.servers.list.tsv)
  - [Minecraft](./minecraft.gameservers.list.tsv)
- [Blocklists](./blocklists.list.tsv)
  - Network Security
    - Don't Route or Peer
      - [lists.d IPv4 DROP](./drop.ipv4.block.list.tsv)
      - [lists.d IPv6 DROP](./drop.ipv6.block.list.tsv)
      - [lists.d ASN DROP](./drop.asn.block.list.tsv)
      - [lists.d Domains DROP](./drop.domains.block.list.tsv)
      - [lists.d IPv4 MIL/INTEL](./milintel.ipv4.block.list.tsv)
  - Application-Specific
    - [Hostile ActivityPub Servers](./activitypub.domains.block.list.tsv)
    - [Spammer Domains](./spammers.domains.block.list.tsv)
  - Platform-Specific
    - [Toxic GitHub Users](./users.github.block.list.tsv)
  - Optional Blocklists
    - [Gambling Domains](./gambling.domains.block.list.tsv)
- Lists of Lists
  - [Bona-Fide Onion Services](./onionlists.list.tsv)
  - [Network-wide Blocklists](./blocklists.list.tsv)
- Other
  - ["do not report security issues to" list](./dontreport.security.list.tsv)  based off hostility towards responsible disclosures.
    - Organizations and Individuals that are known to litigate and attack those that report security issues to them.
      - aka. ["shooting the messenger"](https://en.wikipedia.org/wiki/Shooting_the_messenger)
  - [public logins](./logins.list.tsv)

---

## FAQ

### Where can I get the latest version?
If you need the latest main branch, you can just [download it here directly from GitHub](https://github.com/greyhat-academy/lists.d/archive/refs/heads/main.zip).
- You can also find [the latest "release" here](https://github.com/greyhat-academy/lists.d/releases/latest).
Either way, simply unpack and you should get the TSV files which you can then edit with your favorite editor, spreadsheet tool or IDE and parse in your scripts.

### Why make this repo?
There are various reasons why I started this:
- I needed a convenient way to version, update and manage essential configurations like DNS- & NTP-Servers as well as being able to just simply fetch and apply them when setting up systems, or at the very least just pull the latest version in a script.
- I don't want to constantly copy & paste any current recommendation but have a fixed link to said repo for use on projects and recommendation.
- Others might benefit from sharing said data and being able to contribute too.
  - Please feel free to [open up an issue](https://github.com/greyhat-academy/lists.d/issues) if you have any suggestions, like adding your own data to it
    - Don't forget to provide source links!

### Why use it?
- It just works!
  - Due to using TSV files you can simply pull said lists and query them with any tool that can handle plaintext.
    - [from pfBlockerNG](https://twitter.com/k3vk4/status/1564055009762967555) and a lot of CLI / TUI tools and scrips to even GUI-based spreadsheet programs like LibreOffice Calc...
- Because it's well-maintained and documented.
  - Suggestions and Reports of Issues are welcome.
- It's increasing adoption already works.
  - See [#DropKiwifarms](https://twitter.com/k3vk4/status/1562956359686971392)
- It's being used by several companies internally.
  - Due to NDAs we can't list them here, unfortunately.
    - But it's part of the toolkit of many people - both contributors and non-contributors.

### Why contribute to it?
- We're open and welcoming towards contributions.
  - OFC, behave yourself! We'll not tolerate spamming, harrasment and cybervandalism in our repo and will take foreseeable consequences within the appropriate channels to act against such misbehaviour!

### I'm having issues with a certain list, help!
- If you're certain your issue is caused by said list, please [open up an issue here](https://github.com/greyhat-academy/lists.d/issues) and provide as much detail as possible.
  - We're quick to react and remediate issues if caused by us
    - see [this example](https://github.com/greyhat-academy/lists.d/issues/17)

### Which License do you use?
- The entire repo is [licensed under CC-BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
  - You can find the [license here.](./LICENSE.md)
  - This means you can use it everywhere, but you cannot sell with or as part of a commercial product [i.e. network security appliance].
      - Customers / end-users may be made aware and provided step-by-step or automated tools to use and query it, but they should be made aware that this is a freely accessible list and not part of your commercial product and/or services.
        - You'll have to comply with the terms of the license.
      - Please feel free to inform us if you use our lists and/or contribute to them.
