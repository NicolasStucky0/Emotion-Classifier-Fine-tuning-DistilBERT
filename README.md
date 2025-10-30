# 🧠 Emotion Classifier – Fine-tuning DistilBERT

Ce projet met en place un pipeline complet de **classification d’émotions** à partir du modèle pré-entraîné `distilbert-base-uncased`, fine-tuné sur le dataset **Emotion** de 🤗 Hugging Face.

---

## 🎯 Objectifs
- Utiliser un modèle pré-entraîné (`distilbert-base-uncased`)
- Fine-tuner sur le dataset *Emotion* (6 émotions)
- Sauvegarder le modèle
---

## 🧱 Structure du projet
```
emotion-classifier/
│
├── emotion_classification.ipynb   # Notebook principal
├── models/                        # Modèle fine-tuné sauvegardé
├── requirements.txt               # Dépendances Python
└── README.md                      # Documentation du projet
```

---

## ⚙️ Installation

### 1️⃣ Cloner le dépôt
```bash
git clone [https://github.com/<ton_nom_utilisateur>/emotion-classifier.git](https://github.com/NicolasStucky0/Emotion-Classifier-Fine-tuning-DistilBERT.git)
cd emotion-classifier
```

### 2️⃣ Créer un environnement virtuel (recommandé)
```bash
python -m venv venv
source venv/bin/activate   # ou venv\Scripts\activate sous Windows
```

### 3️⃣ Installer les dépendances
```bash
pip install -r requirements.txt
```

---

## 🚀 Utilisation

### 🧩 Exécuter le notebook
Lance le notebook `emotion_classification.ipynb` (sous Jupyter ou Google Colab)  
pour fine-tuner le modèle sur le dataset Emotion.

Le modèle sera automatiquement sauvegardé dans :
```
./models/emotion-distilbert/
```

---

## 🔮 Améliorations possibles
- Ajuster le nombre d’époques ou le learning rate  
- Tester d’autres modèles (`bert-base-uncased`, `roberta-base`, etc.)  
- Ajouter des métriques (F1, confusion matrix, etc.)  
- Déployer le modèle sur Hugging Face Hub
