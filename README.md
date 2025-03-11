# 📌RAG Multimodal avec Colpali et LangChain

### 📝 Description du Projet

Ce projet implémente un système de RAG (Retrieval-Augmented Generation) multimodal
utilisant **Colpali** comme retriever et **LangChain** pour l'orchestration des requêtes. 
L'objectif est de permettre la récupération et l'exploitation d'informations contenues dans des documents, y compris des images.

### Fonctionnalités

- Indexation de documents (PDF) avec ***Colpali***.

- Recherche de documents via un retriever basé sur ***Byaldi***.

- Génération de réponses contextuelles en utilisant Gemini via ***l'API de Google***.

- Interface utilisateur interactive grâce à ***Gradio***.

- Prise en charge de documents multimodaux (texte + images).

- Historique des conversations avec export en CSV.

### Pourquoi utiliser l'API Google ?

L'API Google (Gemini) a été utilisée pour le LLM en raison des **contraintes de mémoire** de
l'environnement (Google Colab). L'objectif à terme est de passer à un modèle open-source compatible avec les capacités matérielles disponibles.

### Utilisation

- **Uploader un document PDF** et créer un index.
- **Interagir avec le chatbot** en posant des questions sur le document indexé.
- **Exporter l'historique des conversations** pour analyse ultérieure.

### Améliorations futures

- Remplacement de l'API Google par un modèle open-source sur Hugging Face.
- Optimisation de l'indexation pour des performances accrues.
- Intégration d'autres types de documents multimodaux.






📌 *Projet en cours d'amélioration. Contributions et feedbacks bienvenus !*
