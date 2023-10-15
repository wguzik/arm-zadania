# Lab 002 - ARM templates: zależności

## Wymagania
Aktywna subskrypcja w Azure i dostęp do portalu.

## Wstęp
### Cel
Wskazywanie zależności między zasobami oraz przekazywanie danych między obiektami

Czas trwania: 45 minut

### Struktura


### Polecenia konsoli
Polecenie `terraform` pozwala na uruchomienie Terraforma w wierszu poleceń. W praktyce jest to całe środowisko pozwalające na sprawdzanie, tworzenie i zarządzanie zasobami (terraformowymi, nie cloudowymi).

Przydatne polecenia na początek:
```bash

```

### Krok 0 - Uruchom Cloud Shell w Azure i sklonuj kod ćwiczeń Nawiguj w przeglądarce do [portal.azure.com](https://portal.azure.com), uruchom "Cloud Shell" i wybierz `Bash`.  Oficjalna dokumentacja: [Cloud Shell Quickstart](https://github.com/MicrosoftDocs/azure-docs/blob/main/articles/cloud-shell/quickstart.md).
```bash
git clone https://github.com/wguzik/
```

> Poniższe kroki realizuje się za pomocą Cloud Shell.



### Krok 8 - Usuń zasoby

```
terraform destroy
```

## Zadanie domowe
Dodaj więcej do zmiennej `environment` ograniczenie dotyczące możliwych wartości, np 'dev', 'test', 'prod'.