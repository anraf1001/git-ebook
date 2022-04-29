# Podstawowe użycie gita
## Sklonowanie repozytorium
Jeśli chcemy wprowadzić zmiany w repozytorium na naszym komputerze, w pierwszej kolejności musimy sklonować repozytorium (stworzyć jego lokalną kopię).
Do tego celu służy komenda:
```
git clone <link_do_repozytorium>
```
Link możemy odnaleźć klikają na zielony przycisk `Clone` na stronie głównej naszego repozytorium.
![Link do repozytorium](github_url.png)

Po pobraniu repozytorium na nasz komputer, przechodzimy do folderu, w który się ono znajduje (nazwa folderu jest taka jak nazwa repozytorium). Przykład:
```
cd cpp-fundamentals/
```

## Wybranie odpowiedniej gałęzi
Chcąc wprowadzić zmiany w implementacji zadania domowego powinniśmy przełączyć się na odpowiednią dla tego niego gałąź.
Do zmiany gałęzi służy komenda:
```
git checkout <nazwa_gałęzi>
```
np. chcąc wprowadzić zmiany w zadaniu `fibonacci` powinniśmy przełączyć się na gałąź o tej samej nazwie:
```
git checkout fibonacci
```
Na wyjściu otrzymamy komunikat informujący nas na jaką gałąź się przełączyliśmy:
```
branch 'fibonacci' set up to track 'origin/fibonacci'.
Switched to a new branch 'fibonacci'
```

W każdym momencie możemy też sprawdzić aktualną gałąź korzystając z polecenia `git branch`.
Aktualna gałąź zostanie oznaczona za pomocą `*`.
```
* fibonacci
  main
```
