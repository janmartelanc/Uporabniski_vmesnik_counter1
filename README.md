# Razvoj mobilnih aplikacij - Naloga 3: HelloConstraint (Aplikacija Counter / Števec)

Aplikacija je interaktivni števec za naprave Android, ki uporabniku omogoča spremljanje števila klikov, vizualno opozarjanje na parnost števila ter ponastavitev vrednosti z dinamičnim spreminjanjem barvnih stanj elementov.

---

## Kaj aplikacija dela in kako deluje?

### 1. Prikaz števca in začetno stanje
* Ob zagonu aplikacije se na desni strani zaslona prikaže veliko rumeno polje z začetno vrednostjo **0**.
* Na levi strani so navpično razporejeni trije gumbi: **Toast**, **Zero** in **Count**.
* Gumb **Zero** (ponastavitev) je na začetku neaktiven in obarvan **sivo**, saj je števec že na ničli.

### 2. Štetje in dinamično spreminjanje barv (Gumb "Count")
* **Povečevanje števila:** Ob vsakem pritisku na gumb **Count** se številka v rumenem polju poveča za +1 (npr. 1, 2, 3 ...).
* **Parnost števila:** Gumb **Count** sproti preverja, ali je trenutno število sodo ali liho, ter glede na to spreminja svojo barvo ozadja (vizualni signal parnosti).
* **Aktivacija gumba Zero:** Ko se števec poveča nad 0, gumb **Zero** spremeni svojo barvo iz sive v opazno barvo. S tem uporabniku jasno nakaže, da je sedaj mogoče števec ponastaviti.

### 3. Ponastavitev števca (Gumb "Zero")
* Ob pritisku na gumb **Zero** se vrednost števca takoj vrne na **0**.

### 4. Prikaz obvestila (Gumb "Toast")
* Ob pritisku na gumb **Toast** se na dnu zaslona prikaže kratko skočno obvestilo (Toast sporočilo) s trenutno vrednostjo števca ali pozdravnim besedilom.

### 5. Prilagajanje zaslonu in orientaciji
* **Ležeči način (Landscape) in tablice:** Ko uporabnik obrne telefon v ležeči položaj ali aplikacijo odpre na večjem zaslonu (tablici), se postavitev gumbov in rumenega polja samodejno prilagodi dimenzijam zaslona, tako da so vsi trije gumbi in števec vedno jasno vidni in enostavno dostopni.
* <img width="250" alt="image" src="https://github.com/user-attachments/assets/5b3cdc63-9d90-4acc-8278-322863ab0524" />

