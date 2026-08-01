# Projet : Assistant Vocal Intelligent et Automatisation Système (Projet J.A.R.V.I.S.)

## 💡 Le Concept
Une application d'assistant vocal personnel capable d'interagir en langage naturel, d'effectuer des recherches sur le web en temps réel et d'exécuter des actions d'automatisation complexes directement sur ton système d'exploitation (comme basculer d'un profil de travail à un profil de jeu en un mot).

---

## 🛠️ Fonctionnalités clés (MVP)
1. **Reconnaissance et Synthèse Vocale (STT/TTS) :** Écoute du microphone en continu ou sur mot-clé de déclenchement (*hotword*) et restitution vocale des réponses.
2. **Cerveau contextuel par IA (Function Calling) :** Utilisation d'un LLM couplé à une API de reconnaissance d'intentions pour comprendre les demandes de l'utilisateur et déclencher les bons scripts.
3. **Recherche Web en direct :** Capacité pour l'assistant d'interroger Internet pour récupérer des informations fraîches (météo, actualités, documentation).
4. **Automatisation Système ("Mode Jeu") :** Un moteur de scripts local capable de:
   * Fermer proprement ou de force les applications de travail en cours (ex: IDE, navigateurs, messageries).
   * Lancer instantanément les lanceurs de jeux et logiciels de divertissement (ex: Steam, Discord).

---

## 🚀 Pourquoi c'est top pour ton CV ?
* **Compétences en automatisation et administration système :** Manipulation des processus de l'OS (`psutil`, `subprocess`) pour interagir physiquement avec l'environnement de la machine.
* **Intégration d'IA avancée :** Mise en œuvre de concepts modernes de l'intelligence artificielle (gestion d'agents, *Tool/Function Calling*).
* **Architecture multi-domaines :** Fait le pont entre du code logiciel de haut niveau (IA, API) et des scripts système bas niveau (gestion des processus de l'ordinateur).

---

## 🎨 Pistes d'évolution (pour aller plus loin)
* **Exécution 100% locale :** Remplacer les API cloud par des modèles open-source exécutés en local (via **Ollama** pour le LLM et **Whisper** pour la voix) pour un assistant totalement privé et hors-ligne.
* **Interface visuelle holographique :** Créer une interface graphique futuriste (style HUD d'Ironman en HTML/CSS/Canvas) qui s'affiche sur un second écran pour visualiser l'activité de l'assistant en direct.