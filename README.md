# lists.d
### listings for known devices, device identifiers, public servers and more.
For a Table of Contents, checkout [INDEX.TSV](INDEX.TSV).

---
## [Currently Existing Lists]((./INDEX.tsv)):
- Software
  - [Download Links to popular Software and Distributions](./largefiles.downloads.links.list.tsv)
  - [Homebrew](./homebrew.list.tsv) Games and Software for Game Consoles
- Devices
  - [EID](./eid.devices.list.tsv) - eSIMs
  - [ICCID](./iccid.devices.list.tsv) - SIM Cards
  - [IMEI](./imei.devices.list.tsv) - WWAN Modems
  - [MAC](./mac.devices.list.tsv) - (W)LAN Devices
  - [USB Device IDs](./usb.devices.list.tsv) of known devices
  - [known default logins](./default.logins.list.tsv) for various systems
- Services [You'll need to register / sign-up for to use them!]
  - [Dialup Internet Access](./dialup.providers.list.tsv)
  - [IPTV Streams](./iptv.livestreams.list.tsv)
  - [ActivityPub Servers](./activitypub.servers.list.tsv)
  - [eMail](./email.servers.list.tsv)
  - [XMPP / Jabber](./xmpp.servers.list.tsv)
  - [Webhosting](free.webhosters.list.tsv)
  - [Filehosting](free.filehosters.list.tsv)
  - [Bona-fide Onion Services](./onion.domains.list.tsv)
- Public Servers [They are freely accessible without registration or signups!]
  - [DNS](./dns.servers.list.tsv)
  - [NTP](./ntp.servers.list.tsv)
  - [FTP](./ftp.servers.list.tsv)
  - [Search Engines](./searchpages.list.tsv)
  - [BitTorrent Trackers](./bittorent.trackers.list.tsv)
  - [IRC Networks](./irc.networks.list.tsv)
  - [Monero Nodes](./monero.nodes.list.tsv)
  - [Minecraft Gameservers](./minecraft.gameservers.list.tsv)
- [Blocklists](./blocklists.list.tsv)
  - Network Security
    - Don't Route or Peer
      - [lists.d IPv4 DROP](./drop.ipv4.block.list.tsv)
      - [lists.d IPv6 DROP](./drop.ipv6.block.list.tsv)
      - [lists.d ASN DROP](./drop.asn.block.list.tsv)
      - [lists.d Domains DROP](./drop.domains.block.list.tsv)
      - [lists.d IPv4 MIL/INTEL](./milintel.ipv4.block.list.tsv)
      - [lists.d Typosquatting Domains](./typos.domains.block.list.tsv)
  - Application-Specific
    - [Hostile ActivityPub Servers](./activitypub.domains.block.list.tsv)
    - [ActivityPub "AI Bots"](./activitypub.bots.block.list.tsv)
    - [ActivityPub Servers that federate with Facebook](./activitypub.threads.domains.block.list.tsv)
    - [eMail Spam Domains](./spammers.domains.block.list.tsv)
  - Platform-Specific
    - [Toxic GitHub Users](./users.github.block.list.tsv)
  - Optional Blocklists
    - [Gambling Domains](./gambling.domains.block.list.tsv)
    - ["AI Content"](./ai.content.domains.block.list.tsv)
      - Basically Garbage sites that only exist to commit Ad-Farming, Malware/Phishing and other scams like selling useless stuff noone needs or asks for...
  - Other Blocklists
    - [Spamcallers, Robocalls and Scammers' Phone numbers](spammers.phone.numbers.list.tsv)
    - ["do not report security issues to" list](./dontreport.security.list.tsv)  based off hostility towards responsible disclosures.
      - Organizations and Individuals that are known to litigate and attack those that report security issues to them.
        - aka. ["shooting the messenger"](https://en.wikipedia.org/wiki/Shooting_the_messenger)
- Lists of Lists
  - [INDEX of this repository](./INDEX.tsv)
  - [Bona-Fide Onion Services](./onion.domains.list.tsv)
  - [Network-wide Blocklists](./blocklists.list.tsv)
- Allowlists
  - [Allowed Domains](domains.allow.list.tsv)
  - [Verified Monero Donation Wallets](./donations.monero.wallets.list.tsv) for several Open Source Projects and Services.
- Other
  - [Credit Cards](creditcards.list.tsv) - for API testing only!
  - [public logins](./logins.list.tsv)
  - [Desktop Wallpapers](./desktop.wallpapers.list.tsv)
  - [known and verified Monero addresses](./donations.monero.wallets.list.tsv)
  - [known crawlers](./crawlers.lists.tsv)

---
## Important Notice:
#### All information here is provided as-is with no guarantee of accuracy or reliability, and is meant for bona-fide purposes only!
Lists are provided as [TSV files](https://en.wikipedia.org/wiki/Tab-separated_values) with [POSIX-compliant line endings](https://en.wikipedia.org/wiki/Newline#Representation) in order to make them easily searchable and interpretable for applications whilst retaining human readability and editability with text editors, scripts and spreadsheet programs, maximizing accessibility and compatibility at the same time.

## Privacy Notice:
### All info has been taken from publicly available sources, not from private data or leaks.
#### We will reject all pull requests with data that have been obtained from non-public data and without proper source deeplinking to verify that these are not attempts at d0xxing or other actions that are not only violating GibHub's ToS but also might have serious legal remifications attached to them!
###### Being listed is not an explicit endorsement of said services, sites and/or their maintainers. Tho we will take reports seriously and will act accordingly in case some will act against our values and common interests.
Knowledge is Free!

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

### Which License do you use?
- The entire repo is [licensed under CC-BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
  - You can find the [license here.](./LICENSE.md)
  - This means you can use it everywhere, but you cannot sell with or as part of a commercial product [i.e. network security appliance].
    - Customers / end-users may be made aware and provided step-by-step or automated tools to use and query it, but they should be made aware that this is a freely accessible list and not part of your commercial product and/or services.
      - You'll have to comply with the terms of the license.
    - Please feel free to inform us if you use our lists and/or contribute to them.

### Can I customize it?
- Yes, please do so.
  - If you don't want to contribute private data upsteam, please name those files with .private.list.tsv  as file extension as per [.gitignore](.gitignore) .
    - Otherwise we'd highly recommend to at least keep your fork synced and push corrections upstream to us in the form of a [pull request](https://github.com/greyhat-academy/lists.d/pulls)!

---
## Troubleshooting:
### My Domain / Site / IP-Adresses / ... are listed on a blocklist and I want them removed!
That's Great to Hear! 

To do so we still need you to [open up a new issue](https://github.com/greyhat-academy/lists.d/issues/new/choose) and provide us with some details:
1. The Entry in Question [Permalink to it!].
2. The [Issue](https://github.com/greyhat-academy/lists.d/issues?q=is%3Aissue) / [Pull Request](https://github.com/greyhat-academy/lists.d/pulls?q=is%3Apr+) it was submitted with.
3. Evidence of Ownership or Authorization by the Owner of said Domain / IP Adress Space / ASN / ... to act on their behalf.
   - This MUST be verifyable!
4. Proof that the reason for the listing has been removed / corrected.

###### Please allow us time for due diligence and processing of your request.
##### We will not accept other channels for submissions!
###
#### But, but I want it removed NOW!
Please be reminded that we operate on transparency, accountability and consequences and do think that doing the correct thing is better than doing things fast.
##### Whilst our decision may not be final forever, [as we do acknowledge that we ain't perfect](https://github.com/greyhat-academy/lists.d/issues/17), we will take action against spammers flooding our queue and [will publicly ban them](users.github.block.list.tsv).
We do not take threats kindly and advise anyone from attempting these, as we will publish any such attempts.

### Nothing in this section shall be deemed or construed as non-willingness to comply with any reasonable request.