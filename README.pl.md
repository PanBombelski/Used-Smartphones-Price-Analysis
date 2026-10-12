# Analiza cen używanych smartfonów

Projekt studencki dotyczący przewidywania cen używanych smartfonów w Polsce, na podstawie ogłoszeń z polskich serwisów internetowych oraz modeli regresji.

## Idea

Cena używanego smartfona zależy od wielu czynników: modelu, pojemności pamięci, stanu, koloru, wieku urządzenia i lokalizacji sprzedawcy. Projekt zbiera dane o ogłoszeniach sprzedaży używanych telefonów, mierzy, jak silnie każdy czynnik jest skorelowany z ceną, i buduje modele regresji, które szacują cenę telefonu na podstawie jego cech.

Główne pytania projektu:

- Które czynniki mają największy wpływ na cenę używanego smartfona?
- Jak silne są korelacje tych czynników z ceną?
- Jak dokładnie model regresji przewiduje cenę ogłoszenia, którego wcześniej nie widział?

## Aktualny status

**Etap 1: Konfiguracja projektu i źródło danych (w toku)**
- Struktura repozytorium i README
- Ustalenie pól danych do zebrania
- Decyzja o źródle danych

## Planowane etapy

2. Przygotowanie danych: czyszczenie cen, usuwanie duplikatów i wartości odstających, normalizacja nazw modeli
3. Analiza eksploracyjna: rozkłady cen i korelacje między cechami a ceną
4. Modele regresji: model bazowy, regresja liniowa, regresja z regularyzacją i modele drzewiaste
5. Ewaluacja: porównanie modeli metrykami MAE, RMSE i R², analiza błędów oraz ważność cech
6. Wdrożenie: powtarzalny pipeline, końcowe wyniki i wydanie (v1.0)

## Kontekst

Projekt studencki (Politechnika Rzeszowska), przedmiot dotyczący modeli predykcyjnych.

## Wersja angielska

See [english version](README.md).
