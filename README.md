# Poker Chart Webapp 1.03

Interaktív póker chart megjelenítő webapp, amely képes kezelni és megjeleníteni a Holdem Resources Calculatorból (HRC) exportált range-eket.

## Főbb funkciók

- HRC .json fájlok importálása és feldolgozása
- Interaktív póker chart megjelenítés
- Dinamikus, Floptimal-stílusú navigáció
- Pozíciók közötti lépkedés
- Különböző akciók megjelenítése és kiválasztása

## Technikai információk

A webapplikáció a következő technológiákkal készült:

- Next.js 15.2.4
- React
- Tailwind CSS
- Framer Motion
- Zustand (state management)

## Változások az 1.03 verzióban

- Javítva az ActionBar pozíció kezelése
- Javítva a 0 értékű node ID-k feldolgozása
- Hozzáadott hibakeresési információk a könnyebb fejlesztéshez
- Részletes naplózás a navigációs történet kezeléséhez

## Indítás fejlesztői módban

```bash
npm run dev
```

A webapplikáció ezután elérhető a http://localhost:3000 címen.