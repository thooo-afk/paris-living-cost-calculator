# paris-living-cost-calculator
Analyse complète du budget mensuel pour vivre à Paris avec 2500€/mois.  Calcul du reste à vivre par quartier pour T2/T3 non meublés,  incluant toutes les dépenses (nourriture, transport, vacances, etc.)
# 🏠 ParisBudget Analyzer

**Analyse complète du coût de la vie à Paris pour un salaire de 2500€/mois**

Outil d'analyse budgétaire permettant d'identifier les meilleurs quartiers parisiens pour vivre avec un budget limité, en tenant compte de **toutes** les dépenses mensuelles : loyer, nourriture, transport, hygiène, loisirs, et même les vacances !

---

## 📊 Aperçu du projet

Ce projet analyse les données de loyers à Paris (T2 et T3 non meublés) et calcule le **reste à vivre** après déduction de toutes les dépenses mensuelles réalistes :

- 🏠 **Loyer + charges** (par quartier)
- 🍽️ **Alimentation** (courses, restaurants, cafés)
- 🧴 **Hygiène & santé** (produits, coiffeur, mutuelle)
- 🧹 **Entretien** (produits ménagers)
- 🚇 **Transport** (Navigo)
- ✈️ **Vacances** (2 fois/an, provisionné mensuellement)
- 🎭 **Loisirs** (sport, culture, vêtements)

---

## 🎯 Objectif

Aider les personnes gagnant **2500€ net/mois** à :
- Trouver les quartiers parisiens les plus abordables
- Calculer leur capacité d'épargne réelle
- Comparer les arrondissements par reste à vivre
- Faire un choix éclairé entre T2 et T3

---

## 📈 Fonctionnalités

✅ **Analyse de 80+ quartiers parisiens**  
✅ **Calcul automatique du reste à vivre**  
✅ **Visualisations interactives** (graphiques, camemberts)  
✅ **Comparaison T2 vs T3**  
✅ **Classement par arrondissement**  
✅ **Export CSV des résultats**  
✅ **Budget détaillé incluant les vacances**  

---

## 🛠️ Technologies utilisées

- **Python 3.x**
- **Pandas** - Manipulation de données
- **NumPy** - Calculs numériques
- **Matplotlib** - Visualisations
- **Seaborn** - Graphiques statistiques
- **Google Colab** - Environnement d'exécution

---

## 🚀 Installation et utilisation

### Option 1 : Utiliser directement sur Google Colab (recommandé)

1. Ouvrez Google Colab : https://colab.research.google.com
2. Uploadez le fichier `PariBudget_Analyzer.ipynb`
3. Uploadez votre dataset de loyers (CSV)
4. Exécutez toutes les cellules
5. Consultez les résultats et graphiques

### Option 2 : Installation locale
```bash
# Cloner le repository
git clone https://github.com/VOTRE_USERNAME/PariBudget-Analyzer.git

# Installer les dépendances
pip install -r requirements.txt

# Lancer Jupyter Notebook
jupyter notebook PariBudget_Analyzer.ipynb
```

---

## 📁 Structure du projet
```
PariBudget-Analyzer/
│
├── PariBudget_Analyzer.ipynb    # Notebook principal
├── requirements.txt              # Dépendances Python
├── resultats_analyse_paris.csv   # Résultats exportés (exemple)
├── README.md                     # Documentation
└── images/                       # Captures d'écran (optionnel)
    ├── graph1.png
    ├── graph2.png
    └── graph3.png
```

---

## 📊 Résultats clés

### Budget mensuel type (2500€)

| Catégorie | Montant | % du salaire |
|-----------|---------|--------------|
| 🏠 Loyer + charges | 900-1400€ | 36-56% |
| 🍽️ Alimentation | 350€ | 14% |
| 🧴 Hygiène & santé | 110€ | 4.4% |
| 🚇 Transport | 23€ | 0.9% |
| ✈️ Vacances (prov.) | 108€ | 4.3% |
| 🎭 Loisirs | 150€ | 6% |
| 💰 **Reste à vivre** | **100-700€** | **4-28%** |

### Meilleurs arrondissements par reste à vivre

🥇 **13e, 19e, 20e** → Reste moyen : 400-500€/mois  
🥈 **18e, 11e, 10e** → Reste moyen : 300-400€/mois  
🥉 **12e, 14e, 15e** → Reste moyen : 250-350€/mois  

---

## 📸 Captures d'écran

### Graphique 1 : Top 15 quartiers
![Top 15 quartiers](images/graph1.png)

### Graphique 2 : Répartition du budget
![Budget breakdown](images/graph2.png)

### Graphique 3 : Comparaison T2 vs T3
![T2 vs T3](images/graph3.png)

---

## 💡 Personnalisation

Vous pouvez facilement adapter ce projet à votre situation :

1. **Modifier le salaire** : Changez `SALAIRE_NET_MENSUEL = 2500`
2. **Ajuster les dépenses** : Modifiez les variables dans la section "Paramètres personnels"
3. **Changer le type de logement** : Filtrez sur T1, T2, T3, ou T4
4. **Meublé vs non meublé** : Changez le filtre `Type de location`

---

## 📦 Dataset utilisé

**Source** : Observatoire des loyers de Paris  
**Année** : 2024-2025  
**Données** : Loyers de référence par quartier (encadrement des loyers)

---

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :
- 🐛 Signaler des bugs
- 💡 Proposer des améliorations
- 📊 Ajouter de nouvelles visualisations
- 🗺️ Étendre l'analyse à d'autres villes d'Île-de-France

---

## 📜 Licence

Ce projet est sous licence MIT. Vous êtes libre de l'utiliser, le modifier et le distribuer.



## 👤 Auteur

**Votre Nom**  
- LinkedIn: (https://www.linkedin.com/in/anthony-biyele-b68397222/)


---

## 🙏 Remerciements

- Données fournies par l'Observatoire des loyers de Paris
- Inspiré par le besoin d'outils d'aide à la décision pour le logement à Paris



## 📝 Notes

⚠️ **Disclaimer** : Les loyers sont basés sur des moyennes et peuvent varier selon l'état du logement, l'emplacement exact, et la période. Les charges sont estimées à 15% du loyer. Ce projet est un outil d'aide à la décision, pas un conseil financier professionnel.



**⭐ Si ce projet vous a été utile, n'oubliez pas de laisser une étoile !**

