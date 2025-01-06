# Jigsaw Multilingual Toxic Comment Classification

Ce projet s'attaque au problème de classification des commentaires toxiques dans un contexte multilingue, proposé dans la compétition Kaggle **Jigsaw Multilingual Toxic Comment Classification**. L'objectif est de prédire si un commentaire est toxique ou non à partir de textes dans différentes langues.

---

## Approche

1. Utilisation du modèle pré-entraîné **DistilBERT Multilingual** (`distilbert-base-multilingual-cased`) pour la classification binaire.
2. Implémentation de deux techniques :
   - **Fine-tuning classique**.
   - **Parameter-Efficient Fine-Tuning (PEFT)** pour une approche optimisée des ressources.
3. Comparaison des performances sur les données de test.

---

## Résultats

Les performances des deux approches sont similaires :
- **Accuracy** : 0.79
- PEFT n'a pas montré de gain significatif sur ce problème mais reste une méthode prometteuse pour des scénarios différents.

---

## Technologies Utilisées

- **Python** et **Hugging Face Transformers**
- **PyTorch**, **datasets**, et **scikit-learn**

---

## À Propos

Pour plus d'informations sur le problème, consultez la [page Kaggle de la compétition](https://www.kaggle.com/competitions/jigsaw-multilingual-toxic-comment-classification). Contributions et discussions sont les bienvenues !
