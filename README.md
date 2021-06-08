# Kolokwium:

1. Utworzyć **publiczne** repozytorium o nazwie "Kolokwium"
2. Wewnątrz repozytorium dodać plik `index.html` utworzony na podstawie pliku `index_start.html`
3. Wykonać pierwszy commit o nazwie `Initial commit` i otagować `v0.0.1`
4. Do html'a, a konkretniej `<div id="app">` dopisać `div` (potocznie nazwę go "cell") taki, że:
    - ma mieć klasę `cell`
    - wysokość i szerokość 50px
    - tło pomarańczowe
    - obramowanie 1px linia ciągła szara
    - zaokrąglenie brzegów 10px
    - margines dolny i prawy 10px
5. Wykonać commit o nazwie `Cell`, otagować `v0.0.2` oraz wykonać `push` na github
6. Do boxa wpisać cyfrę `1` w ten sposób aby była idealnie na środku przy wykorzystaniu stylu `display: flex`
7. Wykonać commit o nazwie `Cyfra`, otagować `v0.0.3` oraz wykonać `push` na github
8. Dopisać do `data` VueJS'owego dwie zmienne: `rows`, `columns` i nadać im początkowe wartości `10`
9. Za pomocą `v-for` VueJS'owego - utworzyć idealny kwadrat o wymiarach rows * columns zbudowany z identycznych cell'ów tak aby:
    - Wewnątrz każdego cella była wpisana współrzędna jak na screenshocie 1
10. Wykonać commit o nazwie `Mapa`, otagować `v0.0.4` oraz wykonać `push` na github
11. Stworzyć zmienną `active` wewnątrz `data` - ma mieć początkową wartość tekstowo: `1,1`
12. Dodać logikę, że `<div>` o klasie `cell` który posiada również klasę `active` ma mieć dodatkowo:
    - czerwone tło
    - biały tekst
14. Stworzyć logikę, że jeżeli zmienna `active` ma wartość `1,1` to pierwszy z lewej od góry cell posiada klasę `active` - analogicznie wszystkie pozostałe celle
15. Na tym etapie pierwszy od góry z lewej powinien być już czerwony z białym tekstem
16. Wykonać commit o nazwie `Active`, otagować `v0.0.5` oraz wykonać `push` na github
17. Przechwycić kliknięcie myszą w dane pole w ten sposób, aby została zmieniana wartość zmiennej `active` na kliknięty `cell`
18. Wykonać commit o nazwie `Click`, otagować `v0.0.6` oraz wykonać `push` na github
19. Przechwycić eventy `keydown` w taki sposób, aby dało się "przemieszczać" aktywnym boxem góra/dół/prawo/lewo
20. Sprawić, że jeżeli wyjdzie się poza zakres `row` lub `cell` - wybrany zostanie cell z przeciwległego brzegu (jak tunele w grze pacman)
21. Wykonać commit o nazwie `Mousedown`, otagować `v0.0.7` oraz wykonać `push` na github
22. Ustawić wartość `columns` na 15 oraz `rows` na 7, sprawdzić czy wszystko działa
23. Wykonać commit o nazwie `Done`, otagować `v1.0.0` oraz wykonać `push` na github
