# Projet Réseau (AITAOUICHA YASSINE) : Architecture Réseau de l’EUROMED UNIVERSITY OF FES (UEMF)

# Objectif du Projet
Ce projet a pour objectif de concevoir et de simuler l’architecture réseau complète de l’**EUROMED UNIVERSITY OF FES (UEMF)** en utilisant **Cisco Packet Tracer**.  
L’architecture proposée vise à assurer une **connectivité fiable**, une **bonne segmentation du réseau**, une **haute disponibilité** et une **facilité de gestion**, tout en respectant les standards des architectures réseaux modernes.

Le campus est composé de **6 bâtiments**, chacun comprenant **3 étages**.  
Le **premier bâtiment** est dédié aux services **administratifs et pédagogiques**, tandis que les autres bâtiments hébergent les salles de cours, laboratoires et services académiques.

Le réseau est conçu selon une **architecture 3-tiers** :
- Couche **Accès**
- Couche **Distribution**
- Couche **Cœur**

Chaque bâtiment dispose de sa propre couche d’accès et de distribution, toutes reliées à une **couche cœur centralisée**.

---

# Description Générale de l’Architecture

- **Nombre de bâtiments** : 6  
- **Nombre d’étages par bâtiment** : 3  
- **Architecture réseau** : Architecture hiérarchique 3-tiers  
- **Environnement de simulation** : Cisco Packet Tracer  

### Détails de l’architecture :
- Chaque **bâtiment** contient :
  - Une **couche d’accès** (switchs d’accès pour les hôtes)
  - Une **couche de distribution** (agrégation et routage local)
- Les **couches de distribution** de tous les bâtiments sont reliées à :
  - Une **couche cœur (Core Layer)** centrale
- La couche cœur est composée de :
  - **1 switch**
  - **1 routeur**,  associé à un switch afin de simuler un **switch Layer 3**
- Cette conception permet :
  - Une meilleure **scalabilité**
  - Une **tolérance aux pannes**
  - Une **séparation logique du trafic** 

---


<img width="1641" height="725" alt="image" src="https://github.com/user-attachments/assets/04d33cfa-2105-4725-822a-e6400051b696" />
