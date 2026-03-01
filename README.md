# RunnEep - Deine Lauf-App

## Beschreibung
RunnEep ist eine deutsche Lauf-App mit folgenden Features:
- 🏃‍♂️ GPS-Tracking für Läufe
- 📊 Distanz, Geschwindigkeit und Tempo-Anzeige
- 🔥 Google Login mit Firebase Integration
- 📱 Responsive Design für mobile Geräte
- 💾 Workout-Verlauf und Statistiken
- 🏆 Persönliche Rekorde

## Web App
Die Web-App kann direkt im Browser geöffnet werden:
1. Öffne `index.html` in einem modernen Browser
2. Melde dich mit deinem Google-Konto an
3. Beginne deinen ersten Lauf!

## Firebase Konfiguration
Bevor du die App verwendest, aktualisiere die Firebase-Konfiguration in `index.html`:

```javascript
const firebaseConfig = {
    apiKey: "DEINE_API_KEY",
    authDomain: "DEIN_AUTH_DOMAIN",
    projectId: "DEIN_PROJECT_ID",
    storageBucket: "DEIN_STORAGE_BUCKET",
    messagingSenderId: "DEIN_SENDER_ID",
    appId: "DEINE_APP_ID"
};
```

## APK Build
Um die Android APK zu erstellen:

1. Stelle sicher, dass Node.js und npm installiert sind
2. Führe aus: `python build_web_apk.py`
3. Die APK wird als `RunnEep.apk` gespeichert

## Vercel Deployment
Für die Bereitstellung auf Vercel:

1. Lade alle Dateien in ein Vercel-Projekt hoch
2. Stelle sicher, dass `index.html` als Startseite konfiguriert ist
3. Firebase muss für die Domain whitelistet sein

## Benötigte Berechtigungen
- 📍 GPS-Standort (für Tracking)
- 🌐 Internet (für Firebase)
- 💾 Speicher (für Offline-Daten)

## Technologie-Stack
- HTML5, CSS3, JavaScript
- Firebase Authentication & Firestore
- Apache Cordova (für APK)
- Progressive Web App (PWA)

## Support
Bei Problemen oder Fragen, kontaktiere den Support.
