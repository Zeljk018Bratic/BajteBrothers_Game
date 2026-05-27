# 🎮 BajteBrothers – Rescue Mission

Akcijska rescue igrica za djecu — **spasi životinje od Trapavka, pobijedi se, postani heroj!** 🦸

> *"BajteBrothers ne čine ništa iz osobne koristi — samo pomažu!"* ❤️

---

## 🚀 Kako igrati

### 📱 Bez instalacije — direktno u browseru!
Otvori **`index.html`** — nema potrebe za App Storeom ili kompleksnom instalacijom.

✅ Radi na: **iPhone** | **Android** | **Tablet** | **Laptop** | **Desktop**

### ⌨️ Upravljanje

| Uređaj | Kretanje | Akcija |
|--------|----------|--------|
| **📱 Mobitel/Tablet** | Joystick (lijevo dolje) | Gumb ⚡ (desno dolje) |
| **⌨️ Tastatura** | WASD ili ↑↓←→ | Razmak = ⚡ · E = 🏪 |

---

## 🎯 Cilj igre

1. **Pronađi Trapavka** — villain koji sprema trikove
2. **Pritisni ⚡** — ponizi ga ili ga zasmiješi
3. **Spasi životinju** — dotrči do kaveza, otključaj, spasi!
4. **Skupljaj resurse:**
   - ⛽ **Gorivo** (35% po pickupu)
   - ⭐ **Zvjezdice** (za Shop)
5. **Prođi sve nivoe** — kupi nadogradnje, postani neporaziv!

---

## 🆕 Heroji (verzija 3.0)

### 🚜 Alex — Najbrži Bager
- **Brzina:** 92% 🔥
- **Gorivo:** 52% normale
- **Emoji:** 🚜
- **Specijalizacija:** Brzina je sve!

### 🏗️ Kevin — Ekonomičan Majstor
- **Brzina:** 58%
- **Gorivo:** 92% (najnižja potrošnja!)
- **Emoji:** 🏗️
- **Specijalizacija:** Endurance mode

### 🚛 Mia — Vidi Skrivene Staze
- **Brzina:** 72% (balans)
- **Gorivo:** 72% (balans)
- **Emoji:** 🚛
- **Specijalizacija:** All-rounder

### 🛻 Lara — Noćna Vozačica ⭐ **NOVA**
- **Brzina:** 80% (brza!)
- **Gorivo:** 65%
- **Emoji:** 🛻
- **Specijalizacija:** 
  - ✨ **NIVO 7 — Larinina Noć!** 🌙
  - Ekstra zvjezdice za bonus
  - Brža u mračnom okruženju

### ⚡ Nova — Elektri-Heroj ⚡ **NOVA**
- **Brzina:** 85% (2. najbrža!)
- **Gorivo:** 78% (ekonomična)
- **Emoji:** ⚡
- **Specijalizacija:**
  - **Munja-brzina** — akcija kao struja
  - Električna energija za ekstreme
  - Teorijski best all-around heroj

---

## 📊 7 Nivoa Igre

| Nivo | Naziv | Emoji | Trik | Životinja |
|------|-------|-------|------|-----------|
| 1 | 🌲 Šuma | 🐺 | Banana | Vuk |
| 2 | ⛰️ Planina | 🦌 | Snowman | Jelen |
| 3 | 🏙️ Grad | 🦅 | Bucket | Orao |
| 4 | 💧 Rijeka | 🐢 | Bubble | Kornjača |
| 5 | 🏜️ Oaza | 🦜 | Echo | Ptica |
| 6 | 👶 Finale | 👶 | Chase | Dijete (SUPER QUEST!) |
| **7** | **🌙 Larinina Noć** | **🔦** | **Night** | **SVE ŽIVOTINJE** ✨ |

**Nivo 7** je dostupan **SAMO AKO ODABEREŠ LARU!** 💜

---

## 🛒 Shop Sustav

Skupljaj ⭐ zvjezdice i kupi nadogradnje za svoju misiju:

| Item | Cijena | Efekt |
|------|--------|-------|
| 🔑 Zlatni Ključ | 50 ⭐ | Odmah otvara kavez — bez trika! |
| 🧲 Super Magnet | 80 ⭐ | Privlači gorivo i zvjezdice iz daljine |
| 🚀 Turbo Bager | 200 ⭐ | Brzina +40% (samo Alex) |
| 🛡️ Bajte Shield | 120 ⭐ | Gorivo teče 50% sporije |

