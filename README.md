# Portal Klienta B2B BOBRTECH: strona ćwiczeniowa

Fikcyjny portal do ćwiczeń z automatyzacji przeglądarki (Playwright) na szkoleniu „Zarządzanie w erze AI”.
Firma, produkty i ceny są zmyślone. Konto testowe: **demo / bobr2026**.

- Portal: https://dawidml.github.io/bobrtech-portal/
- Sprawdzanie wyniku: https://dawidml.github.io/bobrtech-portal/sprawdz.html

## Przełączanie wersji (dla prowadzącego)

1. Otwórz https://github.com/dawidml/bobrtech-portal/edit/main/config.json
2. Zmień cyfrę przy `"wersja"`:

| Wersja | Układ | Dane | Kiedy |
|---|---|---|---|
| 1 | A: tabela, stronicowanie, osobna strona szczegółów | v1, 24 produkty | dzień 1, Zadanie 2 |
| 2 | B: karty, „Load more”, panel z zakładkami, etykiety po angielsku | v2, 26 produktów | dzień 2, Zadanie 9 |
| 3 | losowy: A albo B przy każdym wejściu, losowe klasy CSS | v2, 26 produktów | dzień 2, Zadanie 9, wersja trudniejsza |

3. Kliknij **Commit changes** i jeszcze raz **Commit changes** w okienku.

Po ok. minucie portal i `sprawdz.html` działają w nowej wersji (odśwież stronę).
Aktualną wersję widać pod adresem https://dawidml.github.io/bobrtech-portal/config.json.
W wersjach 2 i 3 działają parametry w adresie: `?uklad=A`, `?uklad=B`, `?uklad=losowy`.

Źródło strony: folder `06_portal_B2B` w materiałach szkolenia (ten sam kod, tu z danymi wbudowanymi w HTML).
