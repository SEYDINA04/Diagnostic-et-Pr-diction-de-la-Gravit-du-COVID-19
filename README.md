# 🦠 Projet IA : Diagnostic et Prédiction de la Gravité du COVID-19

Ce projet a été réalisé à partir d’un jeu de données médicales fourni par l’hôpital Israelita Albert Einstein (Brésil), disponible sur [Kaggle](https://www.kaggle.com/). Il s’inscrit dans le cadre de mes explorations autour de l’Intelligence Artificielle appliquée à la santé.

---

## 🎯 Objectifs du projet

- **Task 1** : Prédire si un patient suspecté de COVID-19 est effectivement positif au test RT-PCR, à partir d’examens biologiques standards.
- **Task 2** : Pour les cas confirmés, prédire le **niveau de gravité** attendu : hospitalisation en service général, semi-intensif ou en unité de soins intensifs (ICU).

---

## 🧠 Technologies utilisées

- **Python 3.10+**
- **Pandas / NumPy** : traitement et nettoyage des données
- **Scikit-learn** : modélisation, évaluation et sélection de modèles
- **Matplotlib / Seaborn** : visualisation des données
- **SMOTE** : rééchantillonnage pour classe minoritaire
- **GridSearchCV** : optimisation des hyperparamètres

---

## 📁 Fichiers principaux

- ` 3-Modelisation.ipynb` : Notebook complet du projet, incluant :
  - Prétraitement et visualisation des données
  - Création de modèles (SVM, Random Forest…)
  - Équilibrage des classes avec SMOTE
  - Optimisation des hyperparamètres
  - Évaluation : F1-score, recall, courbe ROC
  - Ajustement du **seuil de décision**

---

## ✅ Résultats

Modèle final (SVM optimisé avec GridSearchCV) :  
- **F1-score** : 0.53  
- **Recall** : 0.68  
- **Seuil ajusté** : -1  
Ces résultats ont été obtenus après gestion du déséquilibre des classes et analyse de l’impact du seuil de classification.

---

## 💡 Enseignements

Ce projet a constitué **le point de départ de ma réflexion sur les systèmes IA appliqués à la santé**. Il m’a permis de :

- Comprendre les enjeux de la classification médicale dans un contexte pandémique
- Prendre en main la manipulation de données cliniques (réelles, bruyantes et incomplètes)
- Explorer des solutions concrètes face à l’enjeu de saturation des hôpitaux


---

## 📌 Prochaines étapes

- Intégrer des variables cliniques supplémentaires (âge, symptômes, comorbidités)
- Déployer une API pour prédiction en ligne
- Étendre la solution aux maladies chroniques

---

## 👨‍💻 Auteur

**Babacar NDAO**  
Master 2 en Génie Logiciel (IA & Big Data)  
📫 nbcprof04@gmail.com  
🔗 [GitHub – Seydina04](https://github.com/SEYDINA04)

---

## 🔖 Licence

Projet open-source sous licence MIT. Vous êtes libre de le réutiliser à des fins éducatives ou de recherche.