---

## 📁 Struktura Projekta

```
BajteBrothers_Game/
├── index.html              ← 🎮 IGRICA (OTVORI OVO!)
├── manifest.json           ← PWA manifest (instalacija)
├── sw.js                   ← Service Worker (offline)
├── slika1.jpg              ← Intro slika
├── slika2.jpeg             ← Završni ekran
├── README.md               ← Ovdje si (dokumentacija)
└── Start of The Game - All Files Backup/
    └── (starije verzije i materijali)
```

---

## 📱 Instalacija na Home Screen

### 🍎 iPhone (Safari)

1. Otvori `index.html` u **Safari** browseru
2. Tap na **Dijeli** → **Dodaj na početni zaslon**
3. Igrica se otvara kao prava aplikacija! 🎉

### 🤖 Android (Chrome)

1. Otvori stranicu u **Chrome** aplikaciji
2. Tap na **⋮ (tri točke)** → **Dodaj na početni zaslon**
3. Ili čekaj Chrome bannera za instalaciju
4. Igrica je kao pravi app! 🚀

---

## 🔧 PWA & Offline Podrška (verzija 3.0)

### ✅ Service Worker
- **Datoteka:** `sw.js`
- **Funkcjonira:** Cache-first strategija za lokalne datoteke
- **Rezultat:** Igra radi **offline** nakon prvog učitavanja!

### ✅ Web App Manifest
- **Datoteka:** `manifest.json`
- **Funkcja:** Registracija kao PWA
- **Sadržaj:** Naziv, ikone, orientacija (landscape), boja teme

### ✅ Service Worker Registracija
- Automatski se registrira u `index.html`
- Ako nema interneta — koristi keš verziju
- Sinkronizira se čim se ponovo poveže!

---

## 🎨 Vizualni Elementi

### 🎜 Audio & Sound Effects
- 🔊 Engine zvuk (Motor bager-a)
- 🎵 Mission Ambience background
- 🎶 Collect zvuk (zvjezdice, gorivo)
- 🔔 Ding zvuk (level complete)
- 🎙️ Mission Cheer (voicelike motivacijske poruke)
- ⚡ Heroj-specifični zvukovi

### ✨ Vizualni Efekti
- Pulsiranje levela i kaveza
- Animirani čestice (exhaust, trail)
- Rasvjeta s osvjetljenjem
- Color-coded likovi po broji
- Sjajni naslovi s text-shadow efektem

### 📊 HUD Prikaz
- ⭐ Zvjezdice (gornji desni kut)
- 📍 Nivo & najbolja postignuća
- ⛽ Gorivo bar (realno vrijeme)
- 🎯 Status heroja
- 💜 Merge/Bonusi (Lara special)

---

## 🆕 Poboljšanja (verzija 3.0)

✅ **Novo:**
- 🌙 **Larinina Noć** — Level 7 za Laru sa posebnom temom
- ⚡ **Nova** — Elektri-heroj s maksimalnom brzinom
- 💜 **Larinina Specijalizacija** — Zvjezdice bonus za poseban nivo
- 🔌 **Offline PWA** — Kompletan Service Worker
- 🌐 **manifest.json** — Pravi web app

✅ **Iz Verzije 2.0:**
- 📱 Touch joystick upravljanje
- ⌨️ Keyboard podrška (WASD, Razmak, E)
- 🎵 Dinamički sound efekti
- 🛒 Shop sustav sa Zvjezdica ekonomijom
- 🏪 4 Shop item-a (Ključ, Magnet, Turbo, Shield)
- 🎮 5 nivoa + Finale
- 🌍 Multi-map teme (forest, snow, city, dark)
- 📊 Napredak sa localStorage
- 🎨 Animirani intro & završni ekrani
- 📱 Full mobile responsive design
- 🎯 Vibracijski feedback na mobitelu

---

## 🎮 Kako Igranje Funkcionira

### Game Loop
```
1. Odaberi heroja (Alex, Kevin, Mia, Lara, Nova)
2. Igraj nivo (1-6 dostupni za sve, 7 samo za Laru)
3. Skupljaj ⭐ zvjezdice
4. Pobijedi Trapavka
5. Spasi životinju
6. Level Complete → Nagradu ⭐
7. Kupi shop nadogradnje
8. Napreduj na sljedeći nivo
9. Repeat dok ne finaliziraš sve nivoe!
```

