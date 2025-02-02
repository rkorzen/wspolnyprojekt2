# wspolnyprojekt2

Celem projektu jest nauka współpracy w zespole w ramach projektu / repozytorium na github.

## Podstawowe komend git:

git status
git add .
git commit -m "commit message"
git push origin main

## Podstawowe komendy github:

git clone <url-repo>


# proba wypchniecia przy niezgodnej hist

Przy próbie wypchnięcia zmian do repozytorium, gdy historia commitów jest niezgodna z repozytorium mamy kilka opcji:

- git push --force - zmienia historię commitów na serwerze

- git pull origin <branch> - pobiera najnowszą historię z repozytorium i stara się zmergować zmiany
   - rozwiązanie konfliktów:
      - manualne rozwiązanie konfliktów w plikach
      - accept current change - przyjmuje zmiany z HEAD
      - accept incoming change - przyjmuje zmiany z repozytorium
      - accept both changes - przyjmuje zmiany z HEAD i repozytorium
- git pull origin --rebase - pobiera najnowszą historię z repozytorium i stara się zmergować zmiany
   - rozwiązanie konfliktów:
      - manualne rozwiązanie konfliktów w plikach
      - accept current change - przyjmuje zmiany z HEAD
      - accept incoming change - przyjmuje zmiany z repozytorium
      - accept both changes - przyjmuje zmiany z HEAD i repozytorium

