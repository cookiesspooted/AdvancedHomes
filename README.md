# AdvancedHomes V1.0 🏠

AdvancedHomes est un plugin Minecraft pour serveurs Paper 1.20.4+ qui permet aux joueurs de créer, gérer et utiliser plusieurs homes avec des fonctionnalités avancées (GUI, cooldowns, homes publics/privés/partagés, etc).

---

## ✨ Fonctionnalités

- ✅ `/sethome <nom>` — Définit un home
- ✅ Options : `--public`, `--private`, `--shared <joueur>`
- ✅ `/home <nom>` — Se téléporte à un home
- ✅ Accès aux homes publics ou partagés d'autres joueurs
- ✅ `/delhome <nom>` — Supprime un home
- ✅ `/homes` — Liste interactive (GUI) ou texte de vos homes
- ✅ `/back` — Retourne à votre dernière position
- ✅ Limites de homes configurables par permission
- ✅ Cooldown & warmup configurables
- ✅ Multi-monde
- ✅ Sauvegarde dans `homes.yml`
- ✅ Permissions modulables

---

## 📦 Installation

1. Télécharge le fichier `.jar` compilé (ou build le projet avec Gradle).
2. Place le `.jar` dans le dossier `/plugins/` de ton serveur Paper.
3. Redémarre le serveur.
4. Modifie le fichier `config.yml` si besoin.

---

## ⚙️ Configuration (`config.yml`)

```yaml
settings:
  defaultHomesLimit: 1
  teleportWarmupSeconds: 5
  teleportCooldownSeconds: 30
  enableBackOnDeath: true
  useGUI: true