### Scoring
- **Pobijediti Trapavka:** +10 ⭐
- **Spasiti životinju:** +15 ⭐
- **Bonus (brz level):** +5-10 ⭐
- **Lara nivo 7 bonus:** +25 ⭐

---

## 🎯 Igranje Savjeti

1. **Biranj heroja:** 
   - Želiš brzinu? → **Alex** ili **Nova** ⚡
   - Želiš endurance? → **Kevin** 💪
   - Balans? → **Mia** ✨
   - Poseban nivo? → **Lara** 🌙

2. **Shop prioriteti:**
   - Prvo kupi 🔑 **Ključ** (50 ⭐) — odmah otvara kavez
   - Zatim 🧲 **Magnet** (80 ⭐) — lakše skupljanje
   - 🛡️ **Shield** (120 ⭐) — za teže nivoe
   - 🚀 **Turbo** (200 ⭐) — endgame flex

3. **Strategija:**
   - Skupljaj **gorivo** PRVO — bez goriva, game over!
   - Izbjegavaj **Trapavka** dok ne pritisnešš ⚡
   - Koristi **joystick** za precizno kretanje
   - Pritisni ⚡ blizu **kaveza** da oslobodiš životinju

---

## 🌟 Posebnosti po Heroju

### 🚜 Alex Trik
- Maxspeed: 4.4 (NAJBRŽI!)
- Turbo 🚀 ga čini neporazivim (4.4 × 1.4 = 6.16!)

### 🏗️ Kevin Trik
- Fuel economy: 0.72× (pije malo!)
- Shield 🛡️ ga čini tankim (0.72 × 0.5 = 0.36× potrošnja!)

### 🚛 Mia Trik
- Balans između brzine i goriva
- Odličan za početnike

### 🛻 Lara Trik
- **LEVEL 7** — samo za nju! 🌙
- Extra zvjezdica bonus na specijalnom nivou
- Brža na noći (special mechanic je moguć)

### ⚡ Nova Trik
- Brzina 4.1 + visoki acceleration (0.35)
- Teža kontrola ali najbrža!
- "Elektri" tema sa #00bfff + #ffff00 bojama

---

## 💻 Tehnologije

- **HTML5** — Semantic markup, PWA meta tagovi
- **CSS3** — Flexbox, gradijenti, animacije, responsive
- **Canvas API** — Game rendering u realnom vremenu
- **Web Audio API** — Dinamički zvuk i music
- **Service Worker** — Offline podrška
- **LocalStorage** — Persistentni napredak
- **Touch API** — Mobile joystick i gestures

---

## 📝 Licence & Atribucije

**Autor:** Željko Bratić & BajteBrothers Tim ❤️

Igrica je **open source** — slobodno forkiraj, doprinesi, ili koristi kao inspiraciju za svoje projekte!

---

## 🤝 Doprinosi

Nešto bi moglo biti bolje? Otvori **Issue** ili **Pull Request** na GitHubu:

👉 `Zeljk018Bratic/BajteBrothers_Game`

---

## 📞 Kontakt & Podrška

- 🐙 **GitHub:** [@Zeljk018Bratic](https://github.com/Zeljk018Bratic)
- 💬 **Bug Report:** Issue na repou
- 🎮 **Feedback:** Welcome!

---

## ✨ Što Je Novo (verzija 3.0)

```
🎉 LEVEL 7 — Larinina Noć (Samo Lara!)
⚡ NOVA — Elektri-bager (Nova postava heroja)
🔌 SERVICE WORKER — Kompletan offline mod
🌐 PWA REGISTRACIJA — Instalacija na Home Screen
💜 LARA SPECIJALIZACIJA — Zvjezdica bonus
```

---

## 🎮 Zašto Je Ovo Igrica?

**"BajteBrothers ne čine ništa iz osobne koristi — samo pomažu!"**

Ova igrica uči djecu:
- 🤝 **Prijateljstvo** — Alex & Kevin su najbolji prijatelji
- 💪 **Kuraj** — Spašavatibu životinje od zlog Trapavka
- 💰 **Upravljanje resursima** — Gorivo & zvjezdice
- 🧠 **Problem solving** — Različiti trikovi po nivou
- ♥️ **Dobrota** — Tema je spašavanje, ne pljačka

---

**Igraj sada! Otvori `index.html` u svom browseru.** 🚀

**Sretno u misiiji! BajteBrothers te čeka!** 💜⚡🚜
