# autaspz
zadanie MIP auta SPZ
program pre prácu so súborom predajcov aut
program má základné funkcie:
- načítanie obsahu súboru,
- výpis obsahu súboru
- výpočet odmien zamestnancov
- vyhľadanie SPZ podľa počtu najviac predaných aut
program bol vyvíjaný postupne zapracovaním jednotlivých funkcií
každá funkcia bola priebežne refaktorovaná - vylepšená a testovaná do finálnej podoby


1. funkcia "v" - výpis SPZ a vytvorenie hlavného menu
2. doplnenie funkcie "v" - načítanie znakov zo súboru a ich výpis,
   refaktoring - funkcia fgets načítavala vstupné údaje len po prvý biely znak, preto musela byť nahradená funkciou fgetc
3. funkcia "o" - doplnený aktuálny dátum cez knižnicu time.h, výpis položiek zo súboru na obrazovku
4. dokončenie funkcie "o", otestovanie a zrušenie kontrolných výpisov,
   urobila som branch existujúcej verzie a zároveň som vykonala push verzie na Git server do repository "git-refactoring-mip-2017-DeMensa123"
5. v novej lokálnej verzii som pokračovala s vytváraním ďalších funkcií "n" + úpravy a doladenie funkcií "v" a "o" (refaktoring)
6. dokončenie funkcie "n" a pridanie funkcií "p" a "s"
7. dokončenie a posledné opravy kódu - napr. uvoľnovanie pamäti, úprava podmienok v palindróme

