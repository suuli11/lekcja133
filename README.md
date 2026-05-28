# Formularz rejestracyjny - jQuery Validation Plugin

## Zastosowane reguły walidacji

### Imię
- required
- minlength: 2

### Email
- required
- email

### Hasło
- required
- minlength: 6

### Powtórz hasło
- required
- equalTo

### Wiek
- required
- digits
- min: 18

### Nazwa użytkownika
- required
- minlength: 3
- remote (AJAX)

## Funkcjonalności

- Walidacja formularza po stronie klienta.
- Własne komunikaty błędów.
- Sprawdzanie zgodności haseł.
- Walidacja wieku.
- Sprawdzanie dostępności loginu przy użyciu AJAX.

## Technologie

- HTML5
- CSS3
- JavaScript
- jQuery
- jQuery Validation Plugin
