# Pi-hole-custom-blocklist
Le but de ce projet est de bloquer tous les nom de domaines inutiles lorsque l'on navigue sur le web et qui n'existe que pour nous gacher la vie en hébérgeant des blocklist à importer sur vos fichier host ou sur votre dns.

blocklist prêt à être utilisé :
- [x] Adware-Malware
- [ ] Tracking & Telemetry
- [ ] Suspicious

## Blocklist

Host file source | Description | Home page | Raw hosts | Update frequency | License | Issues
-----------------|-------------|:---------:|:---------:|:----------------:|:-------:|:------:
Steven Black's ad-hoc list | Additional sketch domains as I come across them. |[link](https://github.com/StevenBlack/hosts/blob/master/data/StevenBlack/hosts) | [raw](https://raw.githubusercontent.com/StevenBlack/hosts/master/data/StevenBlack/hosts) | occasionally | MIT | [issues](https://github.com/StevenBlack/hosts/issues)
AdAway | AdAway is an open source ad blocker for Android using the hosts file. |[link](https://adaway.org/) | [raw](https://raw.githubusercontent.com/AdAway/adaway.github.io/master/hosts.txt) | frequently | CC BY 3.0 | [issues](https://github.com/AdAway/adaway.github.io/issues)
add.2o7Net | 2o7Net tracking sites based on [hostsfile.org](http://www.hostsfile.org/hosts.html) content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.2o7Net/hosts) | occasionally | MIT | [issues](https://github.com/FadeMind/hosts.extras/issues)
add.Dead | Dead sites based on [hostsfile.org](http://www.hostsfile.org/hosts.html) content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Dead/hosts) | occasionally | MIT | [issues](https://github.com/FadeMind/hosts.extras/issues)
add.Risk | Risk content sites based on [hostsfile.org](http://www.hostsfile.org/hosts.html) content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Risk/hosts) | occasionally | MIT | [issues](https://github.com/FadeMind/hosts.extras/issues)
add.Spam | Spam sites based on [hostsfile.org](http://www.hostsfile.org/hosts.html) content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Spam/hosts) | occasionally | MIT | [issues](https://github.com/FadeMind/hosts.extras/issues)
AdguardTeam cname trackers | CNAME-cloaked tracking abuses. |[link](https://github.com/AdguardTeam/cname-trackers) | [raw](https://raw.githubusercontent.com/AdguardTeam/cname-trackers/master/combined_disguised_trackers_justdomains.txt) | occasionally | MIT | [issues](https://github.com/AdguardTeam/cname-trackers/issues)
Mitchell Krog's - Badd Boyz Hosts | Sketchy domains and Bad Referrers from my Nginx and Apache Bad Bot and Spam Referrer Blockers |[link](https://github.com/mitchellkrogza/Badd-Boyz-Hosts) | [raw](https://raw.githubusercontent.com/mitchellkrogza/Badd-Boyz-Hosts/master/hosts) | weekly | MIT | [issues](https://github.com/mitchellkrogza/Badd-Boyz-Hosts/issues)
hostsVN | Hosts block ads of Vietnamese |[link](https://github.com/bigdargon/hostsVN) | [raw](https://raw.githubusercontent.com/bigdargon/hostsVN/master/option/hosts-VN) | occasionally | MIT | [issues](https://github.com/bigdargon/hostsVN/issues)
KADhosts | Fraud/adware/scam websites. |[link](https://kadantiscam.netlify.app/) | [raw](https://raw.githubusercontent.com/PolishFiltersTeam/KADhosts/master/KADhosts.txt) | frequently | CC BY-SA 4.0 | [issues](https://github.com/PolishFiltersTeam/KADhosts/issues)
MetaMask eth-phishing-detect | Phishing domains targeting Ethereum users. |[link](https://github.com/MetaMask/eth-phishing-detect) | [raw](https://raw.githubusercontent.com/MetaMask/eth-phishing-detect/master/src/hosts.txt) | frequent | DON'T BE A DICK PUBLIC LICENSE | [issues](https://github.com/MetaMask/eth-phishing-detect/issues)
minecraft-hosts | Minecraft related tracker hosts |[link](https://github.com/jamiemansfield/minecraft-hosts) | [raw](https://raw.githubusercontent.com/jamiemansfield/minecraft-hosts/master/lists/tracking.txt) | occasionally | CC0-1.0 | [issues](https://github.com/jamiemansfield/minecraft-hosts/issues)
MVPS hosts file | The purpose of this site is to provide the user with a high quality custom HOSTS file. |[link](https://winhelp2002.mvps.org/) | [raw](https://winhelp2002.mvps.org/hosts.txt) | monthly | CC BY-NC-SA 4.0 | [issues](mailto:winhelp2002@gmail.com)
osint.digitalside.it | DigitalSide Threat-Intel malware domains list. |[link](https://github.com/davidonzo/Threat-Intel) | [raw](https://raw.githubusercontent.com/davidonzo/Threat-Intel/master/lists/latestdomains.piHole.txt) | daily | MIT | [issues](https://github.com/davidonzo/Threat-Intel/issues)
shady-hosts | Analytics, ad, and activity monitoring hosts |[link](https://github.com/shreyasminocha/shady-hosts) | [raw](https://raw.githubusercontent.com/shreyasminocha/shady-hosts/main/hosts) | occasionally | CC0-1.0 | [issues](https://github.com/shreyasminocha/shady-hosts/issues)
Dan Pollock – [someonewhocares](https://someonewhocares.org/) | How to make the internet not suck (as much). |[link](https://someonewhocares.org/hosts/) | [raw](https://someonewhocares.org/hosts/zero/hosts) | frequently | non-commercial with attribution | [issues](mailto:hosts@someonewhocares.org)
Tiuxo hostlist - ads | Categorized hosts files for DNS based content blocking |[link](https://github.com/tiuxo/hosts) | [raw](https://raw.githubusercontent.com/tiuxo/hosts/master/ads) | occasional | CC BY 4.0 | [issues](https://github.com/tiuxo/hosts/issues)
UncheckyAds | Windows installers ads sources sites based on https://unchecky.com/ content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/UncheckyAds/hosts) | occasionally | MIT | [issues](https://github.com/FadeMind/hosts.extras/issues)
URLHaus | A project from [abuse.ch](https://abuse.ch/) with the goal of sharing malicious URLs. |[link](https://urlhaus.abuse.ch/) | [raw](https://urlhaus.abuse.ch/downloads/hostfile/) | weekly | CC0 | [issues](mailto:contactme@abuse.ch)
yoyo.org | Blocking with ad server and tracking server hostnames. |[link](https://pgl.yoyo.org/adservers/) | [raw](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&mimetype=plaintext&useip=0.0.0.0) | frequently |  | [issues](mailto:pgl@yoyo.org)

## Adware-Malware
Bloque les Adwares et Malwares

## Tracking & Telemetry
Bloque les tracking inutiles et les telemetry (windows, etc...)

## Suspicious
Bloque les sites reconnus comme dangereux ou qui possède des virus

## Contribuer
Vous pouvez contribuer au projet en ajoutant des noms de domaines à bloquer dans les blocklists correspondantes en ajoutant à la ligne "0.0.0.0 nomdudomaine" en format regex.
Les sous-domaines peuvent être bloqué individuellement.
