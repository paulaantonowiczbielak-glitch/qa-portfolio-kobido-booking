# Przypadki testowe

## TC01 - Poprawna rezerwacja wizyty

### Kroki

1. Wejdź na stronę rezerwacji.
2. Wybierz usługę Kobido.
3. Wybierz datę.
4. Wybierz godzinę.
5. Podaj imię i nazwisko.
6. Podaj numer telefonu.
7. Podaj adres e-mail.
8. Kliknij „Zarezerwuj”.

### Oczekiwany rezultat

System wyświetla komunikat:

"Rezerwacja została przyjęta."

---

## TC02 - Brak imienia

### Kroki

1. Wypełnij formularz.
2. Pozostaw pole imię puste.
3. Kliknij „Zarezerwuj”.

### Oczekiwany rezultat

System wyświetla komunikat:

"Pole imię jest wymagane."

---

## TC03 - Niepoprawny adres e-mail

### Kroki

1. Wpisz adres e-mail bez znaku @.
2. Kliknij „Zarezerwuj”.

### Oczekiwany rezultat

System wyświetla komunikat:

"Niepoprawny adres e-mail."
