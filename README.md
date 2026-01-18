# Projet Réseau (AITAOUICHA YASSINE) : Architecture Réseau de l’EUROMED UNIVERSITY OF FES (EMUF)

# Objectif du Projet
Ce projet a pour objectif de concevoir et de simuler l’architecture réseau complète de l’**EUROMED UNIVERSITY OF FES (UEMF)** en utilisant **Cisco Packet Tracer**.  
L’architecture proposée vise à assurer une **connectivité fiable**, une **bonne segmentation du réseau**, une **haute disponibilité** et une **facilité de gestion**, tout en respectant les standards des architectures réseaux modernes.

Le campus est composé de **6 bâtiments**, chacun comprenant **4 étages**.  
Le **premier bâtiment** est dédié aux services **administratifs et pédagogiques**, tandis que les autres bâtiments hébergent les salles de cours, laboratoires et services académiques.

Le réseau est conçu selon une **architecture 3-tiers** :
- Couche **Accès**
- Couche **Distribution**
- Couche **Cœur**

Chaque bâtiment dispose de sa propre couche d’accès et de distribution, toutes reliées à une **couche cœur centralisée**.

---

# Description Générale de l’Architecture

- **Nombre de bâtiments** : 6  
- **Nombre d’étages par bâtiment** : 4  
- **Architecture réseau** : Architecture hiérarchique 3-tiers  
- **Environnement de simulation** : Cisco Packet Tracer  

### Détails de l’architecture :
- Chaque **bâtiment** contient :
  - Une **couche d’accès** (switchs d’accès pour les hôtes)
  - Une **couche de distribution** (agrégation et routage local)
- Les **couches de distribution** de tous les bâtiments sont reliées à :
  - Une **couche cœur (Core Layer)** centrale
- La couche cœur est composée de :
  - **2 switches**
  - **2 routeurs**, chacun associé à un switch afin de simuler un **switch Layer 3**
- Cette conception permet :
  - Une meilleure **scalabilité**
  - Une **tolérance aux pannes**
  - Une **séparation logique du trafic** (VLANs, routage inter-VLAN)

---

