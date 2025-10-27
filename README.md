# REMITTANCE
# Analyse économétrique des remittances en Afrique (2001–2024)

## 🎯 Objectif du projet
Ce projet vise à étudier les **déterminants macroéconomiques** des remittances (% du PIB) dans quinze pays africains entre 2001 et 2024 à partir des données de la **Banque mondiale**.

## 🧠 Méthodologie
- Nettoyage et transformation des données sous **Python**
- Visualisations exploratoires des tendances et corrélations
- Estimation de modèles économétriques de panel :
  - Modèle à effets fixes (FE)
  - Modèle à effets aléatoires (RE)
  - Test de Hausman pour le choix du modèle approprié

## ⚙️ Outils utilisés
- Python 3.12  
- Pandas, Matplotlib, Seaborn  
- Statsmodels, Linearmodels  

## 📊 Résultats clés
- Le **PIB par habitant**, le **commerce international** et la **population (log)** exercent un effet **positif et significatif** sur les remittances.
- L’**inflation** a un effet **négatif et significatif**, traduisant une perte de pouvoir d’achat et de confiance économique.
- L’impact du **COVID-19** n’est pas significatif, suggérant une **résilience** des flux migratoires pendant la crise.
- Le **modèle à effets aléatoires (RE)** a été retenu suite au test de Hausman (p-value = 1.0000).

## 🗂️ Données
Source : [World Development Indicators – World Bank](https://databank.worldbank.org/source/world-development-indicators)

## 🧾 Références principales
- Wooldridge, J. M. (2010). *Econometric Analysis of Cross Section and Panel Data*. MIT Press.  
- Gupta, S., Pattillo, C., & Wagh, S. (2009). *Effect of Remittances on Poverty and Financial Development in Sub-Saharan Africa*. *World Development*, 37(1), 104–115.  
- World Bank (2022). *Migration and Development Brief 36: Resilience in the Face of Crises*.

## ✍️ Auteure
**Irene ANDE**  
Projet personnel d’analyse économétrique sur données de panel  
📧 andrirene75@email.com
