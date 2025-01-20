# Project Vote 🎴

Project Vote to aplikacja do wyceny zadań w zespołach. Wspiera wyceny w systemie liczb Fibonacciego, ułatwiając zespołowi osiągnięcie konsensusu podczas wycen.

## Funkcje ✨

- Wyceny zadań w systemie Fibonacciego (1, 2, 3, 5, 8, 13)
- Obsługa sesji wyceny dla wielu użytkowników
- Prosty interfejs użytkownika
- Konfigurowalność za pomocą pliku `.env`

---

## Wymagania systemowe 🖥️

- **Go** w wersji 1.22.6 lub wyższej
- **Docker** (opcjonalnie, do uruchomienia w kontenerze)

---

## Instrukcja instalacji i uruchomienia lokalnie 🏃‍♂️

1. **Sklonuj repozytorium**:
   ```bash
   git clone https://github.com/gradev-dev/ProjectVote.git
   cd ProjectVote
   ```
2. **Utwórz lokalną kopię pliku `.env`**:
   ```bash
   cp .env.vm .env
   ```
3. **Zainstaluj zależności**:
   ```bash
   go mod tidy
   ```
4. **Uruchom aplikację lokalnie**:
   ```bash
   go run main.go
   ```
5. **Dostęp do aplikacji `http://localhost:4009`**:
