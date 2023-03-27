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
git checkout -b <name> - creaza, daca nu exista, ramura <name> si face switch pe ea direct
git merge <name_of_branch> - face merge intre ramura pe care esti si cea din <name_of_branch>. 
   Daca e o ramura directa, si nici in prima ramura (din care deriveaza si pe care se face merge ulterior) nu s-au mai facut schimbari, atunci merge-ul e numit "Fast-forword"
   Daca apar conflicte, nu se face merge-ul automat, ci se creaza un pseudo-branch (de ex:) master|MERGING, deschizi in editor si se vad variantele-diferentele; 
   alegi ce cod si de unde sa ramana, apoi faci add si commit, dupa care pseudo-branch-ul dispare si schimbarile sunt acum oficiale pe master (sau pe ramura pe care faci merge-ul) 
git --delete (sau, pe scurt, -d) <branch-name> - sterge ramura respectiva