# FCSC 2026 Adresses du noyau - Un peu d'aléa

Vous recevez des captures de la mémoire vive sur trois machines, et vous cherchez l’adresse de la première instruction du noyau (fonction _stext) pour chacune d’entre elles.

Le flag est au format `FCSC{phys-virt}` où :

- `phys` est l’adresse physique de la première instruction du noyau,
- `virt` est l’adresse virtuelle de la première instruction du noyau dans la zone kernel text mapping.

Les adresses sont toutes sur 64 bits, au format hexadécimal avec préfixe 0x.

Par exemple : `FCSC{0x0123456789abcdef-0xfedcba9876543210}`

*Note : Lors du FCSC, le nombre d’essais était limité à 10 pour cette épreuve.*

Auteur : kernx

Origine : [Adresses du noyau - Un peu d'aléa](https://hackropole.fr/fr/challenges/forensics/fcsc2026-forensics-kaslr-2/)


## Challenge
[files/random.mem.xz](files/random.mem.xz)

-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2026-forensics-kaslr-2.git

> cd fcsc2026-forensics-kaslr-2


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/forensics/fcsc2026-forensics-kaslr-2/
