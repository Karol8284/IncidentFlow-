
## Najlepszy projekt do pracy bez AI

Nie rekomendowałbym kolejnego CRM, zakupów ani zarządzania projektami — powtarzasz domeny już istniejące.

**Wybór: `IncidentFlow` — system zgłoszeń serwisowych.**

Napisz go na osobnym forkowanym starterze. Minimalny zakres:

- użytkownik zgłasza incydent,
- administrator nadaje priorytet i przypisuje pracownika,
- osoba rozwiązująca zmienia status,
- komentarze tworzą historię działania,
- system zapisuje podstawowe SLA i termin,
- istnieją role użytkownika, assignee i administratora,
- backend posiada jednostkowe i integracyjne testy,
- React pokazuje listę, filtrację i szczegóły zgłoszenia.

MVP w 10 dni:

- dzień 1–2: domena i encje,
- dzień 3–5: tworzenie i przydział zgłoszenia,
- dzień 6–7: statusy, komentarze i history log,
- dzień 8: unit testy i jeden test PostgreSQL,
- dzień 9: jeden przepływ E2E i instrukcja,
- dzień 10: README, screenshot i code review własnego kodu.

Taki projekt dobrze uzupełnia [ProcureFlow](https://github.com/Karol8284/ProcureFlow):

- pokazuje role i autoryzację,
- oferuje inne reguły biznesowe,
- dowodzi samodzielnego wdrożenia w istniejącej bazie,
- nie wymaga wielkiego zakresu,
- dobrze łączy frontend, EF Core, testy i pracę z błędami.

## Co przypiąć od razu

1. [ProcureFlow](https://github.com/Karol8284/ProcureFlow) — główny projekt domenowy.
2. `IncidentFlow` — osobna samodzielna próba bez AI.
3. [ClinicBook](https://github.com/Karol8284/ClinicBook) — drugi pełny produkt tylko jeśli potrafisz go uruchomić i obronić własny wkład.

Starter pozostaw jako podstawę do nauki i technicznego referencja, nie jako trzeci główny produkt.
