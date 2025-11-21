<div align="center" style="font-family: 'Georgia', serif;" color: #3498db;"> <h1 style="font-size: 10em; margin-bottom: 180px;"> Boutique en Ligne – GOCCE DE CHARME:<br> </h1> </div>

📌 Table of Contents <a name="table-of-contents"></a>

📝 Project Overview

✨ Features

🧱 Technologies Used

📁 Project Structure

🚀 Installation

🌀 How It Works

📸 Screenshots

👤 Author

📝 Project Overview <a name="project-overview"></a>

Cette application est une boutique en ligne complète permettant :

d’afficher des produits

gérer un panier

passer une commande

gérer les avis

administrer les produits, commandes et utilisateurs

Elle utilise :

HTML/CSS/JavaScript → Interface utilisateur

Flask (Python) → Backend & API

MongoDB Atlas (Cloud) → Base de données NoSQL

↑ Back to Top

✨ Features <a name="features"></a>
👤 Côté Utilisateur

Inscription / Connexion

Navigation produits

Panier dynamique

Avis & Détails produit

Paiement / Validation

Suivi des commandes

🛠️ Côté Admin

Ajouter / Modifier / Supprimer produits

Gérer utilisateurs

Gérer commandes

Dashboard

↑ Back to Top

🧱 Technologies Used <a name="technologies-used"></a>
Layer	Technologie
Frontend	HTML, CSS, JavaScript
Backend	Python Flask
Database	MongoDB Atlas
API	Flask REST
Auth	Sessions / cookies

↑ Back to Top

📁 Project Structure <a name="project-structure"></a>
project/
│── app.py
│── config.py
│── requirements.txt
│
├── templates/
│   ├── accueil.html
│   ├── login.html
│   ├── signup.html
│   ├── liste_produits.html
│   ├── produit_detail.html
│   ├── mon_panier.html
│   ├── paiement.html
│   ├── dashboard.html
│   ├── update_produit.html
│   └── utilisateurs.html
│
└── static/
    ├── css/
    └── js/


↑ Back to Top

🚀 Installation <a name="installation"></a>
1️⃣ Cloner le projet
git clone https://github.com/<username>/<repo>.git
cd <repo>

2️⃣ Installer les dépendances
pip install -r requirements.txt

3️⃣ Configurer MongoDB Atlas

Dans config.py :

MONGO_URI = "mongodb+srv://<username>:<password>@cluster.mongodb.net/"

4️⃣ Lancer Flask
python app.py


➡️ Accès : http://127.0.0.1:5000/

↑ Back to Top

🌀 How It Works <a name="how-it-works"></a>

Le frontend envoie les requêtes au backend Flask

Flask communique avec MongoDB Atlas

Chaque utilisateur possède son panier

Les commandes sont stockées en base

L’interface admin permet d’agir sur tout le système

↑ Back to Top

📸 Screenshots <a name="screenshots"></a>
<div align="center"> <img src="images/home.png" width="800"> </div>

↑ Back to Top

👤 Author <a name="author"></a>

Ton Nom

GitHub : https://github.com/
<username>

↑ Back to Top
