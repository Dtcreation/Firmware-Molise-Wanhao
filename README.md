# Molise Firmware 

N'hésitez pas à me soutenir. Payez moi une 🍺 ou un ☕ : [https://paypal.me/dtouton](https://paypal.me/dtouton)

Ma chaine Youtube : [Dtcreation 3D](https://www.youtube.com/channel/UCQOsiY8l6Of56zkFhtDT0Sw)

Rejoignez notre groupe facebook : [Molise Firmware](https://www.facebook.com/groups/molisefirmware)

## FRENCH - ENGLISH DOWN

### Qu'est ce que le firmware Molise

Molise est un firmware modifié pour les imprimantes de la marque [Wanhao](https://www.wanhaofrance.com/). Le firmware support atuellement la D12/230 et la D12/300.

### Version actuelle

Dernière version de Molise __1.4.0__ basée sur [Marlin BugFix 2.0.x](https://github.com/MarlinFirmware/Marlin/tree/bugfix-2.0.x)

### A propos du Firmware Molise

Voici un listing de ce que propose actuellement le Firmware : 

Le Firmware supporte actuellement le hardware suivant : 

- Drivers A4988, TMC 2100, 2208 ou 2209 et LV8729
- Carte mère MKS Robin Nano V1.2
- Extruder BMG, Hemera et Matrix
- BlTouch
- Mono et Dual Color
- TFT mode Marlin ou Graphique

Le Firmware apporte les modifications suivantes à Marlin (par rapport à la version stock)

- Support du BlTouch
- Le M600 : permet de changer de couleur en cours de print (Compatible avec la carte SD, et Ocotprint)
- Mesh Bed Leveling : MBL - Permet de palper manuellement plusieurs points de votre plateau comme un BLTouch le ferait automatiquement
- Babystepping
- PID auto tune
- Level Corner with Probe
- M73
- ABL
- Z Offset Auto
- Chargement-Déchargement de filament assisté
- ...

Le code du fichier `Configuration.h` a été découpé en 7 sections afin de rendre le code plus lisible. Ainsi, pour les personnes souhaitant compiler le code à partir des sources, le travail sera plus simple. Pour plus d'explication sur la compilation du code, merci de vous reporter à la page du [wiki dédiée](https://github.com/Dtcreation/Firmware-Molise-Wanhao/wiki)

Le firmware Molise 1.4 vous est fourni gratuitement, dans un état « tel quel ». Nous ne pouvons pas être tenus responsables des dommages qu’il pourrait faire à votre imprimante 3D le cas échéant. S’il vous plaît procéder avec prudence.

Pour vous faciliter la tâche, le firmware molise vous est fourni "pré-compilé" pour les 4 cas de figures suivants:

- D12/230 Stock + MBL (Z driver A4988)
- D12/230 Stock + MBL (Z driver TMC2209)
- D12/230 Stock + BLTouch (Z driver A4988)
- D12/230 Stock + BLTouch (Z driver TMC2209)

Si vous l'aimez ou si vous souhaitez contribuer à d'autres améliorations de ce firmware, veuillez envisager la possibilité de faire un don à :

https://paypal.me/dtouton

Merci !

### Installation et configuration

Afin de vous aider dans l'installation et la configuration du Firmware, merci de faire un tour sur le [Wiki](https://github.com/Dtcreation/Firmware-Molise-Wanhao/wiki)

PROCÉDURES DE MISE À JOUR DE MARLIN FW:

Copiez les fichiers sur la carte SD, insérez la carte dans l'imprimante éteinte, allumez l'imprimante et attendez qu'elle ait fini !!
### Changelog

#### 1.4.0

- First Release

# Remerciement

Le firmware Molise 1.2 vous est fourni par David TOUTON, [la géniale communauté d’impression 3D sur Facebook](https://www.facebook.com/groups/molisefirmware), et bien sûr, nous ne pouvons pas oublier l’équipe Marlin qui a passé d’innombrables jours, nuits et années à construire Marlin jusqu’où il est aujourd’hui.



## ENGLISH

# Molise Firmware
