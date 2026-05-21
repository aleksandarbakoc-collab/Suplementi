# Sašin Tracker v4.0

Personalizovana web aplikacija za praćenje dnevnog uzimanja suplemenata i vitamina sa Firebase sinhronizacijom.

## 🎯 Funkcionalnosti

- **Dnevno praćenje** - Čekiraj uzete suplemente po kategorijama (jutro, doručak, glavni obrok, popodne, veče)
- **Firebase sinhronizacija** - Automatsko čuvanje podataka u cloud-u
- **Istorija uzimanja** - Pregled svih prethodnih dana sa statistikom
- **Laboratorijski nalazi** - Prikaz najnovijih nalaza i genetskog profila
- **Upozorenja** - Važne informacije o interakcijama između suplemenata
- **Predlozi** - Preporučeni dodatni suplementi sa prioritetima

## 📊 Kategorije suplemenata

- 🌅 **Jutro natašte** - TruNiagen (NR)
- 🍳 **Uz doručak** - B vitamini (B12, B6, B2, Folate)
- 🍽️ **Uz glavni obrok** - D3+K2, CoQ10, Omega-3, Vitamin E/C, Selen, Kreatin
- 🌞 **Tokom dana** - Magnezijum Citrate
- 🌙 **Veče** - 5-HTP, Taiwan Fungus, Crestor (Rx)

## 🔧 Tehnologije

- Vanilla JavaScript (ES6 modules)
- Firebase Firestore za sinhronizaciju podataka
- Responsive dizajn sa custom CSS
- Google Fonts (Space Mono, Unbounded)

## 🚀 Pokretanje

1. Otvori `index.html` u web pregledaču
2. Aplikacija automatski učitava podatke iz Firebase-a
3. Klikni na suplement da označiš da si ga uzeo
4. Podaci se automatski sinhronizuju

## 📱 Interfejs

- **DANAS** - Trenutni dan sa statistikom i napretkom
- **ISTORIJA** - Pregled prethodnih dana
- **NALAZI** - Laboratorijski rezultati i genetski profil
- **UPOZORENJA** - Važne informacije o interakcijama
- **PREDLOZI** - Dodatni suplementi sa prioritetima

## 📈 Statistika

- Uzeto / Ostalo / Ukupno za dan
- Streak - broj uzastopnih dana sa kompletnim uzimanjem
- Vizuelni progress bar


## 🔐 Firebase konfiguracija

Aplikacija koristi Firebase Firestore za čuvanje podataka. Konfiguracija je uključena u fajl.

---

**Verzija:** 4.0 — Firebase Sync  
**Jezik:** Srpski (latinica)
