# 📊 Visualiser un fichier Excel avec Python et Plotly

Créez un graphique élégant à partir de n’importe quel tableau Excel… **sans utiliser Power BI !**

---

## 📌 Objectif

Ce projet vous montre comment :
- Charger un fichier Excel depuis votre ordinateur (manuellement)
- Lire les données avec pandas
- Générer un graphique interactif avec Plotly
- Télécharger l’image pour vos présentations

---

## 🧰 Technologies utilisées

- Python
- pandas
- plotly
- Google Colab
- kaleido (pour exporter les images)

---

## 🚀 Comment utiliser ce projet

1. Ouvrir le notebook dans Google Colab :  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1n016iUD_NzPj4m1ubHRzGez9tpwrlT-g)


2. Charger votre propre fichier Excel quand demandé (`ventes_par_produit.xlsx`, par exemple)

3. Le script :
- lit les données,
- crée un graphique Plotly stylé,
- vous permet de **le télécharger** facilement.

---

## ✏️ Exemple de personnalisation

```python
fig = px.bar(
    df,
    x="Produit",  # ou toute autre colonne
    y="Ventes",
    color="Produit",
    text="Ventes"
)
```

---

## 📂 Exemple de fichier attendu

| Produit | Ventes |
|---------|--------|
| A       | 120    |
| B       | 340    |
| C       | 230    |
| D       | 150    |
| E       | 280    |

---

## 🧠 Pourquoi ce projet ?

🎯 Beaucoup de professionnels travaillent avec Excel mais ne savent pas comment **visualiser rapidement leurs données**.  
Ce projet rend la data visualisation accessible **en quelques minutes**, sans outil complexe.

---

## 📬 Contact

Pour toute suggestion ou retour :  
👉 [LinkedIn – Mathieu Carré](https://www.linkedin.com/in/matthieu-carre-data/)
