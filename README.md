# Abderrahmane Boudia

**Comptabilité · Audit · Contrôle de gestion**, avec des outils de données (Excel, Python)

Titulaire d'un Master en Comptabilité et Audit (Bac+5, Alger) · près de trois ans d'expérience en Algérie · candidat en master en France pour la rentrée 2027

[![Email](https://img.shields.io/badge/Email-boudiaabderrahmane5%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:boudiaabderrahmane5@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Abderrahmane%20Boudia-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/A-COMPLETER)
[![GitHub](https://img.shields.io/badge/GitHub-boudia--abderrahmane-181717?logo=github&logoColor=white)](https://github.com/boudia-abderrahmane)
[![CV](https://img.shields.io/badge/CV-Consulter-2E7D32?logo=readthedocs&logoColor=white)](https://github.com/boudia-abderrahmane/BOUDIA-Abderrahmane/blob/main/CV/CV.md)


---

## À propos

Diplômé en comptabilité et audit, j'ai travaillé en audit interne, en gestion comptable d'une structure et en pilotage de flux logistiques. Je m'intéresse surtout à ce qui se passe **avant** le chiffre : d'où vient la donnée, comment la contrôler et ce qu'on peut en conclure.

Je prépare un master en France pour consolider ce socle avec les référentiels et les outils français, et évoluer vers le **contrôle, l'audit et le pilotage de la performance** des organisations.

---

## Projets

> Projets personnels d'apprentissage, réalisés avec l'appui d'un assistant d'IA (Claude) pour le code. Leur intérêt est la démarche financière et le contrôle des données. Ce ne sont pas des produits logiciels.

### 💶 [Pilotage de trésorerie](https://github.com/boudia-abderrahmane/pilotage-tresorerie)

**Question :** comment suivre et anticiper la trésorerie d'une petite entreprise à partir de ses seuls mouvements bancaires ?

- **Contrôle des données avant tout calcul**, comme un rapprochement bancaire : dates invalides, montants nuls ou négatifs, sens ou type de flux inconnu, catégorie vide, doublons. Chaque anomalie est signalée avec son numéro de ligne. Rien n'est corrigé ni supprimé automatiquement, et l'outil **refuse d'analyser** tant qu'une erreur bloquante subsiste.
- Synthèse mensuelle des encaissements, décaissements, flux nets et soldes, avec la distinction **exploitation / investissement / financement**.
- Deux contrôles arithmétiques de l'outil lui-même : le report des soldes d'un mois à l'autre, et le solde final recalculé depuis les transactions.
- Prévision à trois mois par moyenne mobile (scénario central et scénario prudent), puis exports CSV qui s'ouvrent directement dans Excel en français.

Données **fictives** : 480 mouvements sur 24 mois pour une entreprise de distribution imaginaire.
`Python` `pandas` `matplotlib` `Streamlit` `Git`

<img src="https://raw.githubusercontent.com/boudia-abderrahmane/pilotage-tresorerie/main/docs/images/solde_tresorerie.png" alt="Solde de trésorerie en fin de mois sur 24 mois, avec un passage en solde négatif en août 2024" width="720">

### 📉 [FinRisk AI : diagnostic financier et risque de défaillance](https://github.com/boudia-abderrahmane/finrisk-ai)

**Question :** que peuvent apporter des modèles de prédiction à l'analyse des ratios pour repérer les entreprises en difficulté, et que devient ce diagnostic quand l'information comptable est incomplète ?

- Diagnostic financier par les ratios (rentabilité, endettement, liquidité, rotation) sur **5 910 états financiers** d'entreprises polonaises (UCI, 64 ratios, 6,9 % de défaillances).
- Comparaison de trois modèles avec une référence naïve : régression logistique, Random Forest et XGBoost. Le seuil d'alerte est fixé sur un échantillon de validation, puis le modèle est évalué sur un jeu de test séparé.
- **Effet de la qualité des données :** en masquant au hasard une partie des valeurs, la précision moyenne (Average Precision) du meilleur modèle passe de 0,84 à 0,49 avec 10 % de données manquantes. Le modèle le plus performant sur données complètes (XGBoost) est aussi celui qui se dégrade le plus vite.
- Restitution sous forme de **fiche d'analyse** pour un cas d'entreprise, avec les ratios qui pèsent le plus dans le score. Les limites sont documentées : données polonaises de 2000 à 2013, secteur inconnu, aucune validité pour une entreprise française ou algérienne sans données locales.

`Python` `pandas` `scikit-learn` `XGBoost` `Streamlit` `Jupyter` `Excel`

<img src="https://raw.githubusercontent.com/boudia-abderrahmane/finrisk-ai/main/reports/figures/07_qualite_donnees_vers_diagnostic.png" alt="Dégradation de la précision, du rappel et du F1 des trois modèles quand la part de données masquées passe de 0 à 20 %" width="720">

---

## Parcours professionnel

| Période | Poste | Ce que j'y ai fait |
|---|---|---|
| juil. – déc. 2025 | **Chargé de gestion de stock et administration financière**<br>SARL Indigo Med (import et distribution de matériel médical), Alger | Flux de stocks et conformité, achats à l'international et suivi douanier, inventaires tournants et valorisation des stocks, tableaux de bord |
| oct. 2023 – mai 2025 | **Gérant d'établissement**<br>HomeFit, Alger | Direction opérationnelle, administrative et financière : comptabilité journalière, caisse et trésorerie, maîtrise des dépenses, encadrement d'équipe |
| janv. – mai 2023 | **Stagiaire en audit interne**<br>Algérienne des Autoroutes (ADA), Alger | Cartographie des risques financiers et administratifs, analyse du circuit de facturation et des délais de paiement, plans d'action correctifs |
| janv. – mai 2021 | **Stagiaire en comptabilité et finance**<br>RUTA 1, Alger | Vérification et imputation des mandats de paiement, rapprochements bancaires, travaux de clôture |

---

## Formation

- **Master en Comptabilité et Audit** : Faculté des Sciences Économiques, Dely Ibrahim (Alger), 2021–2023. Audit, normes IFRS/IAS, fiscalité, analyse financière avancée, consolidation.
- **Licence en Sciences Financières et Comptabilité** : même faculté, 2017–2021. Mathématiques financières, comptabilité analytique, contrôle de gestion.
- **Certification** : maîtrise des procédures de préparation et d'exécution des inventaires, Learning Business Training (organisme agréé par l'État).

---

## Compétences

| Domaine | Compétences |
|---|---|
| Comptabilité, audit, finance | Audit comptable et financier · normes IFRS/IAS · fiscalité d'entreprise · contrôle interne et cartographie des risques · trésorerie et rapprochements bancaires |
| Gestion des flux | Stocks et inventaires (méthode certifiée) · procédures import/export et suivi douanier · suivi de facturation · tableaux de bord |
| Bureautique | Excel (formules, tableaux de bord, analyse de données) · Word · PowerPoint |
| Données | Python appliqué à l'analyse financière (pandas, Streamlit) · initiation au machine learning (scikit-learn, XGBoost) · Power BI (notions) · Git et GitHub |

**Langues :** arabe (langue maternelle) · français (courant, TCF B2) · anglais <!-- préciser le niveau -->

