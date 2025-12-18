# DOEK - Projet de conservation et restauration

**DOEK** (signifiant *chiffon* ou *tissu* en néerlandais) est un logiciel de modélisation 3D historique conçu spécifiquement pour l'artiste **Annie Abrahams** par Jan de Weille dans les années 1990.

Ce projet archive et reconstitue le second original de ce logiciel emblématique de l'art numérique.

---

## 📖 À propos du projet

### Contexte historique

DOEK a été développé sur **Amiga 500Plus** et **Amiga 1000** entre 1990 et 1993. Ce logiciel permettait à Annie Abrahams de :

- Simuler des espaces d'exposition virtuels
- Modéliser l'accrochage de ses œuvres en 3D
- Explorer différentes configurations d'exposition
- Créer ce qu'elle appelait la **"rechaotisation"** : superposition des possibles pour évoquer ses tableaux chaotiques

### Importance du logiciel

- **Outil de création** : accompagna l'artiste durant des années, témoignant d'une méthodologie de travail particulière
- **Innovation technologique** : utilisation précoce de la modélisation 3D à des fins artistiques
- **Documentation d'exposition** : utilisé lors de l'exposition ESCA (1995)

---

## 🖥️ Spécifications techniques

### Matériel d'origine

- **Processeur** : Motorola 68000 (16/32 bits CISC)
- **Mémoire RAM** : 512 Ko (Chip RAM)
- **Système d'exploitation** : AmigaOS 1.2 ou 1.3
- **Chipset** : OCS
- **Lecteur** : disquette 3.5" double face/simple densité (880 Ko)

### Langage et développement

- **Langage** : C
- **Développeur** : Jan de Weille
- **Format source** : listing papier en code C (uniquement document conservé)

---

## 🔧 Restauration et reconstruction

### Phase 1 : Numérisation (2014-2015)

1. Scan du listing papier au format A3
2. Retouche des zones imprimées
3. Tests de reconnaissance optique de caractères (OCR) - résultats décevants
4. Décision : transcription manuelle du code

### Phase 2 : Partenariat IUT Aix-Marseille (2015)

Un groupe d'étudiants en licence professionnelle et leur tuteur Éric Remy ont :
- Saisi l'intégralité du code C
- Compilé le logiciel sur **Amiga 500** (via émulateur FS-UAE)
- Intégré les fonctions originales
- Effectué des corrections et débogage

**Résultat en mai 2015** : DOEK réactivé sur Amiga 500, avec certaines fonctionnalités à finaliser.

### Phase 3 : Portage web

Une version JavaScript accessible en ligne a été développée :
- Interface de navigation
- Intégration de la police Amiga
- Fonctionnalités essentielles disponibles
- Travaux en cours pour amélioration esthétique et technique

---

## 📁 Structure du repository

```
DOEK_Annie_Abarahams/
├── CODE DOEK/              # Code source C du logiciel
├── DOEK synthèse.pdf       # Document récapitulatif
├── Plaquette.pdf           # Documentation visuelle
├── Scan.jpg                # Image du listing papier
└── README.md               # Ce fichier
```

---

## 🎯 Fonctionnalités principales

### Modélisation 3D

- Création de scènes 3D vides
- Placement de points dans un espace 3D (coordonnées x, y, z)
- Connexion de points pour créer des lignes
- Représentation filaire des objets 3D

### Gestion d'exposition

- Stockage de données pour chaque œuvre (dimensions, système d'accrochage)
- Stockage des informations d'espace (dimensions, cloisons, fenêtres)
- Simulation de multiples configurations d'accrochage

### Interaction utilisateur

- Contrôle à la souris pour placement de points
- Exploration interactive de l'espace virtuel
- Superposition des configurations possibles

---

## 📊 Exposition et impact

### Exposition "Une Archéologie des médias"
- **Date** : 20/05/2015 - 28/06/2015
- **Lieu** : Seconde Nature, France
- **Exposition du second original** : listing papier, code source numérisé, documentation du projet

### Impact artistique

Les images générées par DOEK sont décrites comme :
> *"intéressantes comme images graphiques classiques, mais elles sont aussi le symbole des possibilités inconnues de la technique. Ces images ne sont pas 'gratuites'; elles sont toujours basées sur une entité dans la réalité, en l'occurrence sur les tailles physiques de l'espace et les tableaux."*

---

## 👥 Contributeurs et partenaires

- **Artiste** : Annie Abrahams
- **Développeur original** : Jan de Weille
- **Tuteur IUT** : Éric Remy (IUT Aix-Marseille, site d'Arles)
- **Groupe d'étudiants** : Licence professionnelle Système Informatique et Logiciel
- **Institution de conservation** : PAMAL (Preservation & Art - Media Archaeology Lab)

---

## 📚 Documentation additionnelle

- [Synthèse complète](./DOEK%20synthèse.pdf) - Documentation technique détaillée
- [Plaquette du projet](./Plaquette.pdf) - Guide visuel
- 
---

## 🔐 Licence et droits

Ce projet de conservation est mené à titre documentaire et archéologique. Pour toute utilisation des œuvres ou du code de DOEK, veuillez contacter :

- **PAMAL_Group** - Preservation & Art - Media Archaeology Lab
- **Annie Abrahams** - Artiste

---

## 🌐 Ressources

- [PAMAL Group](https://github.com/PAMALGroup) - Groupe de conservation du matériel numérique
- [FS-UAE](https://fs-uae.net/) - Émulateur Amiga utilisé pour la restauration
- [AmigaOS](https://en.wikipedia.org/wiki/AmigaOS) - Système d'exploitation historique

---

## 📞 Contact et informations

Pour plus d'informations sur le projet DOEK ou sur la conservation du patrimoine numérique :
- **Email** : contact@pamal.org
- **Site** : [PAMAL Group](https://pamal.org)

---

**⭐ Un projet historique de conservation du patrimoine numérique - 1990-2015**

*"DOEK témoigne de l'utilisation des technologies numériques comme outil de création artistique et de réflexion plastique."*
