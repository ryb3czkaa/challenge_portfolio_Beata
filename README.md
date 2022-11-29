# Task 5
## Subtask 1
### Zapytania, których nauczyłam sie z kursu:
1.SELECT * FROM  NAZWA TABELI - WYŚWIETLENIE ZAWARTOŚCI TABELI

2.USE 

3.GO - ODGRADZA KILKA INSTRUKCJI

4.SELECT NAZWA, Name, np. color, size  FROM NAZWA TABELI - wyświetlanie wybranych części tabeli

5.SELECT ProductID AS ID, Name AS Nazwa, Color AS Kolor, Size AS Rozmiar
FROM Production.Product  - aliasy

6.CREATE TABLE naza - tworzenie kolumny

7.SELECT * FROM nazwa tabeli ORDER BY Name  - sortowanie danych po nazwie

8.SELECT * FROM nazwa tabeli ORDER BY Name ASC  - sortowanie danych po nazwie rosnąco

9.SELECT * FROM nazwa tabeli ORDER BY Name  DESC - sortowanie danych po nazwie malejąco

10.SELECT ProductID, Name, Color, Size FROM Production.Product WHERE zakres -filtrowanie danych 

11.SELECT * FROM Production.Product WHERE Name LIKE ' ' - 

12.SELECT ProductID, Name, Color, Size FROM Production.Product WHERE Color = 'Black' AND Size = 'M'



## Subtask 3
1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.
![image](https://user-images.githubusercontent.com/109338452/204647643-8eabe533-6a55-4a67-9a8c-e3c44c05f9eb.png)


2. Wyświetl film, który powstał w 2019 roku.
![image](https://user-images.githubusercontent.com/109338452/204648137-38f7920d-134b-4f92-a2c7-e6c471ec5fe9.png)

3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.
![image](https://user-images.githubusercontent.com/109338452/204649053-1019bf90-b611-40d2-8d96-71a8f2511a3d.png)

4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$ 
![image](https://user-images.githubusercontent.com/109338452/204650021-0269b429-3135-4384-b20a-2f98ad53f2df.png)

5.Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.
![image](https://user-images.githubusercontent.com/109338452/204657213-1a746c40-db47-4f27-b72f-dc4b90b38516.png)


6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny. 
![image](https://user-images.githubusercontent.com/109338452/204661306-a64a1333-f8fc-4617-96b4-591262a9b864.png)

7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN. 
![image](https://user-images.githubusercontent.com/109338452/204660476-a8d7f936-5fd7-418a-a5c7-a2a37c18ef48.png)

8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.
![image](https://user-images.githubusercontent.com/109338452/204656551-84f1050d-d633-4122-947f-b7113421df59.png)


9. Wyświetl dane klienta, który nie ma podanego adresu email.
![image](https://user-images.githubusercontent.com/109338452/204657962-2c1eab3b-e0c5-47b4-aeda-24ef7c0af355.png)

10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.
![image](https://user-images.githubusercontent.com/109338452/204661814-8040f5ec-ca1e-49cb-b733-18d85ea196f6.png)
