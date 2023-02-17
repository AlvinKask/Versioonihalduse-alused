# Versioonihalduse-alused

- Terminal (emulaator) - ilus värviline aken
- Käsurida (shell) - käsurida, mis kirjutab terminali teksti
#
### Visual Studio Code
- Hex converter add-on võib olla kasulik
#
### Windows Terminal (Microsoft Store)
- Leitav Windowsi otsinguaknas sõnaga "terminal"
# 
### Git (https://git-scm.com/download/win)
- Windows Explorer integration - ei ole vajalik (näiteks koduarvutis... parempoolne hiireklikk avab menüüs bash ja GUI valikud)
- Add a Git Bash profile to Windows Terminal
- Use Visual Studio Code as Git's default editor
- Override the default branch name for new repositories (main)
- Checkout as-is, commit as-is
# 
- Kasutame Terminali Git Bash seadistuses
- **~** tähendab kasutaja kodukausta
- **cd ...** - change directory liigub etteantud kausta
- **ls** või **dir** - list kuvab kaustas olevad failid
- **... --help** - kuvab etteantud käskluse abi
- **cd ..** - viib tagasi eelnevasse kataloogi
- **cd** - toob alati kasutaja kodukausta tagasi
- **mkdir ...** - loob kataloogi
- **cd D + Tab** - teeb soovitusi D tähega algavate kaustade kohta. Kui üks kaust ainult, siis teeb autocomplete
- **touch ...** - loob faili (näiteks touch hello.txt)
- **mv ...** - move/rename (mv hello.txt cool.md). Kaotab originaali ära
- **cp ...** - copy/paste. Töötab nagu mv aga jätab originaali alles
- **rm ...** - remove (failide kustutamiseks)
- **rm -r ...** - kustutab etteantud kausta ja selles olevad failid
- **rm dir ...** - remove (kaustade kustutamiseks)
- **pwd** - annab täispika hetkeaadressi
- **cat ...** - trükib välja etteantud faili sisu
- **grep ...** - failisisu otsing

# GIT KÄSKLUSED
- **git init** - tekitab kaustast git'ile mõeldud lisa (main)
- **code .** - avab visual studio code, hetkel aktiivses kataloogis

Markdown koodid (kasutatavad ka GitHub'is) - https://www.markdownguide.org/cheat-sheet/ - https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
- **git status** - aitab aru saada, mis hetkel Git'iga toimub
- **git add readme.md** - jälgib faili
- **git add (tärn).md** - jälgib .md faile
- **git add .** - jälgib kõiki faile aktiivses kataloogis
- **git add --help** - annab help faili
- **git commit -m "siia kirjuta kommentaar"** - "save game" hetkeolukorrast
- https://docs.github.com/en/get-started/getting-started-with-git/associating-text-editors-with-git
- **git config - global user.name "Alvin Kask"**
- **git config - global user.email "Alvin.Kask@tptlive.ee"**
- https://docs.github.com/en/get-started/getting-started-with-git/associating-text-editors-with-git
- **$ git config -global core.editor "code --wait"** - paneb visual studio code põhiliseks programmiks
- **git log** - abistav staatus
- **git checkout "unik kood"** - näitab, mis toimus eelmise commitiga
- **git checkout main** - läheb tagasi viimasesse commiti
# UUS GITHUB REPO "learngit"
- **git remote add origin https://github.com/AlvinKask/learngit.git**
- **git push -u origin main** - saadab masinast pilve
- **git clone** - viskab git projekti hetkel aktiivsesse kausta
- **git clone https://github.com/AlvinKask/learngit.git learngit2** - kloonib githubi kausta nimega learngit2
- **git pull** - toob pilvest info arvutisse
- **git branch** - näitab kõik harud ja kus me oleme
- **git checkout cool_branch** - paneb meid harusse
# Terminalis END akna paneb kinni "Q"
- **git merge cool_branch** - sulatab kõrvalharu peaharuga kokku**
- **git push --set-upstream origin cool_branch**
- **git add --p(b)atch**  - kui meil on palju muudatusi (commite)

- https://cbea.ms/git-commit/
- https://www.youtube.com/watch?v=qpdYRPL3SVE
