# Sac de sable

### *Par Samuel Desmeules-Voyer*

*[URL du Document](https://samesthumain.github.io/#/)*

## Concept
Je veux que l'utilisateur s'immerse dans le rôle d'un boxeur qui s'entraine pour son premier vrai match.

<img src="./images/sac_de_sable.png" alt="sac de sable" width="500"/>

### Objectif
L'objectif de l'oeuvre est de promouvoir le sport, l'esprit sportif, l'esprit de compétition.
Mon but est de faire bouger les gens.


## Scénario

```mermaid
flowchart TD
    A(L'utilisateur entre dans la salle) --> B[Il met les gants de boxe et les écouteurs et se place devant l'installation]
    B --> C[Il commence l'activité en appuyant sur un des panneaux, les instructions sur comment l'activité marche seront transmises par les écouteurs]
    C --> D[Il frappe sur les panneaux en rythme avec la musique et les directives ressues par les écouteurs, plus le temps passe, plus il faut réagir vite aux instructions]
    D -->|Il ne fait pas d'erreur| E[L'activitée continue normalement]
    D -->|Il fait des erreurs| F[Il doit recommencer la partie de l'activité dans laquelle il a fait une erreur]
    F --> E
    C -->|IL appuie sur le bouton quitter à côté de l'installation| G(L'activitée peut être arrêtée en tout temps)
    G --> H[L'activitée est terminée]
    E --> H

```

## Ambiance
### Visuelle
<img src="./images/moodboard.png" alt="sac de sable" width="500"/>

### Sonore

[Exemple de musique](https://www.youtube.com/watch?v=KPhqU--Mq1A)
[Exemple de Voix](https://www.youtube.com/watch?v=q-7bo1i_ZbA)

## Technologies

### Support
**Audio:**
- Écouteurs bluetooth  

**Lumière:**
- Lumières de scène
- LEDs bleus, blancs et rouges

### Matériel
**Intéractif:**
- M5Stack Atom
- Boutons  
<img src="./images/m5stack.jpg" alt="sac de sable" width="100"/> <img src="./images/bouton.jpg" alt="sac de sable" width="100"/>

**Autre:**
- Panneux et cylindre (imprimés en 3d)
- Table
- Peinture
- Gants de boxe
- Vis et visseuse pour fixer le "sac de sable" à la table
- Des ressorts pour le fonctionnement des panneaux

### Logiciel
- Arduino
- Reaper
- Max

*documentation par Samuel Desmeules-Voyer*
