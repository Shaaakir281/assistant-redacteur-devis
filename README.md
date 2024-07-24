# Assistant Rédacteur de Devis

Ce projet est un assistant virtuel capable de générer des devis basés sur les descriptions fournies par les utilisateurs. L'assistant utilise une base de données de clients et de produits pour produire des devis modifiables, en utilisant des outils comme OpenAI, ChromaDB, et Pydantic.

## Fonctionnalités

- **Extraction d'informations client et produit** : Utilisation de l'API OpenAI pour extraire et structurer les informations des descriptions fournies.
- **Base de données vectorielle** : Utilisation de ChromaDB pour gérer les embeddings de texte et effectuer des recherches par similarité.
- **Validation et formatage des données** : Utilisation de Pydantic pour valider les données et s'assurer qu'elles sont correctement formatées pour les devis.
- **Génération de devis** : Création automatique de devis dans un fichier Excel avec les détails des produits et des clients.

## Structure du Projet

1. **Import des bibliothèques nécessaires**
2. **Configuration de la clé API OpenAI**
3. **Définition des modèles de données avec Pydantic**
4. **Fonction de génération de contexte pour les requêtes**
5. **Création de la base de données des clients et des produits**
6. **Initialisation du patch Instructor**
7. **Génération de réponse et traitement des données**
8. **Mise à jour du devis dans le fichier Excel**

## Installation

Clonez ce dépôt et installez les dépendances :

```bash
git clone https://github.com/votre-utilisateur/assistant-redacteur-devis.git
cd assistant-redacteur-devis
pip install -r requirements.txt
```

## Utilisation

1. **Configurer la clé API OpenAI** : Ajoutez votre clé API OpenAI en tant que variable d'environnement ou modifiez le code pour l'inclure directement.
2. **Exécuter le notebook** : Suivez les étapes dans le notebook pour générer des devis à partir des données clients et produits.

## Auteur

Ce projet a été réalisé par [Fathi METALSI](https://www.linkedin.com/in/fathi-metalsi-328159124/). N'hésitez pas à me contacter pour toute question ou suggestion d'amélioration.

## Contribuer

Les contributions sont les bienvenues ! Veuillez soumettre une pull request ou ouvrir une issue pour discuter de changements.

## Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus d'informations.
