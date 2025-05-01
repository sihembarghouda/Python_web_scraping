
# 🕸️ Web Scraping Job Keywords Analyzer

## 👥 Mini projet à faire en binôme

## 💡 Idées proposées pour le projet de scraping

### 🔍 1. Suivi des prix des produits
- Récupérez les prix des produits sur des sites e-commerce.
- Envoyez des alertes quand le prix baisse.
- **Sites suggérés** : Amazon, Flipkart, eBay

### 📰 2. Agrégateur de nouvelles
- Collectez des articles depuis plusieurs sources.
- Filtrage par mots-clés ou thématiques.
- Résumés automatiques.
- **Sites suggérés** : Feedly, Google Actualités, Flipboard

### 💼 3. Scraper les offres d'emploi
- Rassemblez les offres d’emploi par secteur, lieu ou entreprise.
- **Sites suggérés** : Indeed, ZipRecruiter, Monster

### 📊 4. Analyse des sentiments sur les réseaux sociaux
- Parcourez Twitter, Facebook, etc. pour analyser les opinions sur un sujet.
- Très utile pour la réputation de marque.
- **Sites suggérés** : Twitter, Facebook, Instagram

## 🚀 Fonctionnalités du projet existant
- Récupération de commentaires depuis Hacker News
- Extraction de mots-clés technologiques
- Nettoyage de texte et transformation en set pour unicité

## 🧪 Technologies utilisées
- Python 3
- Requests
- BeautifulSoup4
- Matplotlib (optionnel)
- FastAPI (optionnel)
- Selenium (optionnel)
- Streamlit (optionnel)

## ⚙️ Installation & Commandes utiles

```bash
# Créer l’environnement virtuel
python -m venv .venv

# Activer l’environnement (Windows)
.\.venv\Scripts\activate

# Lancer le script principal
python scraper.py

# Installer les dépendances
pip install requests
pip install beautifulsoup4
pip install matplotlib

# Geler les dépendances dans un fichier
pip freeze > requirements.txt
```

## 🌐 Exécution de l’API (si FastAPI activé)
```bash
uvicorn scraper:app --reload
```

## 📌 Prochaines étapes possibles
- Adaptation à d’autres sites web
- Création d’une API sans serveur
- Intégration Selenium pour interaction dynamique
- Stockage CSV / Base de données
- Création d’un tableau de bord Web

## 📄 Licence
Projet open-source sous licence MIT.
