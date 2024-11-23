        **Wizualizacja danych: ceny zamknięcia KGHM i miedzi**

Spis treści:
    Informacje ogólne
    Wykorzystane technologie
    Instalacja
    Użycie
    Kontakt

Informacje ogólne:
    Ten projekt demonstruje, jak wizualizować dane finansowe przy użyciu bibliotek Python i Plotly. Dane obejmują ceny zamknięcia akcji KGHM oraz miedzi (copper), przedstawione na interaktywnych wykresach i w tabeli.

Celem projektu było stworzenie wizualizacji:
    wykresu cen zamknięcia KGHM,
    wykresu cen zamknięcia miedzi,
    tabeli zestawiającej te dane w przejrzysty sposób.

Projekt został wykonany w celu zdobycia doświadczenia w analizie danych, wizualizacji interaktywnej oraz pracy z biblioteką Plotly.
Wykorzystane technologie
    Python - wersja 3.x
    Plotly - wersja 5.x
    Pandas - wersja 1.x
    (Opcjonalnie) Jupyter Notebook - do uruchamiania kodu w środowisku interaktywnym

Instalacja
    Sklonuj repozytorium na swoją maszynę lokalną:

    git clone <adres-repozytorium>

    Upewnij się, że masz zainstalowanego Pythona (3.x) oraz wymagane biblioteki:

    pip install pandas plotly

    (Opcjonalnie) Jeśli chcesz korzystać z Jupyter Notebook, zainstaluj go za pomocą:

    pip install notebook

Użycie
    Projekt zawiera kod, który:

    Wczytuje dane z plików CSV (ceny KGHM i miedzi).
    Łączy dane na podstawie daty i przekształca je w odpowiedni format.
    Tworzy trzy elementy wizualizacji:
        Wykres cen zamknięcia akcji KGHM.
        Wykres cen zamknięcia miedzi.
        Tabelę zestawiającą ceny zamknięcia KGHM i miedzi w tych samych dniach.

Aby uruchomić kod:
    Wczytaj dane do projektu w formacie CSV (np. kgh_d.csv dla KGHM i ca_c_f_d.csv dla miedzi).
    Uruchom kod w środowisku Python lub Jupyter Notebook.
    Wygenerowane wykresy i tabela będą wyświetlone jako interaktywny dashboard w przeglądarce.

Kontakt
    Stworzone przez @Quick-witted-flower  – jeśli masz pytania, śmiało napisz! 😊