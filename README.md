# Fighting-game
Na mój projekt zrobiłem bijatykę w stylu 2D.

W grę może grać jednocześnie 2 graczy

Player 1: 
Ruch : W,A,D
Atak: Spacja

Player 2:
Ruch : ←↑→
Atak: ↓


Gra jest zrobiona po części w HTML-u i w dużej mierze z użyciem Javascriptu. 

Myślałem nad pracą w Unity, ale zrobiłem w tym projekt w tamtym roku i chciałem spróbować czegoś nowego.

Ogólnie to program składa sie z klasy, która zawiera np. pozycję postaci i jakie akcje wykonuje. 

Kolejna klasa zajmuje się końcem gry. Są 2 sposoby na zakończenie gry. Albo któryś z graczy umiera, albo kończy się czas i gra kończy się remisem.

Później mamy plik HTML, który służy tylko do wyświetlenia działającego progamu.

Na końcu jest plik js, który umożliwia poruszanie się, obsługuje animacje i wyznacza hitboxy postaci.

Inspirowałem się dawnymi wersjami gry Mortal Kombat i chciałem trochę więcej podziałać właśnie z Javascryptem.

Myśle że takim największym wyzwaniem była implementacja wszystkich animacji oraz hitboxów (często było tak, że postacie mogły się bić pomimo tego, że były po przeciwnych stronach mapy).

Kierowałem się tym tutorialem na Youtubie: https://www.youtube.com/watch?v=vyqbNFMDRGQ.


Myśle, że na tą chwile projekt jest na bardzo wczesnym etapie. Na pewno chce dodać możliwość wyboru postaci, ewentualnie więcej ataków i map.
