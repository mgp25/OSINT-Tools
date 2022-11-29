# OSINT Tools
[![sponsor](https://img.shields.io/badge/-Become%20a%20sponsor%20❤-ff6964)](https://github.com/sponsors/mgp25)

# Index

- [**Social network resources and tools**](#social-network-resources-and-tools)
    - [**Github**](#github)
    - [**Google**](#google)
    - [**Youtube**](#youtube)
    - [**Twitter**](#twitter)
    - [**Skype**](#skype)
    - [**Protonmail**](#protonmail)
- [**Cloud Storage and File Sharing**](#cloud-storage-and-file-sharing)
    - [**Mediafire**](#mediafire)
- [**Geolocalization**](#geolocalization)
- [**Search engine services**](#search-engines-services)
- [**Other**](#other)
- [**Lists and documentation**](#lists-and-documentation)

## Social network resources and tools
### Github

- [Gitrecon](https://github.com/GONZOsint/gitrecon): OSINT tool to get information from a Github and Gitlab profile and find user's email addresses leaked on commits.
- [GitStalk](https://github.com/un1k0n/GitStalk): OSINT tool to get information from a Github and Gitlab profile.

### Google

- [Ghunt](https://github.com/mxrch/GHunt): GHunt is an OSINT tool to extract information from any Google Account using an email.
- [Epieos Gmail](https://tools.epieos.com/email.php): Get similar results as Ghunt but online! 

Once you have a Google ID you can use any of the following URLs to get more information about the account:

- Google Maps: `https://www.google.com/maps/contrib/<ID>`
- Google Photos: `https://get.google.com/albumarchive/<ID>`

### Youtube

Get info about a Youtube account:

`https://www.youtube.com/feeds/videos.xml?user=<username>`

Find Youtube accounts:

`site:youtube.com/channel intitle:"<fullname>"`

### Twitter

Check if an email is already registered in Twitter:

`https://api.twitter.com/i/users/email_available.json?email=<email>`

### Skype

- SkypeHunt: A python script to obtain user information using Skype Web API.

### Protonmail

`https://api.protonmail.ch/pks/lookup?op=index&search=<email>`

- [ProtOsint](https://github.com/pixelbubble/ProtOSINT)


## Cloud Storage and File Sharing

### Mediafire

- [PyrOsint](https://github.com/mgp25/PyrOsint): PyrOsint is a simple python script that uses Mediafire API to obtain the owner of a media file for OSINT purposes.

## Geolocalization

- [Shade Map](https://shademap.app/): The source of shade data for the planet. View shadows cast across a map of the Earth in real-time. See how shadows fall in specific locations, at specific dates/times.

## Search engines services

- [spyse](https://spyse.com/) - all in one recon service. scans the entire internet using OSINT and collects all the data in its own DB for instant access. Scanned info: ipv4 host, AS, DNS, sub/domains, whois/site info, ports/banners/protocols etc...
- [criminalip.io](https://www.criminalip.io/) - Criminal IP is a specialized Cyber Threat Intelligence (CTI) search engine that allows users to search for various security-related information such as malicious IP addresses, domains, banners, etc. It can be widely integrated.
- [Namechk.sh](https://github.com/HA71/Namechk): Osint tool based on namechk.com for checking usernames on more than 100 websites, forums and social networks.
- [shodan](https://shodan.io): Shodan is a search engine for Internet-connected devices.
- [phonebook.cz](https://phonebook.cz/): Get emails by domain search.
- [Spytox](https://www.spytox.com/email-search): Email search
- [shodan.io](https://shodan.io)
- [wigle.net](https://wigle.net)
- [grep.app](https://grep.app)
- [app.binaryedge.io](https://app.binaryedge.io)
- [onyphe.io](https://onyphe.io)
- [viz.greynoise.io](https://viz.greynoise.io)
- [censys.io](https://censys.io)
- [hunter.io](https://hunter.io)
- [fofa.so](https://fofa.so)
- [zoomeye.org](https://zoomeye.org)
- [leakix.net](https://leakix.net)
- [intelx.io](https://intelx.io)
- [app.netlas.io](https://app.netlas.io)
- [searchcode.com](https://searchcode.com)
- [urlscan.io](https://urlscan.io)
- [publicwww.com](https://publicwww.com)

### Other

- [DataSploit](https://github.com/DataSploit/datasploit): An OSINT Framework to perform various recon techniques on Companies, People, Phone Number, Bitcoin Addresses, etc., aggregate all the raw data, and give data in multiple formats.
- [OSINT Framework](https://github.com/lockfale/OSINT-Framework):OSINT framework focused on gathering information from free tools or resources.
- exiftool
- dirb
- nmap

## Lists and documentation
- [awesome-osint](https://github.com/jivoi/awesome-osint): A curated list of amazingly awesome OSINT.
- [IntellTechniques](https://inteltechniques.com/menu.html): IntelTechniques Search Tool