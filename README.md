
# 🧬 Morphē Prompt Composer – Demo Edition

Ein modularer Prompt-Baukasten zur Erstellung von KI-kompatiblen, cineastischen Eingabetexten im Stil des Ritualistic Biopunk-Kanons.

## 🚀 Features
- Modularer Prompt-Builder (Kamera, Licht, Stil, Render-Modul)
- Presets: z. B. „Architekt“, „Klinge“
- Verlauf (localStorage)
- Export als .txt
- PWA-fähig: Offline-Nutzung & installierbar auf Mobilgeräten
- GitHub Actions: Automatischer Vercel-Deploy

---

## 🛠️ Lokales Setup

### 📦 Voraussetzungen
- Node.js (empfohlen: v18+)
- npm

### 🔧 Installation
```bash
npm install
npm start
```

Die App läuft nun unter `http://localhost:3000`.

---

## 🌍 Deployment auf Vercel

1. Repository auf GitHub erstellen (z. B. `morpheus-prompt-composer`)
2. ZIP entpacken und Code hochladen
3. Gehe zu [https://vercel.com/new](https://vercel.com/new) und verknüpfe dein GitHub-Konto
4. Wähle dein Repository und bestätige Deployment

**Vercel erkennt automatisch:**
- React-Projekt
- Public-Ordner für statische Inhalte
- Service Worker / manifest.json für PWA

---

## 🔁 GitHub Actions Setup (optional)

Für automatisches Deployment bei jedem Commit:

1. Füge unter `Settings → Secrets → Actions` die folgenden Secrets ein:
   - `VERCEL_TOKEN`: Erstellbar unter [Vercel Tokens](https://vercel.com/account/tokens)
   - `VERCEL_ORG_ID`: Organisation-ID von deinem Vercel-Profil
   - `VERCEL_PROJECT_ID`: Projekt-ID findest du unter „Settings → General“ deines Projekts
2. Stelle sicher, dass `.github/workflows/deploy.yml` vorhanden ist

### ✅ Ergebnis
Nach jedem Push auf `main` oder `master` wird deine App neu deployed.

---

## 📱 PWA Features
- `manifest.json` und `sw.js` enthalten
- Automatische Installation auf mobilen Geräten möglich
- Offline-fähig durch Service Worker

---

## 📷 Beispiel-Presets

| Preset     | Merkmale |
|------------|----------|
| Architekt  | Cinematic, Chiaroscuro, Giger, 8K |
| Klinge     | Shallow DOF, God Rays, Beksiński |

---

🧠 **Inspirationen:** H.R. Giger, Pharmakologie, Voodoo-Tech, Sakrale Kybernetik  
👁️‍🗨️ Entwickelt für experimentelle KI-Ästhetik und kreative Weltbildung
