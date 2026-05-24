# Samurai Slash ⚔️

Tek oyunculu samurai aksiyon oyunu. Dalga dalga gelen düşmanları kes, hayatta kal.

**4 Karakter:** Kage · Kensei · Hayabusa · Oni  
**Platform:** Web (HTML5) · Android APK · iOS IPA

## Kontroller

| Platform | Hareket | Saldırı | Dash |
|----------|---------|---------|------|
| Masaüstü | Ok tuşları / WASD | Mouse sürükle | Space / Shift |
| Mobil | D-pad | Ekranda sürükle | Sağ alt buton |

## Kurulum

```bash
npm install
```

### Web (tarayıcıda oyna)
```bash
npm run dev
# → http://localhost:3000
```

### Android APK
```bash
npx cap add android
npx cap sync
npx cap open android   # Android Studio açılır → Build APK
```

### iOS IPA
```bash
npx cap add ios
npx cap sync
npx cap open ios       # Xcode açılır (Mac gerekli)
```

## Proje Yapısı

```
samurai-slash/
├── www/
│   └── index.html       ← Oyunun tamamı (tek dosya)
├── capacitor.config.json
├── package.json
└── README.md
```
