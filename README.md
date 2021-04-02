# Molise Firmware

## FRENCH - ENGLISH DOWN

N'hésitez pas à me soutenir. Payez moi une 🍺 ou un ☕ : [https://paypal.me/dtouton](https://bit.ly/3bXz1Bp)

Ma chaine Youtube : [Dtcreation 3D](https://bit.ly/3bXUTwr)

Ma page Instagram : [Dtcreation 3D](https://www.instagram.com/dtcreation3d/)

Mon Twitter : [Dtcreation 3D](https://twitter.com/Dtcreation3)

Rejoignez notre groupe facebook : [Molise Firmware](https://bit.ly/2P9pVZy)

Pour télécharger les supports à imprimer pour BLTouch ou TouchMi : [Thingiverse](https://bit.ly/3rF2LaX)

Merci à [hotends.fr](https://bit.ly/3r2AuLa) pour les supports du TouchMi
### Qu'est ce que le firmware Molise

Molise est un firmware modifié "universel" pour les imprimantes de la marque [Wanhao](https://www.wanhaofrance.com/). Le firmware support atuellement la D12/230 et la D12/300.

### Version actuelle

Dernière version de Molise __1.4.0__ basée sur [Marlin BugFix 2.0.x](https://github.com/MarlinFirmware/Marlin/tree/bugfix-2.0.x)

### A propos du Firmware Molise

Avec la version "Mode Marlin", on perd la prévisualisation de Gcode et le Wifi.

Si vous voullez ces fonctions, il vous faut décommenter //#define GRAPHIC_MODE dans la section 6 pour retrouver le mode graphique plus "standard"

Pour installer votre BLTouch ou TouchMI, connectez les fils noir et blanc sur le Z- pour le BLTouch et les 3 fils sur le Z- pour le TouchMi

Voici un listing de ce que propose actuellement le Firmware : 

Le Firmware supporte actuellement le hardware suivant : 

- Drivers A4988, TMC 2100, 2208 ou 2209 et LV8729
- Carte mère MKS Robin Nano V1.2
- Extruder BMG, Hemera et Matrix
- BlTouch
- TouchMi
- Mono et Dual Color
- TFT mode Marlin ou Graphique

Le Firmware apporte les modifications suivantes à Marlin (par rapport à la version stock)

- Support du BlTouch
- Support du TouchMi
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

Le code du fichier `Configuration.h` a été découpé en 7 sections afin de rendre le code plus lisible. Ainsi, pour les personnes souhaitant choisir leur configuration et compiler le code à partir des sources, le travail sera plus simple. Pour plus d'explication sur la compilation du code, merci de vous reporter à la page du [wiki dédiée](https://github.com/Dtcreation/Firmware-Molise-Wanhao/wiki)

Le firmware Molise 1.4 vous est fourni gratuitement, dans un état « tel quel ». Nous ne pouvons pas être tenus responsables des dommages qu’il pourrait faire à votre imprimante 3D le cas échéant. S’il vous plaît procéder avec prudence.

Pour vous faciliter la tâche, le firmware molise vous est fourni "pré-compilé" pour les 3 cas de figures suivants:

- D12/230 Stock + MBL (Z driver A4988) Mono et Dual
- D12/230 Stock + BLTouch (Z driver A4988) Mono et Dual
- D12/230 Stock + TouchMi (Z driver A4988) Mono et Dual

Si vous l'aimez ou si vous souhaitez contribuer à d'autres améliorations de ce firmware, veuillez envisager la possibilité de faire un don à :

https://paypal.me/dtouton

Merci !

### Installation et configuration

Afin de vous aider dans l'installation et la configuration du Firmware, merci de faire un tour sur le [Wiki](https://github.com/Dtcreation/Firmware-Molise-Wanhao/wiki)

PROCÉDURES DE MISE À JOUR DE MARLIN FW:

Copiez le fichier "Robin_nano35.bin" sur la carte SD, insérez la carte dans l'imprimante éteinte, allumez l'imprimante et attendez qu'elle ait fini !!
### Changelog

#### 1.4.0

- First Release

# Remerciement

Le firmware Molise 1.4 vous est fourni par David TOUTON, [la géniale communauté d’impression 3D sur Facebook](https://www.facebook.com/groups/molisefirmware), et bien sûr, nous ne pouvons pas oublier l’équipe Marlin qui a passé d’innombrables jours, nuits et années à construire Marlin jusqu’où il est aujourd’hui.



## ENGLISH

# Molise Firmware

Please do not hesitate to support me. Pay me a 🍺 or a ☕: [https://paypal.me/dtouton](https://bit.ly/3bXz1Bp)

My Youtube channel: [Dtcreation 3D](https://bit.ly/3bXUTwr)

My Instagram page: [Dtcreation 3D](https://www.instagram.com/dtcreation3d/)

My Twitter: [Dtcreation 3D](https://twitter.com/Dtcreation3)

Join our facebook group: [Molise Firmware](https://bit.ly/2P9pVZy)

To download the printable media for BLTouch or TouchMi: [Thingiverse](https://bit.ly/3rF2LaX)

Thanks to [hotends.fr](https://bit.ly/3r2AuLa) for the TouchMi support
### What is Molise firmware

Molise is a "universal" modified firmware for [Wanhao](https://www.wanhaofrance.com/) brand printers. The firmware also supports the D12 / 230 and the D12 / 300.

### Current version

Latest version of Molise __1.4.0__ based on [Marlin BugFix 2.0.x](https://github.com/MarlinFirmware/Marlin/tree/bugfix-2.0.x)

### About Molise Firmware

With the "Marlin Mode" version, you lose the preview of Gcode and the Wifi.

If you want these functions, you have to uncomment // #define GRAPHIC_MODE in section 6 to return to the more "standard" graphic mode

To install your BLTouch or TouchMI, connect the black and white wires on the Z- for the BLTouch and the 3 wires on the Z- for the TouchMi

Here is a listing of what the Firmware currently offers:

Firmware currently supports the following hardware:

- Drivers A4988, TMC 2100, 2208 or 2209 and LV8729
- MKS Robin Nano V1.2 motherboard
- Extrude BMG, Hemera and Matrix
- BlTouch
- TouchMi
- Mono and Dual Color
- TFT Marlin or Graphic mode

The Firmware makes the following changes to Marlin (compared to the stock version)

- BlTouch support
- TouchMi support
- The M600: allows you to change color during printing (Compatible with SD card, and Ocotprint)
- Mesh Bed Leveling: MBL - Allows you to manually palpate several points of your board as a BLTouch would do it automatically
- Babystepping
- PID auto tune
- Level Corner with Probe
- M73
- ABL
- Z Offset Auto
- Assisted filament loading-unloading
- ...

The code of the `Configuration.h` file has been split into 7 sections to make the code more readable. So, for people who want to choose their configuration and compile the code from source, the job will be easier. For more explanation on how to compile the code, please refer to the [dedicated wiki page](https://github.com/Dtcreation/Firmware-Molise-Wanhao/wiki)

Molise 1.4 firmware is provided to you free of charge, in an "as is" state. We cannot be held responsible for any damage it may do to your 3D printer if it occurs. Please proceed with caution.

To make your task easier, the molise firmware is supplied to you "pre-compiled" for the following 3 scenarios:

- D12/230 Stock + MBL (Z driver A4988) Mono and Dual
- D12/230 Stock + BLTouch (Z driver A4988) Mono and Dual
- D12/230 Stock + TouchMi (Z driver A4988) Mono and Dual

If you like it or would like to contribute to other improvements of this firmware, please consider the possibility of donating to:

https://paypal.me/dtouton

Thank you !

### Installation and configuration

In order to help you in the installation and configuration of the Firmware, please take a look at the [Wiki](https://github.com/Dtcreation/Firmware-Molise-Wanhao/wiki)

MARLIN FW UPDATE PROCEDURES:

Copy the file "Robin_nano35.bin" to the SD card, insert the card into the turned off printer, turn on the printer and wait for it to finish !!
### Changelog

#### 1.4.0

- First Release

# Thanks

Molise 1.4 firmware is provided to you by David TOUTON, [the awesome 3D printing community on Facebook](https://www.facebook.com/groups/molisefirmware), and of course we can't forget the team Marlin who spent countless days, nights and years building Marlin to where it is today.
