dev# Genealogie-frontend
# 🌳 Family Tree Builder - Application de Généalogie

Un outil complet pour visualiser et gérer votre arbre généalogique avec une interface intuitive et des fonctionnalités puissantes.

## ✨ Fonctionnalités Principales

- **Visualisation Interactive** : Arbre généalogique dynamique avec navigation fluide  
- **Gestion des Membres** :
  - Ajout de nouvelles personnes
  - Ajout de conjoints
  - Ajout d'enfants
  - Suppression de membres
- **Style Automatique** :
  - Différenciation visuelle hommes/femmes
  - Types de relations distincts (conjoints, parents-enfants)
- **Système de Recherche** : Trouvez rapidement des membres dans l'arbre

## 🛠 Installation

1. **Prérequis** :
   - Node.js (v14+)
   - npm ou yarn
   - API backend (voir configuration)


src/
├── components/
│   ├── FamilyTree/
│   │   ├── AddChildForm.tsx
│   │   ├── AddPersonForm.tsx
│   │   ├── AddSpouseForm.tsx
│   │   └── TreeView.tsx
├── types/
│   └── FamilyTypes.ts
├── api/
│   └── familyTree.ts

2. **Configuration** :
   ```bash
   git clone [URL_DU_PROJET]
   cd family-tree-builder
   npm install
   npm run dev
