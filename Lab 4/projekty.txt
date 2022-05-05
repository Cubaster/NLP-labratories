--------  LISTA PRZYKŁADOWYCH/PROPONOWANYCH TEMATÓW ---------------------------------

1. Generator wierszy - program generujący rymowanki w wybranym języku. Do tego celu można użyć neuronowych modeli języka (opartych o Transformer lub LSTM) lub wykorzystać n-gramowe modele języka poznane już na laboratoriach.

 

2. Aspect Based Sentiment Analysis - podstawowe metody detekcji sentymentu klasyfikują cały dokument jako mający wydźwięk pozytywny lub negatywny (opcjonalnie neutralny). Często jednak mamy do czynienia z dokumentami takimi jak "Ekran w tym telefonie jest bardzo dobry, jednak bateria jest tandetna". W takich sytuacjach dużo sensowniejsze wydaje się badanie sentymentu per obiekt w zdaniu, np: Ekran:pozytywny, bateria:negatywny. Efektem projektu byłoby narzędzie, które ekstrahuje z tekstu obiekty i wykrywa ich sentyment przedstawiając pary obiekt:sentyment.

 

3. Detekcja wydarzeń - Na wielu stronach znajdziemy informacje o wydarzeniach zapisane w formie nieustrukturyzowanego tekstu. Gdybyśmy zdefiniowali wydarzenie, jako zwięzłą wzmiankę zawierającą miejsce i czas (opcjonalnie nazwę), moglibyśmy wykrywać wydarzenia poprzez detekcję lokalizacji i wyrażeń "czasowych" i ocenę, czy wykryte elementy łączą się tworząc wydarzenie.

 

4. Klasyfikator języka programowania - ponieważ mamy wiele otagowanych kodów źródłowych (każdy plik na githubie ma rozszerzenie definiujące język programowania jaki w sobie zawiera) możnaby wykonać klasyfikator, który przyjmując kod w nieznanym języku - przewidzi jaki to konkretnie język. Ponieważ zadanie jest prostą klasyfikacją, w ramach projektu należy dodać analizę, która pokaże jakie cechy są mocnymi przesłankami pozwalającymi nam na poprawną klasyfikację (np. jeśli widzimy słówko 'pass', to z dużym prawdopodobieństwem możemy stwierdzić, że mamy do czynienia z pythonem)

 

5. Klasyfikator tekstów piosenek - podobnie jak w projektach 3 i 4 - mamy dostęp do wielu tekstów piosenek i wiemy jakiego gatunku są te piosenki. Czy uda się sklasyfikować gatunki tylko na podstawie tekstu? Projekt obejmowałby przygotowanie klasyfikatora oraz stworzenie analizy jak poszczególne słowa/frazy przekładają się na wykryty gatunek

 

6. Klasyfikator proponujący tagi na reddicie/wykopie - dla pewnego zbioru hasztagów projekt próbowałby w sposób automatyczny wykrywać pod którą kategorię dany tekst należy. Podobnie jak w zadaniu 4, należałoby również wykonać analizę jakie słowa/frazy są najlepszymi wskazówkami co do nadania kategorii.

 

7. Usuwacz danych wrażliwych - wiele firm zmaga się z problemem anonimizacji zebranych danych. Projekt w sposób automatyczny usuwałby dane wrażliwe (numery telefonów, imiona i nazwiska, adresy, numery pesel itp) z dokumentów.



 

9. Zmierzenie się z jednym z zadań zawartych na Kaggle - Kaggle, serwis zawierający wiele zadań związanych z analizą danych zawiera wiele ciekawych wyzwań związanych z językiem naturalnym (np. https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews#description). Projektem zaliczeniowym mógłby być program, który będzie rozwiązywał jedno z tych zadań.

Ponieważ nie chcielibyśmy, aby było zbyt wiele kolizji tematów projektów, sukcesywnie będziemy publikować listę tematów "zaklepanych".

 

Pozdrawiam serdecznie, 
Dawid Wiśniewski

