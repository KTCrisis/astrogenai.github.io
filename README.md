Github Pages Web AstroGenAI 🔮

AstroGenAI est une application de bureau et web qui utilise l'intelligence artificielle pour générer du contenu astrologique personnalisé, incluant des horoscopes textuels, des animations vidéo de constellations et des publications pour les réseaux sociaux.

## ✨ Fonctionnalités Principales

* **Génération d'Horoscopes** : Crée des horoscopes quotidiens pour les 12 signes du zodiaque en utilisant des modèles de langage avancés via Ollama.
* **Animations Vidéo IA** : Génère automatiquement des clips vidéo de constellations animées grâce à une intégration avec ComfyUI.
* **Montage Automatisé** : Assemble les clips vidéo avec des voix off (TTS) et des sous-titres synchronisés pour créer des vidéos prêtes à l'emploi.
* **Chat Astrologique** : Discutez avec un assistant IA spécialisé en astrologie pour poser des questions et obtenir des éclaircissements.
* **Upload Social** : Uploadez directement les vidéos générées sur YouTube et TikTok depuis l'application.
* **Calculs Astronomiques** : Intègre des calculs de positions planétaires réelles pour des horoscopes plus précis.

## 🛠️ Architecture Technique

* **Backend** : Serveur Flask (`main.py`) agissant comme une interface web et une API.
* **Génération de Texte** : Modèles de langage (Llama 3, Mistral) via Ollama.
* **Génération d'Image/Vidéo** : ComfyUI pour la création des animations.
* **Base de Données** : Pas de base de données, les fichiers sont gérés sur le système de fichiers.
* **Frontend** : Interface web simple en HTML, CSS et JavaScript.
