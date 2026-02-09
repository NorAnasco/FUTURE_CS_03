# Future Interns - Cyber Security Internship
## Task 3: API Security Testing & Vulnerability Assessment

### Intern Information
- **Name:** ANANIVI Komlanvi
- **Assignment:** Task 3 - API Security Assessment
- **Target:** API Endpoints (Architecture REST/JSON)
  

---

### 📌 Aperçu du projet 
L'objectif de cette mission était d'évaluer la posture de sécurité des interfaces de programmation (API). Contrairement au scan web classique, cette tâche s'est concentrée sur la logique métier, les mécanismes d'authentification et l'intégrité des échanges de données entre le client et le serveur.

### 🛠️ Outils Utilisés (Tools)
* **Postman :** Pour la manipulation des requêtes (GET, POST, PUT, DELETE), l'automatisation des tests et l'analyse des réponses JSON.
* **OWASP ZAP :** Utilisé en tant que proxy d'interception pour analyser le trafic entre l'application et l'API, et pour effectuer des scans de vulnérabilités spécifiques.
* **JSON Web Token (JWT.io) :** Pour le décodage et l'analyse de la structure des jetons d'authentification.

### 🎯 Portée de l'audit (Scope)
L'audit a porté sur les éléments suivants :
* **Endpoints d'Authentification :** Vérification de la robustesse de la connexion et de la gestion des sessions.
* **Gestion des Ressources :** Analyse de l'accès aux données utilisateur via les identifiants d'objets.
* **Flux de Données :** Inspection des en-têtes HTTP (Authorization, Content-Type) et du corps des requêtes.

### ⚙️ Méthodologie
La méthodologie suivie respecte les standards de l'**OWASP API Security Top 10** :

1.  **Reconnaissance & Énumération :** Identification des différents points de terminaison (endpoints) et des méthodes HTTP autorisées.
2.  **Tests d'Authentification & Autorisation :** * Analyse de la validité et de l'expiration des tokens JWT.
    * Tests de **BOLA (Broken Object Level Authorization)** : tentative d'accès à une ressource appartenant à un autre utilisateur en modifiant l'ID dans l'URL/corps.
3.  **Tests d'Injection & Validation :** Envoi de données malformées ou inattendues pour tester la résilience des serveurs face aux injections (SQL, NoSQL, Command).
4.  **Analyse de l'Exposition de Données :** Vérification que l'API ne renvoie pas plus d'informations que nécessaire dans les réponses JSON.
5.  **Documentation & Rapport :** Synthèse des vulnérabilités découvertes, capture des preuves (screenshots) et proposition de remédiations.

---

### 📂 Livrables
* [X] **Rapport PDF :** Analyse détaillée avec recommandations prioritaires.
* [X] **Collection Postman / Preuves :** Captures d'écran des tests effectués.

---
*Disclaimer: Ce projet a été réalisé dans un but éducatif dans le cadre du programme Future Interns. Toutes les activités ont été menées de manière éthique.*
