# BTS SIO Projet 2 - Forum BTS SIO

**Période**: 2019  
**Niveau**: BTS SIO - SIO1  
**Type**: Forum PHP avec système d'authentification

## 📋 Description du Projet

Forum BTS SIO est une application web PHP développée pour créer un espace de discussion entre étudiants du BTS SIO. Le projet inclut un système complet d'inscription/connexion utilisateur et un système de discussions thématiques.

## 🛠️ Technologies Utilisées

- **Backend**: PHP
- **Frontend**: HTML5, CSS3, JavaScript
- **Base de données**: MySQL
- **Sécurité**: Authentification utilisateur, sessions PHP

## 🎯 Fonctionnalités

- **Système d'inscription** et de connexion utilisateur
- **Gestion des sessions** utilisateur
- **Création de discussions** par catégorie
- **Système de réponses** aux messages
- **Interface d'administration** basique
- **Design responsive** et moderne

## 📁 Structure du Projet

```
BTS-SIO-Projet-2/
├── index.php           # Page d'accueil
├── login.php           # Page de connexion
├── register.php        # Page d'inscription
├── forum.php           # Interface du forum
├── includes/           # Fichiers PHP communs
├── css/                # Styles CSS
├── js/                 # Scripts JavaScript
├── sql/                # Scripts de base de données
└── README.md           # Documentation
```

## 🚀 Installation et Utilisation

1. **Cloner le repository**:
   ```bash
   git clone https://github.com/Elysio3/BTS-SIO-Projet-2.git
   ```

2. **Configuration de la base de données**:
   ```sql
   -- Importer le fichier SQL fourni
   mysql -u root -p < sql/forum_database.sql
   ```

3. **Configuration PHP**:
   - Modifier les paramètres de connexion dans `includes/config.php`
   - Démarrer un serveur web local (XAMPP, WAMP, etc.)

4. **Accès**:
   - Ouvrir `http://localhost/BTS-SIO-Projet-2/` dans un navigateur

## 📊 Compétences Développées

- Développement PHP orienté objet
- Gestion de base de données MySQL
- Système d'authentification et de sessions
- Sécurité web (protection contre les injections SQL)
- Interface utilisateur pour applications web
- Gestion des formulaires et validation des données

## 🎓 Contexte Éducatif

Ce projet représente une étape importante dans l'apprentissage du développement web backend. Il démontre la maîtrise de PHP, de la gestion de base de données et des concepts de sécurité web.

## 🔒 Sécurité

- **Protection contre les injections SQL** avec requêtes préparées
- **Validation des données** côté serveur
- **Gestion sécurisée des sessions** utilisateur
- **Échappement des données** utilisateur

## 📸 Captures d'écran

*[À ajouter: captures d'écran du forum]*

## 🔗 Liens

- **Repository**: https://github.com/Elysio3/BTS-SIO-Projet-2
- **Portfolio**: [Lien vers le portfolio principal]

---

**Développé par**: Maël KERVICHE  
**École**: [Nom de l'école]  
**Année**: 2019