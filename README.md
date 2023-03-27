Learning Git version controll.

Pe scurt:
git --version -versiunea
git config (--global - pentru toate repository-urile) user.name "nume"
git config (-- global - petru toat repository-urile) user.email "email"
git init -initializeaza un folder ca repository
git add - adauga in stage-ing un fisier
git add --all (-A) - adauga in stage toate fisierele modificate (noi, modificate sau sterse)
git status - statusul fisierlor noi/modificate/sterse - sunt adaugate in stage sau nu (tracked/untracked)
git commit -m - neaparat trebuie sa contina un mesaj scurt, prin -m. Commit-urile sunt un fel de noduri -  puncte cheie in istoric
git status (--short) - statusul fisierelor.
Pt --short:
      ?? - Untracked files
      A - Files added to stage
      M - Modified files
      D - Deleted files
git commit -a -m "mesaj"  - se poate face commit si fara staging, dar nu e indicat
git <comanda> -help - toate delatiile legate de comanda
git help --all - toate comenzile git
git branch <name> - creaza un branch (o ramura noua)
git branch  - fara nimic - afiseaza toate ramurile, cu * in dreptul ramurei pe care suntem
git checkout <name> - schimba ramura actuala, care va deveni acum <name>