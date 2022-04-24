# Jegyzetek

**A Note App elkészítésének a jegyzetei.**

## 2022.02.07.

### Teendők jövő szerdára
- NodeJS
- nodemon
- express
- mySQL module !

### Érdekesség
package.json-ban scripts:  
"dev": "nodemon index.js"

### Fontos

Password ne varchar típusú legyen. (Valószínűleg ASH vagy SHA.)

## 2022.02.02.

Nem feltétlenül kell email és felhasználónév is.  
Kulcsmező lehet id vagy az email vagy a felhasználónév.  
Viszont nem javasolt, hogy az legyen a kulcsmező, mert akkor többet nem lehet azt megváltoztatni.  
Valószínűleg kell legyen auto increment mint kulcsmező.  
Mellette lehet email cím.

## 2022.01.24.

Videó a jegyzethez: `2022-01-24-tanacsok.webm` Itt található:\
CL2122_E_13A_Projektmunka/Jegyzet App Projekt/Fájlok/note-app

### Adatbázis

Karakterszám: Max mennyi karakter. Jó ötlet lehet. Adatbázisban viszont valószínűleg nincsen szükség ezt tárolni, csa a frontenden, HA vissza szeretnénk jelezni a felhasználónak, hogy:
összesen hány karaktert írhat/még hány karakter van hátra.

"Mentes" tábla nem feltétlenül kell. Inkább menjenek ezek az "adatok_jegyzetekrol"-be.

- Pláne nem: Első mentés VAGY létrehozás
- Maximum: Utolsó mentés??? "Dokumentum utolsó mentésének az időpontja."

"Jegyzetek" jó csak áttenni az "Adatok_jegyzetekrol"-be. A "mentes"-t is.

Titkosítás.

1 tábla: téma/címkék.

### Ötletek

Topic: téma. Egyelőre lenyíló ablakból, előre hardcode-olt témákból kiválasztani. Később saját 1 (vagy több) címkét beírni.

Megosztás email címre. Ez ok. Max teljes név idővel. Email annak aki még nincsen regisztrálva.

Publikus jegyzetek: sokadik lépés.

Nyomtatás, export PDF-be:
talán

WORD feltöltés:
Nem valószínű. Sima szöveget írnak be az emberek. Nehéz lenne .docx-et konvertálni plaintext-re.

### Projekt

Fontossági sorrend:

1. Felhasználóknak saját, privát jegyzet.
2. Publikus jegyzetek.
3. Megosztás másokkal.
4. Kategória/témák/címkék.

## 2022.12.10.

awesome-note.com
super-duper-note.web.app

### Frontpage

awesome-note/super-duper-note

(Online) notes for ...

(Online) notesz...

profession/foglalkozás = {
developers 3 laptop
recruiters
couriers
teachers
everbody/anybody

fejlesztőknek
toborzóknak
futároknak
tanároknak
mindenkinek/bárkinek

recruiters/toborzók = Adél
teachers/tanárok = Eszter
}

Képek rólunk.
Kék, lila/pink/orange, piros, lila/pink/orange

Some public notes

| Peter B. | Girl 1. | Daniel H. | Girl 2. |

TOP LEFT - [Logo/app-text]
MIDDLE - [Search public notes]
RIGHT - [Register] [Login]

### User page

Left sidebar:

- Everything (extra)
- Just mine
- Shared (extra)
- Archived (extra)

### Extras

- Search notes
- Share notes

---

Text field autosave.
"Note saved" snackbar? "Autosave button?" (Tells user notes are autosaved.)