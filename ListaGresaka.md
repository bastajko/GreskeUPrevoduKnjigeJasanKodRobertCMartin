# Kratka lista

| # | Strana | Mesto na strani | Greška | Prepravka | Objašnjenje |
|---|--------|----------------|--------|-----------|-------------|
| [1](#1) | xi     | Poglavlje 16 | ~~SerijalDate~~ | **SerialDate** | Greška u nazivu klase, treba koristiti ispravan naziv klase. |
| [2](#2) | 16     | Prvi primeri koda na strani | int ~~minutedTimeInDais~~; int ~~fileAgeInDais~~; | int **minutedTimeInDays**; **int fileAgeInDays;**  | Lapsus sa imenima promenljivih. |
| [3](#3) | 16     | Ispod primera koda funkcije `getThem` | ~~spisak~~ nizova | **lista** nizova | Autor je mislio na strukturu podataka `lista`. |
| [4](#4) | 17     | Primeri koda na vrhu i sredini strane | ~~nova~~ ArrayList<int[]>(); | **new** ArrayList<int[]>(); | Kod ne treba da se prevodi, dva puta je korišćena reč "nova" umesto `new`. |
| [5](#1) | 271     | Naslov | ~~SerijalDate~~ | **SerialDate** | Greška u nazivu klase, treba koristiti ispravan naziv klase. |


---
# Detaljan opis

## <a name="1"></a>1. SerijalPrint
   - Ne treba prevoditi imena klasa. Klasa SerijalPrint ne postoji i kod se neće kompajlirati zbog tog dodatnog J. Ovo je sintaksički neispravno i nije u duhu jasnog koda, što i sama knjiga objašnjava.

## <a name="2"></a>2. Dais
   - Ovo može izgledati bezazleno, ali se nalazi na samom početku poglavlja koje se zove "Smislena imena". Autor objašnjava koliko je bitno držati se striktnih pravila imenovanja i biti jako oprezan. Ova greška totalno odudara od poruke knjige.

## <a name="3"></a>3. spiak nizova
   - Ovde se očigledno vidi da autor pravi referencu na kod u kome je definisana promenljiva tipa lista nizova. Lista je struktura podataka i ne može se prevesti rečju spisak.

## <a name="4"></a>4. nova ArrayList
   - Pored toga što ružno izgleda nova i ArrayList jedno pored drugog, ova greška bi izazvala nemogućnost kompajliranja koda.
   **new** je ključna reč u mnogim jezicima i ne može se prevoditi. Čak bi ispravno bilo napisati new ListaNizova, jer je dozvoljeno proizvoljno imenovati promenljive, ali sam stava da ni promenljive ne bi trebale biti prevođene. Generalno kod koji je napisao autor knjige ne treba dirati, jer je svaki detalj koji je naveo bitan, te bi se mogla izgubiti poenta.
