## React - weekend 22-24 lutego 2019 [homework-3]

1. Przygotuj nowe repozytorium na githubie (na swoim prywatnym koncie)
2. Zainicjuj projekt z użyciem `create-react-app` i zacommituj wersję bazową.
3. W komponencie `App` wyświetl listę osób na bazie danych, które są załączone poniżej:

```
[
  { 
    id: 1, 
    name: 'John',
    surname: 'Doe',
    phone: '123-456-789',
    isFavorite: false
  },
  {
    id: 2, 
    name: 'Steve',
    surname: 'Stevens',
    phone: '987-654-321',
    isFavorite: true
  }
]
```
4. Niech dane wyświetlają się w formie tabeli z kolumnami: 'Name', 'Surname', 'Phone'.
5. Niech osoba, która ma atrybut `isFavorite: true` będzie wyróżniona na liście (np. żółte tło)
6. Niech w tabeli pojawi się dodatkowa kolumna bez nagłówka, w której będą wyświetlane przyciski "Toggle favorite" (po jednym dla każdej osoby).
7. Niech kliknięcie przycisku zmienia `isFavorite` danej osoby z `true` na `false` albo z `false` na `true`.
8. Nad listą osób wstaw formularz, za pomocą którego będzie możliwe dodawanie nowych osób do listy (wskazówka: lista osób powinna być w `state` komponentu `App`).
9. Dodaj nowy przycisk w kolumnie z przyciskami: 'Remove contact', niech kliknięcie w niego usuwa daną osobę z listy.
