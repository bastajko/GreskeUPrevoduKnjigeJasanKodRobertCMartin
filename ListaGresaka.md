# Kratka lista

| # | Strana | Mesto na strani | Greška | Prepravka | Objašnjenje |
|---|--------|----------------|--------|-----------|-------------|
| [1](#1) | xi     | Poglavlje 16 | ~~SerijalDate~~ | **SerialDate** | Greška u nazivu klase; treba koristiti ispravan naziv klase. |
| [2](#2) | 16     | Prvi primeri koda na strani | int ~~minutedTimeInDais~~; int ~~fileAgeInDais~~; | int **minutedTimeInDays**; **int fileAgeInDays;**  | Reč "spisak" se ne koristi u programerskim krugovima; ispravno je navesti tačnu strukturu podataka kao "lista". |
| [3](#3) | 16     | Ispod primera koda funkcije `getThem` | ~~spisak~~ nizova | **lista** nizova | Reč "spisak" se ne koristi u programerskim krugovima; ispravno je navesti tačnu strukturu podataka kao "lista". |
| [4](#4) | 17     | Primeri koda na vrhu i sredini strane | ~~nova~~ ArrayList<int[]>(); | **new** ArrayList<int[]>(); | Kod ne treba da se prevodi; dva puta je korišćena reč "nova" umesto `new`. |
| [5](#1) | 271     | Naslov | ~~SerijalDate~~ | **SerialDate** | Greška u nazivu klase; treba koristiti ispravan naziv klase. |


---
# Detaljan opis

Strana xi Sadrzaj Poglavlje 16 Refaktorisanje klase SerijalDate 271 treba da bude SerialDate 2. Strana 16 Ispod primera koda funkcije getThem nalazi se tekst koji spominje spisak nizova, a zapravo se ne misli na spisak nego na vrstu kolekcije tj. tacno definisanu strukturu podataka, te je jedino ispravno napisati lista nizova jer se reč spisak nikada ne koristi u programerskim krugovima. 3. Strana 17 U primerima koda na vrhu i u sredini strane dva puta je preveden kod. Kod ne bi smeo da bude podlozan prevodu. Dva puta je umesto kljucne reci new iskoriscena prevedena rec "nova", te smo dobili nova ArrayList<int[]>();

## <a name="1"></a>1. Strana xi, SerijalPrint
   - Ne treba prevoditi imena klasa. Klasa SerijalPrint ne postoji i kod se neće kompajlirati zbog tog dodatnog J. Ovo je sintaksički neispravno i nije u duhu jasnog koda, što i sama knjiga objašnjava.

## <a name="2"></a>2. Strana 16, Dais
   - Ovo može izgledati bezazleno, ali se nalazi na samom početku poglavlja koje se zove "Smislena imena". Autor objašnjava koliko je bitno držati se striktnih pravila imenovanja i biti jako oprezan. Ova greška totalno odudara od poruke knjige.

## <a name="3"></a>3. Strana 16, spiak nizova
   - Ovde se očigledno vidi da autor pravi referencu na kod u kome je definisana promenljiva tipa lista nizova. Lista je struktura podataka i ne može se prevesti rečju spisak.

## <a name="4"></a>4. Strana 17, nova ArrayList
   - Pored toga što ružno izgleda nova i ArrayList jedno pored drugog, ova greška bi izazvala nemogućnost kompajliranja koda.
   **new** je ključna reč u mnogim jezicima i ne može se prevoditi. Čak bi ispravno bilo napisati new ListaNizova, jer je dozvoljeno proizvoljno imenovati promenljive, ali sam stava da ni promenljive ne bi trebale biti prevođene. Generalno kod koji je napisao autor knjige ne treba dirati, jer je svaki detalj koji je naveo bitan, te bi se mogla izgubiti poenta.
