# Pi-hole-custom-blocklist
Le but de ce projet est de bloquer tous les nom de domaines inutiles lorsque l'on navigue sur le web et qui n'existe que pour nous gacher la vie en hébérgeant des blocklist à importer sur vos fichier host ou sur votre dns.

blocklist prêt à être utilisé :
- [x] Adware-Malware
- [ ] Tracking & Telemetry
- [ ] Suspicious

## Adware-Malware
Bloque les Adwares et Malwares

## Tracking & Telemetry
Bloque les tracking inutiles et les telemetry (windows, etc...)

## Suspicious
Bloque les sites reconnus comme dangereux ou qui possède des virus

## Contribuer
Vous pouvez contribuer au projet en ajoutant des noms de domaines à bloquer dans les blocklists correspondantes en ajoutant à la ligne "0.0.0.0 nomdudomaine" en format regex.
Les sous-domaines peuvent être bloqué individuellement.
