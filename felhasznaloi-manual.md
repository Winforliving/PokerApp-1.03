# Felhasználói Kézikönyv - Poker Chart Webapp 1.03

## Bevezető

A Poker Chart Webapp egy interaktív alkalmazás, amely lehetővé teszi a póker stratégiák vizualizálását és a különböző játékhelyzetekben való navigálást. Az alkalmazás képes a Holdem Resources Calculator (HRC) által exportált JSON fájlokat értelmezni és megjeleníteni.

## Funkciók

### 1. Fájl importálás

1. Kattints a "Fájl importálása" gombra
2. Válaszd ki a HRC által exportált JSON fájlt
3. Az alkalmazás automatikusan feldolgozza és megjeleníti a tartalmat

### 2. Pozíciók közötti navigáció

Az ActionBar segítségével különböző pozíciók között navigálhatsz:
- EP (Early Position)
- MP (Middle Position)
- LJ (Lojack)
- HJ (Hijack)
- CO (Cutoff)
- BU (Button)
- SB (Small Blind)
- BB (Big Blind)

### 3. Akciók kiválasztása

Minden pozícióhoz különböző akciók tartozhatnak:
- Fold
- Call
- Raise különböző összegekkel

Az akciógombokra kattintva kiválaszthatod a következő lépést, és az alkalmazás frissíti a megjelenített chart-ot az új helyzetnek megfelelően.

### 4. Chart értelmezése

A Chart Grid színkódolással mutatja a különböző póker kezek játszási gyakoriságát:
- Sötétebb szín: magasabb gyakoriság
- Világosabb szín: alacsonyabb gyakoriság
- Fehér: nem játszandó kéz

### 5. Fejlett navigáció

A navigációs történet követi a kiválasztott akciókat, és lehetővé teszi a visszalépést korábbi helyzetekhez.

## Hibaelhárítás

Ha problémát tapasztalsz:
1. Ellenőrizd, hogy a HRC fájl megfelelő formátumú-e
2. Próbáld újratölteni az oldalt
3. Ha a probléma továbbra is fennáll, jelentsd a fejlesztőknek

## Rendszerkövetelmények

- Modern webböngésző (Chrome, Firefox, Safari, Edge)
- Internetkapcsolat nem szükséges, az alkalmazás teljesen offline működik