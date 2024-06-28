## Opis projektu

### Cel:

Projekt "Crypto Price App" ma na celu dostarczenie użytkownikom narzędzia do śledzenia aktualnych cen różnych aktywów kryptograficznych (cryptocurrencies) na różnych giełdach w czasie rzeczywistym. Aplikacja umożliwia szybkie i łatwe monitorowanie zmian cenowych, co jest istotne dla inwestorów oraz entuzjastów rynku kryptowalut.

### Opis funkcji:

- **Monitorowanie cen:** Użytkownicy mogą przeglądać aktualne ceny różnych aktywów kryptograficznych na wybranych giełdach.
- **Wykresy i analizy:** Możliwość oglądania historycznych danych cenowych w formie wykresów oraz dokonywania analiz technicznych.
- **Powiadomienia cenowe:** Opcja ustawiania powiadomień dla określonych cen aktywów.
- **Ulubione aktywa:** Możliwość dodawania ulubionych kryptowalut do szybkiego dostępu i monitorowania.
- **Udostępnianie:** Opcja udostępniania aktualnych cen na platformach społecznościowych lub przez inne kanały komunikacyjne.

## Analiza wymagań

### Wymagania funkcjonalne:

- **Monitorowanie cen:** Użytkownik może wybierać aktywa oraz giełdy do monitorowania.
- **Wykresy i analizy:** Dostęp do interaktywnych wykresów cenowych i narzędzi analizy technicznej.
- **Powiadomienia cenowe:** Możliwość ustawienia powiadomień dla określonych poziomów cenowych.
- **Ulubione aktywa:** Funkcjonalność dodawania i zarządzania listą ulubionych aktywów.
- **Udostępnianie:** Umożliwienie udostępniania aktualnych cen na zewnętrzne platformy.

### Wymagania niefunkcjonalne:

- **Aktualność danych:** Zapewnienie, że ceny są aktualizowane w czasie rzeczywistym.
- **Responsywność:** Szybka reakcja aplikacji na zmiany cenowe i interakcje użytkownika.
- **Bezpieczeństwo:** Zapewnienie bezpiecznej transmisji danych użytkownika oraz ochrona prywatności.

## Projekt interfejsu

### Szkice/wizualizacje interfejsu:

- _Strona główna:_ Lista aktualnych cen wybranych aktywów, opcje filtrowania i wyszukiwania.
- _Wykresy cenowe:_ Interaktywne wykresy przedstawiające historię zmian cenowych.
- _Powiadomienia:_ Panel do zarządzania ustawieniami powiadomień cenowych.
- _Ulubione aktywa:_ Zarządzanie listą ulubionych aktywów do szybkiego dostępu.

### Mapa strony:

- _Strona główna_
  - Lista aktualnych cen
  - Opcje filtrowania i wyszukiwania
  - Ulubione aktywa
- _Wykresy cenowe_
  - Interaktywne wykresy z historią cen
  - Narzędzia analizy technicznej
- _Powiadomienia cenowe_
  - Zarządzanie ustawieniami powiadomień
- _Ulubione aktywa_
  - Lista ulubionych aktywów
  - Zarządzanie ulubionymi aktywami

## Architektura systemu

### Opis struktury danych:

Aplikacja przechowuje dane o cenach kryptowalut oraz preferencjach użytkowników, w tym:

- **Ceny kryptowalut:** Aktualne oraz historyczne ceny różnych aktywów na różnych giełdach.
- **Ulubione aktywa:** Lista ulubionych kryptowalut użytkownika.
- **Ustawienia powiadomień:** Preferencje dotyczące powiadomień cenowych.

### Diagramy architektury:

Architektura oparta jest na mikroserwisach, gdzie:

- **Backend:** Zarządza logiką biznesową oraz interakcją z bazą danych.
- **Frontend:** Prezentuje interfejs użytkownika oraz obsługuje interakcje użytkownika.
- **Baza danych:** Przechowuje dane o cenach, preferencjach użytkowników oraz historię transakcji.

## Implementacja

### Opis technologii:

- **Frontend:** React.js, HTML, CSS, JavaScript.
- **Backend:** Node.js (Express), MongoDB (baza danych dla cen i preferencji użytkowników).
- **Użyte API:** API giełd kryptowalut do pobierania aktualnych danych cenowych.
- **Bezpieczeństwo:** Zastosowanie protokołu HTTPS oraz szyfrowanie danych użytkowników.

### Struktura kodu:

- _Katalogi/pliki:_ Oddzielne pliki dla komponentów frontendowych, serwisów backendowych oraz zarządzania danymi.
- _Style pisania kodu:_ Używanie modułowości oraz komentarzy dla zwiększenia czytelności kodu.

## Testowanie

### Plan testów:

- **Testy jednostkowe:** Sprawdzenie poprawności funkcji pobierania danych oraz analizy cenowej.
- **Testy integracyjne:** Upewnienie się, że komponenty współpracują ze sobą poprawnie.
- **Testy interfejsu użytkownika:** Ocena łatwości użytkowania oraz responsywności interfejsu na różnych urządzeniach.
- **Testy wydajnościowe:** Ocena szybkości i responsywności aplikacji podczas dużej ilości użytkowników.

### Procedury testowania:

- Opracowanie scenariuszy testowych dla każdej funkcji aplikacji.
- Ustalenie procedur raportowania i naprawiania znalezionych błędów.

## Wdrożenie i konserwacja

### Plan wdrożenia:

- **Etapy wdrażania:** Testowanie, poprawki, publikacja na platformach dostępnych dla użytkowników.
- **Terminy:** Określenie dat planowanych etapów oraz aktualizacji aplikacji.

### Procedury konserwacji:

- **Wsparcie techniczne:** Ustanowienie kanałów komunikacji z użytkownikami w celu zgłaszania problemów oraz dostarczania wsparcia.
- **Aktualizacje:** Planowanie regularnych aktualizacji aplikacji w zależności od potrzeb rynku oraz opinii użytkowników.

## Harmonogram

### Plan projektu:

- **Etapy realizacji:** Podział prac na konkretne zadania (np. implementacja interfejsu, integracja z API, testowanie).
- **Terminy:** Określenie czasu potrzebnego na każdy etap oraz dostosowanie harmonogramu w zależności od postępów projektu.

## Kosztorys

### Szacunkowe koszty:

- **Rozwój aplikacji:** Koszty pracy zespołu programistów oraz projektantów UI/UX.
- **Koszty utrzymania:** Opłaty za serwery, usługi zewnętrzne oraz wsparcie techniczne dla użytkowników.

---

[English](/README.md)
