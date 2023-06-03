# TCH - Laboratorium 11
## INFO
- W katalogu 'nginx/conf.d' znajduje się plik konfiguracyjny nginx </br>
- W katalogu 'php' znajduje się Dockerfile budujący obraz php (ten dostępny na dockerhubie nie miał zainstalowanych potrzebnych komponentów) </br>
- W katalogu 'src' znajduje się plik 'index.php' z zawartością strony do wyświetlenia </br>
- W katalogu 'ss' znajdują się zrzuty ekranu </br>
- Port 6666 serwera został zmieniony na 6660 - przeglądarka nie zezwalała na dostęp (Firefox 113.0.2) </br>

### REPREZENTACJA GRAFICZNA
Do wygenerowania reprezentacji graficznej użyto narzędzia graphviz i obrazu docker-compose-viz </br>(https://github.com/pmsipilot/docker-compose-viz) </br>
</br> Instalacja i uruchomienie :
- sudo apt-get install graphviz
- docker run --rm -it --name dcv -v $(pwd):/input pmsipilot/docker-compose-viz render -m image docker-compose.yml




