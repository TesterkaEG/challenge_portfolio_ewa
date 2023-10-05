# <br>**[Task 1](https://tiny.pl/cf869)** 

## *Subtask 1*
Wynik z testu: 8/10 pkt. 💪
## *Subtask 2*
Tworzenie repozytorium. 
## *Subtask 3*
🖐 Cześć! Z tej strony Ewa. 🕵🏼‍♀️ 

Biorę udział w projekcie, ponieważ podjęłam decyzję o zmianie branży. Jestem pewna, że tym sposobem zwiększę swoje szanse na rynku pracy. Poza tym lubię wyzwania. Każde z nich traktuję jako szansę na zdobywanie nowych kompetencji oraz możliwości rozwoju. 
## *Subtask 4*
Projekt znajduje się na dysku Google. 
## *Subtask 5*
Tworzenie konta - Jira.


# <br> **[Task 2](https://tiny.pl/cf8bg)** 
Wszystkie zadania są dostępne na dysku Google. 
## *Subtask 1*
Pisanie przypadków testowych na podstawie User Story.
## *Subtask 2*
Pisanie przypadków testowych na podstawie "własnych doświadczeń".
## *Subtask 3*
"Po co piszemy test case'y?" 😄
## *Subtask 4*
Pisanie przypadków testowych na podstawie "własnych doświadczeń". Testy aplikacji Pick Eat Up https://pickeatup.io/


# <br> **[Task 3](https://tiny.pl/c5pzb)** 
## *Subtask 1*
Utworzenie formatki do zgłaszania błędów systemu.
## *Subtask 2*
Testowanie według planów testów i raportowanie błędów.
## *Subtask 3*
Raport z wykonanych testów. 📋
## *Subtask 4*
Sesja testów eksploracyjnych.


# <br> **[Task 4](https://tiny.pl/c1dh9)**
## *Subtask 1*
Utworzenie formatki do zgłaszania błędów systemu (dodatkowe kolumny).
## *Subtask 2*
Testowanie eksploracyjne i raportowanie błędów. 
## *Subtask 3*
Do czego służy ta aplikacja? OLX - ogłoszenia lokalne
## *Subtask 4*
Testy aplikacji mobilnej i webowej.

[Jira](https://tiny.pl/c1f8n)


# <br> Task 5
## *Subtask 1*
Krótki kurs podstaw SQL.
## *Subtask 2*
Konfiguracja środowiska i wgranie bazy danych.
## *Subtask 3*
Zadania.

1.Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.

SELECT * FROM `actors` ORDER BY surname;

![image](https://github.com/TesterkaEG/challenge_portfolio_ewa/assets/144365299/13e3e3a6-6736-4473-a102-69514fbb2c12)

2.Wyświetl film, który powstał w 2019 roku.

SELECT * FROM `movies` WHERE `year_of_production`= 2019;

![zad 2 b](https://github.com/TesterkaEG/challenge_portfolio_ewa/assets/144365299/3f3806e2-92a7-4396-84aa-bcb2d04a8fa7)

3.Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

SELECT * FROM `movies` 
WHERE `year_of_production` BETWEEN 1900 AND 1999;

![image](https://github.com/TesterkaEG/challenge_portfolio_ewa/assets/144365299/c48a0efd-881f-4d13-aa27-a7f790d54838)

4.Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$.

SELECT title, price FROM `movies` WHERE price<7;

![image](https://github.com/TesterkaEG/challenge_portfolio_ewa/assets/144365299/4f6b1c9f-34d9-4467-851b-bd6e35fdfa63)

5.Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

SELECT * FROM `actors` 
WHERE actor_id>= 4 AND actor_id<= 7;


![image](https://github.com/TesterkaEG/challenge_portfolio_ewa/assets/144365299/01ec225e-7954-4705-85df-14a6378e1d95)

6.Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.

SELECT * FROM `customers` 
WHERE customer_id=2 OR customer_id=4 OR customer_id=6;

![image](https://github.com/TesterkaEG/challenge_portfolio_ewa/assets/144365299/f887d7f0-1521-4402-87ce-5bb914653b8d)


7.Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.
