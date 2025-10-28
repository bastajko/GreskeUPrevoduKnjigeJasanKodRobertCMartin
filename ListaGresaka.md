# Kratka lista

| # | Strana | Mesto na strani | Greška | Prepravka | Objašnjenje |
|---|--------|----------------|--------|-----------|-------------|
| [1](#1) | xi     | Poglavlje 16 | ~~SerijalDate~~ | **SerialDate** | Greška u nazivu klase; treba koristiti ispravan naziv klase. |
| [2](#2) | 16     | Prvi primeri koda na strani | int ~~minutedTimeInDais~~; int ~~fileAgeInDais~~; | int **minutedTimeInDays**; **int fileAgeInDays;**  | Reč "spisak" se ne koristi u programerskim krugovima; ispravno je navesti tačnu strukturu podataka kao "lista". |
| [3](#3) | 16     | Ispod primera koda funkcije `getThem` | ~~spisak~~ nizova | **lista** nizova | Reč "spisak" se ne koristi u programerskim krugovima; ispravno je navesti tačnu strukturu podataka kao "lista". |
| [4](#4) | 17     | Primeri koda na vrhu i sredini strane | ~~nova~~ ArrayList<int[]>(); | **new** ArrayList<int[]>(); | Kod ne treba da se prevodi; dva puta je korišćena reč "nova" umesto `new`. |


---
# Detaljan opis

## <a name="1"></a>1. Strana xi, Sadržaj Poglavlje 16 
   - **Greška:** SerijalDate  
   - **Prepravka:** SerialDate  
   - **Objašnjenje:** Greška u nazivu klase; treba koristiti ispravan naziv klase.

## <a name="2"></a>2. Strana 16, Prvi primeri koda na strani
   - **Greška:** spisak nizova  
   - **Prepravka:** lista nizova  
   - **Objašnjenje:** Reč "spisak" se ne koristi u programerskim krugovima; ispravno je navesti tačnu strukturu podataka kao "lista".

## <a name="3"></a>3. Strana 16, Ispod primera koda funkcije `getThem`
   - **Greška:** spisak nizova  
   - **Prepravka:** lista nizova  
   - **Objašnjenje:** Reč "spisak" se ne koristi u programerskim krugovima; ispravno je navesti tačnu strukturu podataka kao "lista".

## <a name="4"></a>4. Strana 17, Primeri koda na vrhu i sredini strane
   - **Greška:** nova ArrayList<int[]>();  
   - **Prepravka:** new ArrayList<int[]>();  
   - **Objašnjenje:** Kod je pogrešno preveden; ključna reč `new` se ne prevodi; dva puta je korišćena reč ~~nova~~ umesto **new**.
