# \# Super Enceinte : Amplificateur TPA3110D2 \& Récepteur Bluetooth MH-M18

# 

# Conception complète (électronique et mécanique) d'une enceinte Bluetooth sédentaire avec un amplificateur de classe D et un traitement de signal analogique. 

# 

# !\[Photo de l'enceinte terminée](assets/spk\_img\_2.jpg)

# 

# > 📄 \*\*Rapport détaillé :\*\* \[Voir le rapport de conception PDF complet](docs/Enceinte.pdf)

# 

# \## 🛠 Caractéristiques techniques

# 

# \*   \*\*Amplification :\*\* Amplificateur TPA3110D2 de classe D (puissance de 2x15W bridée à 8W pour la protection des haut-parleurs).

# \*   \*\*Acoustique :\*\* Haut-parleurs issus d'une JBL Flip 3 (Impédance : 4 Ohms ; Puissance : 8 W).

# \*   \*\*Connectivité :\*\* Récepteur Bluetooth MH-M18 piloté par un réseau de résistances (diviseur de tension).

# \*   \*\*Alimentation :\*\* Alimentation continue secteur (12V DC) avec régulation Buck 5V dédiée au module Bluetooth pour l'isolation des parasites.

# 

# \## ⚡ Conception Électronique (KiCad)

# 

# Le circuit a été entièrement schématisé et routé sur \*\*KiCad 8.0\*\*. 

# 

# \*   \*\*PCB 4 couches :\*\* Utilisation de couches internes dédiées à l'alimentation (12V) et aux plans de masse (GND) pour garantir l'intégrité du signal audio et le blindage électromagnétique.

# \*   \*\*Paramétrages matériels :\*\* 

# &#x20;   \*   \*Limitation de puissance (PLIMIT)\* fixée à 2,19 V via pont diviseur.

# &#x20;   \*   \*Gain\* fixé à sa valeur minimale de 20 dB pour réduire le bruit de fond.

# &#x20;   \*   \*Filtrage LC de sortie\* (15µH / 2.2µF) avec fréquence de coupure à 27 kHz adapté sous 4 Ohms.

# \*   \*\*Gestion thermique :\*\* Dissipation thermique passive optimisée via des vias reliant le composant aux plans de masse.

# 

# !\[Capture du routage KiCad 4 couches](assets/Routage.png)

# 

# \## 📐 Conception Mécanique (SolidWorks)

# 

# Le volume de charge acoustique et l'intégration des composants électroniques ont été modélisés sous \*\*SolidWorks\*\*. 

# Le boîtier final intègre une façade texturée et un corps réalisé à partir d'un moule en béton, habillé d'une finition artistique personnalisée (collage et vernis).

# 

# !\[Rendu SolidWorks](assets/spk\_mod\_solidworks.png)

# 

# \## 📁 Structure du projet

# \*   `/hardware` : Fichiers sources KiCad (Schémas, Routage PCB, BOM).

# \*   `/mechanical` : Modèles 3D SolidWorks.

# \*   `/docs` : Documentation technique et rapport de conception.

