# Zgłoszenia błędów

## BUG01 - Brak komunikatu o błędzie przy pustym imieniu

### Priorytet
Wysoki

### Kroki do odtworzenia

1. Wejdź na stronę rezerwacji.
2. Wybierz usługę.
3. Wybierz datę.
4. Wybierz godzinę.
5. Pozostaw pole imię puste.
6. Kliknij „Zarezerwuj”.

### Aktualny rezultat

System nie wyświetla komunikatu błędu.

### Oczekiwany rezultat

System powinien wyświetlić komunikat:

„Pole imię jest wymagane.”

---

## BUG02 - Możliwość wyboru godziny bez daty

### Priorytet
Średni

### Kroki do odtworzenia

1. Otwórz formularz rezerwacji.
2. Wybierz godzinę.
3. Nie wybieraj daty.
4. Kliknij „Zarezerwuj”.

### Aktualny rezultat

System pozwala przejść dalej.

### Oczekiwany rezultat

System powinien wymagać wcześniejszego wyboru daty.
