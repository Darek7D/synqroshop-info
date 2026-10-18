# SynqroShop — integracja z Allegro Sandbox

SynqroShop to aplikacja do zarządzania sprzedażą i synchronizacji danych z Allegro. Integracja ze środowiskiem testowym Allegro Sandbox służy do rozwijania i sprawdzania działania aplikacji.

## Zakres integracji

- Łączenie konta Allegro Sandbox przez OAuth 2.0.
- Pobieranie zamówień, ich pozycji, statusów oraz danych kupującego i dostawy.
- Powiązanie istniejących ofert z produktami w SynqroShop.
- Aktualizacja cen, opisów i stanów magazynowych powiązanych ofert po włączeniu synchronizacji.

## Korzystanie

1. W panelu SynqroShop otwórz integrację Allegro i wybierz środowisko Sandbox.
2. Połącz konto testowe i zaakceptuj wymagane uprawnienia na stronie Allegro.
3. Uruchom synchronizację i sprawdź pobrane zamówienia. Synchronizację ofert włączaj dla wybranych powiązań.

Operacje w Sandbox dotyczą danych testowych. Integracja wymaga osobnego konta i aplikacji zarejestrowanej w środowisku Allegro Sandbox.

## Dane i dostęp

Aplikacja korzysta z danych konta w zakresie udzielonych uprawnień. Tokeny dostępowe i odświeżające są przechowywane w postaci zaszyfrowanej. Konto można odłączyć w panelu SynqroShop.

## Kontakt

Pytania i problemy zgłaszaj w zakładce **Issues** tego repozytorium. Nie zamieszczaj tam tokenów, haseł ani danych kupujących.

## Dokumentacja Allegro

[Allegro REST API](https://developer.allegro.pl/) · [Pierwsze kroki i Sandbox](https://developer.allegro.pl/tutorials/pierwsze-kroki-MRwYEoOq0im)
