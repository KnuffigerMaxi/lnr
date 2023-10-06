### lnr

Configs und Backups der verschiedenen Streams und doodles dazwischen

### zu beachten

Alle Configs hier enthalten meine public-keys vom Host
bitte in der eigenen Testumgebung eigene keys verwenden!

Alle ansible Playbooks enthalten u.U. auch meinen user bzw. keys
-> bitte ebenfalls anpassen

### grundsätzliches zum Setup

ansible läuft bei mir auf dem Proxmox-Host
Dieser hat noch ein vmbr1001 auf dem die Management-IPs
der vyos-VMs erreichbar sind.

In diesem vmbr1001 gibt es kein Gateway, auch die vyos-VMs haben
einfach nur eine IP dort drin.

Das ist eine Krücke und wird im realen Leben anders gemacht,
hier ist es einfach nur der Einfachheit so damit man sich nicht
Huhn-Ei-Problemen aufhalten muss und die initiale Config schneller geht.

