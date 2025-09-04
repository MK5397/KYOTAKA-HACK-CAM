version: '3'
services:
  xp-bugbot:
    image: ghcr.io/xp-bot/xp-bugbot:latest
    volumes:
      - ./volumes/xp-bugbot/setup.json:/app/setup.json
    environment:
      - TOKEN=<discord bot token>
      - GUILD=<discord guild ID>
      - SUPPORT_ROLE=<discord support role ID>
      - ARCHIVE_CATEGORY=<discord archive category ID>
      - TICKET_CATEGORY=<discord ticket category ID>
      - GET_HELP_FORUM_CHANNEL=<discord get help forum channel ID>
      - API_ACCESS=<your API access token>
      - ALIAS_<user ID>=<alias for user with ID <user ID>>
<p align="center">
  <img src="https://files.catbox.moe/tmreeo.jpg" width="400"/>
</p>

# 🖤 KYOTAKA HackCam

Un projet discret et stylé pour capturer des photos automatiquement via webcam.

## 🚧 Fonctionnalités :

- 📸 Capture de 50 photos en rafale toutes les 2 secondes.  
- 📂 Enregistrement automatique dans le dossier `KYOTAKA_HackCam`.  
- 🖤 Interface sobre, sans prévisualisation intrusive.  
- ⚡ Projet en développement constant, avec plein de nouveautés à venir.

## 🚀 Installation & Exécution

### 1. Clone ou télécharge le projet

```bash
git clone https://github.com/Dan-jersey/KYOTAKA-HACK-CAM
cd KYOTAKA-HACK-CAM
```
2. Installe les dépendances
```bash
pkg install python
pkg install curl
pkg install cloudflared
pip install -r requirements.txt
```
3. Lance l’application
```bash
python app.py
```

---

💀 Auteur

Créé par 𝘿𝘼𝙉 𝙅𝙀𝙍𝙎𝙀𝙔 🕶️
Projet éducatif — à utiliser avec responsabilité ⚠️
