# 🤖 AI Agent Chatbot - n8n, Groq & Typebot

Ce projet présente un **Agent IA conversationnel** intelligent conçu pour automatiser l'interaction client. Il utilise la puissance de calcul de **Groq** pour des réponses instantanées et **n8n** pour l'orchestration des flux.

---

## 🚀 Fonctionnalités
- **Intelligence Artificielle** : Intégration du modèle LLM via Groq pour une compréhension contextuelle.
- **Automatisation** : Workflow fluide géré par n8n (Webhooks, Logic, API).
- **Interface Interactive** : UI moderne et responsive construite avec Typebot.
- **Mémoire de session** : Capacité de retenir le contexte de la conversation.

## 🛠️ Stack Technique
- **n8n** : Orchestration du backend et automatisation.
- **Groq AI** : Moteur d'intelligence artificielle (LLM).
- **Typebot** : Interface de chat utilisateur.
- **Webhooks** : Communication entre le frontend et le backend.

## 📦 Installation & Utilisation
1. **n8n** : Importez le fichier `n8n_workflow.json` dans votre instance n8n.
2. **Typebot** : Importez le fichier `typebot_flow.json` sur l'interface Typebot.
3. **Configuration** : Ajoutez votre clé API Groq dans les paramètres du nœud AI sur n8n.
4. **Webhook** : Copiez l'URL du Webhook n8n et collez-la dans le bloc Webhook de Typebot.

---

## 🖼️ Aperçu du Workflow
<img width="2084" height="948" alt="Capture d’écran 2026-04-16 à 22 37 33" src="https://github.com/user-attachments/assets/ad6da8d9-5663-412b-b611-2d0215c5dd22" />

