# Technologie Chmurowe — Zadanie 1 #

## Autor: Ireneusz Witek ##

## Opis zadania: ##
Aplikacja jest prostą stroną internetową uruchamianą w kontenerze Docker, która umożliwia sprawdzenie podstawowych informacji o aktualnej pogodzie dla wybranego miasta. Dane pogodowe pobierane są z serwisu wttr.in i prezentowane w przejrzystym interfejsie WWW. Po uruchomieniu kontenera generowane są logi zawierające datę, autora i port TCP. 

W projekcie zastosowano również:
- optymalizację cache podczas instalacji zależności,
- mechanizm `HEALTHCHECK` monitorujący stan aplikacji,
- uruchamianie aplikacji z poziomu użytkownika nie-root,
- zgodność ze standardem OCI poprzez dodanie odpowiednich etykiet obrazu.

## Działanie aplikacji: ##
!(screens/7.png)
!(screens/8.png)
