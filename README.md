# Pi-hole-custom-blocklist
Le but de ce projet est de bloquer tous les nom de domaines inutiles lorsque l'on navigue sur le web et qui n'existe que pour nous gacher la vie en hébérgeant des blocklist à importer sur vos fichier host ou sur votre dns.

blocklist prêt à être utilisé :
- [x] Adware-Malware
- [ ] Tracking & Telemetry
- [ ] Suspicious

## Blocklist

Host file source | Description | Raw hosts |
-----------------|-------------|:---------:|
Adware-Malware | Bloque les adwares et malwares |[raw](https://raw.githubusercontent.com/RAYTEKO/Pi-hole-custom-blocklist/main/adware-malware) | 
AdAway | AdAway is an open source ad blocker for Android using the hosts file. |[link](https://adaway.org/) | [raw](https://raw.githubusercontent.com/AdAway/adaway.github.io/master/hosts.txt) | frequently | CC BY 3.0 | [issues](https://github.com/AdAway/adaway.github.io/issues)
add.2o7Net | 2o7Net tracking sites based on [hostsfile.org](http://www.hostsfile.org/hosts.html) content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.2o7Net/hosts) | occasionally | MIT | [issues](https://github.com/FadeMind/hosts.extras/issues)

## Adware-Malware
Bloque les Adwares et Malwares

## Tracking & Telemetry
Bloque les tracking inutiles et les telemetry (windows, etc...)

## Suspicious
Bloque les sites reconnus comme dangereux ou qui possède des virus

## Contribuer
Vous pouvez contribuer au projet en ajoutant des noms de domaines à bloquer dans les blocklists correspondantes en ajoutant à la ligne "0.0.0.0 nomdudomaine" en format regex.
Les sous-domaines peuvent être bloqué individuellement.
