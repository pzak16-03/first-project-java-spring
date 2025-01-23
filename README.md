Aplikacja została stworzona przy pomocy frameworku Spring Boot oraz Thymeleaf,
które służą do renderowania dynamicznych widoków na podstawie danych przekazywanych przez kontroler. Mamy w niej strone powitalną, która wyświetla tekst: "Hello Vistula, in my first Spring controller."
dostępną pod adresem http://localhost:8080
Mamy też stronę powitalną z nazwą użytkownika, możemy zmieniać nazwę użytkownika poprzez wpisanie jej w adresie URL. (np. http://localhost:8080/greeting?name=Vistula).
Na podstawie tego jest generowane spersonalizowane powitanie, które wyświetla komunikat "Hello [name]!"
Aplikacja pozwala nam również na wyświetlenie obrazu, który jest załadowany z folderu static.
Zostały użyte technologie: 
-Spring Boot - do stworzenia aplikacji webowej 
-Thymeleaf - pozwala nam renderowanie dynamicznych stron HTML 
-HTML - do formatowania stron i zawartości. 
Struktura aplikacji: 
-Kontroler - odpowiadający za obsługę żądań HTTP i przekazujący dane do widoków 
-Szablony Thymeleaf - zawierające kod HTML, który wykorzystuje dane z kontrolera, np. powitanie i obrazem. Jest to prosty przykład użycia Spring Boot i Thymeleaf do tworzenia aplikacji webowej z interaktywnymi widokami.
Piotr Żak nr indeksu 66774
