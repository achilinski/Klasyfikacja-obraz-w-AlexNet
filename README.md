# ADOM AlexNet — Klasyfikacja Ras Psów

Projekt ten demonstruje implementację sieci AlexNet oraz badanie różnych strategii uczenia (od podstaw, zamrożenie klasyfikatora, pełny fine-tuning, selektywne odmrażanie warstw) na zbiorze danych z konkursu *Dog Breed Identification*.

---

## Uruchomienie lokalne

Aby przygotować lokalne środowisko i zainstalować wymagane pakiety, wykonaj poniższe kroki w terminalu:

### 1. Stworzenie i aktywacja środowiska wirtualnego
```bash
# Tworzenie środowiska venv
python3 -m venv venv

# Aktywacja środowiska (Linux / macOS)
source venv/bin/activate

# Alternatywnie: Aktywacja środowiska na Windows (Command Prompt)
# venv\Scripts\activate
```

### 2. Instalacja zależności
```bash
pip install -r requirements.txt
```

---

## Praca z notatnikiem

Zalecanym i najbardziej komfortowym sposobem uruchomienia tego projektu jest skorzystanie z platformy **Google Colab**, która zapewnia darmowy dostęp do akceleratorów GPU (np. T4 GPU), niezbędnych do sprawnego trenowania modeli.

Możesz bezpośrednio otworzyć przygotowany notatnik za pomocą poniższego przycisku:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1oAtNDhXB4LWLDbhfJxJKJD0uSCBdp0yW?usp=sharing)

---

## Wyniki eksperymentów

Wszystkie szczegółowe analizy, przebiegi uczenia (wykresy strat i dokładności) oraz macierze pomyłek dla poszczególnych eksperymentów (w tym porównanie optymalizatorów SGD vs Adam) zostały wygenerowane i zapisane bezpośrednio wewnątrz udostępnionego wyżej notatnika Google Colab. Nie ma potrzeby ponownego trenowania modeli, aby zapoznać się z rezultatami prac.
