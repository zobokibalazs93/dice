# GIT verziókezelés

- helyi REPO inicializálása: 
    > git init
- ellenőrzése
    > git status
- előkészíjük a commitolásra, feltesszük a színpadra(Stage), indexelés történik:
    > git add .

    > git status
- az új verzió létrehozása:
    > git commit -m "First commit"(helyi repo inicializálása)
- távoli repo létrehozása (a GitHub oldalon):
- összekapcsolajuk a távolni repo-t a helyivel:
    > git remote add origin https://token@github.com/zobokibalazs93/TestRepo.git
- kiválasztjuk az ágat (branch), a távoli repoban: 
    > git push -u origin master (ez csak legelső alkalommal)

    > git push ( a további alkalmakkor)
- Token használata (ezzel azonosítjuk magunkat a Github -on)

## Publikálás

- a publikálandó file neve index.html
- settings > pages > branch non-ból kiválasztottuk a master -t > save
- action-ban látható a publikálási folyamat
