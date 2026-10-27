# Lab1

---

## Zasady oddawania

1. **Nazwa repozytorium** musi zawierać numer s studenta (lub numery studentów), np. `Lab-1_sXXXXX`.
2. **Zadanie Lab1** musi mieć **dedykowany branch** z rozwiązaniem (np. `lab1`).
3. **Oddanie** odbywa się wyłącznie przez Microsoft Teams: przesłanie **linku do brancha** z rozwiązaniem (jako **link**, nie jako plik tekstowy).
4. **Każda poprawa** wymaga przesłania **nowego linku** do brancha z poprawionym rozwiązaniem.
5. **Commity** przesłane po ostatecznym terminie oddania będą traktowane jako **oszustwo**.

---

1. Skopiować pliki lokalnie i stworzyć swoje prywatne repozytorium z nazwą `Lab-1_<twój-numer-s>` (numer s w nazwie jest obowiązkowy) w organizacji [ASI-PJATK-PK](https://github.com/ASI-PJATK-PK). Do repozytorium ma mieć dostęp tylko owner repozytorium. Rozwiązanie Lab1 umieścić na dedykowanym branchu (np. `lab1`).
   
2. a) Zmień nazwę pliku `train.py` na `<twój-numer-studenta>.py`.  
   b) W skrypcie stwórz funkcję, która będzie generowała automatycznie dwa zbiory danych w przestrzeni 2D. Każdy zbiór ma być chmurą zbliżonych punktów, a zbiory powinny być na tyle odległe, aby można było gołym okiem określić ich położenie. Wielkość chmury powinna wynosić od 50 do 100 punktów.  
   c) Wykorzystując wygenerowane dane, stwórz model w skrypcie, który będzie w stanie przewidywać, do którego zbioru/chmury należy dany punkt.

3. Uzupełnij plik `requirements.txt`.

4. Uzupełnij plik `.github/workflows/ci.yml`, tak aby komenda:

   ```yaml
   run: cat accuracy.txt
   ```

   wyświetlała:
   ```
   Model trained with accuracy: <wynik-w-procentach>%
   ```
5. Upewnij się, że wszystko jest uruchamiane w GitHub Action.

6. Oddaj zadanie w Teamsach jako **link do brancha** z rozwiązaniem Lab1 (nie plik tekstowy). Po poprawkach prześlij nowy link.
---
