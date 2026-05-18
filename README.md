# Brain Tumor Detection App

Projet académique d'analyse de données : classification d'images IRM cérébrales avec deep learning.

## Objectif
Importer une image IRM du cerveau et prédire la classe : glioma, meningioma, notumor ou pituitary.

## Dataset conseillé
Kaggle - Brain Tumor MRI Dataset : https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

Structure attendue :

```text
data/
  Training/
    glioma/
    meningioma/
    notumor/
    pituitary/
  Testing/
    glioma/
    meningioma/
    notumor/
    pituitary/
```

## Étapes
1. Télécharger le dataset depuis Kaggle.
2. Mettre `Training` et `Testing` dans le dossier `data/`.
3. Lancer le notebook ou le script `notebooks/train_model.py`.
4. Vérifier que le modèle est sauvegardé dans `model/brain_tumor_model.keras`.
5. Lancer l'application :

```bash
streamlit run app/app.py
```

## Avertissement
Cette application est réalisée uniquement à des fins pédagogiques. Elle ne remplace pas un diagnostic médical.
