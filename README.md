# 🀄🎴🎮 Elderwein

Elderwin jest silnikiem gry MMORPG zawierającej elementy grafiki 3D.
Składa się z wielu niezależnych funkcji, które tworzą razem w pełni konfigurowalną grę MMORPG.

## 💻 Wykorzystywane technologie / stack technologiczny

W tym projekcie wykorzystane zostały rozmaite technologie.

API do obsługi wszystkich funkcji, posiadające odpowiednie endpointy przygotowano w PHP8.
Baza Danych to MySQL 2021 (innoDB).
Aplikacja mobilna stworzona została przy użyciu Unity. Konsumuje ona API, które zostało przygotowane w PHP8.

`(DB)`

- MySQL with PHPMyAdmin / or SQLite / Or more scalable non-relational DB

`(API)`

- PHP8

`(mobile)`

- C#
- .NET
- Unity

# 🗺 Świat gry

Każda gra RPG powinna posiadać świat w którym to rozgrywa się główna fabuła / gracze doświadczają różnych przygód, mogą mierzyć się ze sobą oraz wchodzić w interakcję.

Fantastyczne światy przedstawione w grach charakteryzują się specjalnymi cechami, a lokalizację się w nich znajdujące skrywają ciekawe historie pełne intrygujących niuansów.

Podczas tworzenia świata gry Elderwein należy uwzględnić, iż każda lokalizacja będzie posiadała określony wątek tematyczny skorelowany z głębszą historią związaną z tymże miejscem. Może to się wiązać z np. występowaniem danego typu potworów na okolicznych terenach, lub na infrastrukturze zbudowanej w około.

Pod rozwagę należy brać również aspekty takie jak ukształtowanie terenu, czy też typ osób zamieszkujący dany teren (z jakiej klasy się wywodzą, jakie mają zwyczaje, czy obchodzą szczególne święta).

Wszystkie klasy rodzą się w jednej i tej samej wiosce startowej - `Novum`.

## ⛰ Koncepcja lokalizacji

W świecie Elderwein odnajdziemy malownicze lokalizacje, skrywające swoje sekrety, a są to:

- `Weledor` - Wioska elfów w której odnajdziemy nieśmiertelnych elfów z długimi uszami oraz łukami.

- `Vlewood` - miasto zamieszkane przez bobry, NPC to bobry, a cała akcja rozgrywa się na otoczonym wodą miaście z drewna (takiej kłodzie)

- `Flebia` - jedno z 3. głównych wielkich miast, miasto rycerskie z garnizonem wojskowym lub innym motywem

- `Grana` - mała lokalizacja, przytulny gaj

- `Echal` - półwysep, lokalizacja nadmorska - plażowa z przeciwnikami plażowymi

- `Draunia` - lokalizacja zamieszkana przez Drauny, straszliwe istoty, które są jednak miłe

- `Shem draco` - lokalizacja ze smokami

Każda z lokalizacji musi być odpowiednio zaznaczona na mapie. Należy przygotować podstawowe lokalizację oraz sporządzić pełną liste wszystkich lokalizacji.

### 🗡 Stan walki w danej lokalizacji

Wyróżniamy dwa stany możliwe dla określonej lokalizacji:

- `Brak możliwości walki / PVP` - na takiej mapie nie można walczyć
- `PVP` - na mapie oznaczonej jako PVP można walczyć do woli

> ❔ Rozważyć możliwość zmiany stanu walki w danej lokalizacji w zależności od pory dnia / godziny. Rozważyć dodanie kolejnego stanu opisującego taki konkretny przypadek.

# 😃 Postać

To właśnie postać wymaga największego dopracowania. Z postacią gracz obcuje na codzień, zawsze ją widzi a co za tym idzie musi być ona zrobiona dobrze.

## 🤗 Koncepcja typów postaci

W grze wyróżniamy różne typy postaci, a są to:

- `🧙‍♂️ Czarnoksiężnik` - obrażenia magiczne od ciepła 🔥 / zimna 🧊
- `🔪 Rycerz` - obrażenia fizyczne od broni dwuręcznej bądź jednoręcznej + tarcza
- `🏹 Łucznik` - obrażenia od łuku + wymaga strzał ➵🎯, jest możliwość używania zatrutych strzał ☠️

Wraz z rozwojemy gry kolejne klasy będą dodawane.

# Przeciwnicy

## Koncepcja typów przeciwników

## Koncepcja przeciwników specjalnych

# 🎇 Przedmioty

Każda gra MMORPG wymaga tego, aby gracz posiadał określone przedmioty, które będzie mógł ulepszać lub kupić lepsze alternatywy dla obecnie posiadanych przedmiotów.

## ✨ Typy przedmiotów

Wyróżniamy następujące typy przedmiotów według żadkości:

- `Pospolity` - przedmiot łatwy do znalezienia, jego zdobycie nie wymaga wiele trudu, jest stosunkowo tani

- `Żadki` - przedmiot trudniejszy do zdobycia od przedmiotu pospolitego, jego zdobycie wymaga włożenia trudu (szans 1/200 -> 0.5%?)

- `Eventowy` - do zdobycia w różnych eventach organizowanych np. na Wielkanoc, Boże Narodzenie

- `Premium` - przedmiot zakupiony za walutę premium

- `Krwawy / Zakrwawiony` - za punkty, zdobywane w momencie ubijania przeciwników z różnicą +/- 30 poziomów

# NPC oraz zadania

W celu zapewnienia rozrywki na najwyższym poziomie w grze muszą zostac wprowadzone postacie NPC u których możliwe będzie wykonywanie określonych zadań na konkretny poziom doświadczenia. Za wykonyane zadania powinna być odpowiednia nagroda w złocie, punktach doświadczenia czy tez przedmiotach lub innych formach.

## Koncepcja

# Podstawowe mechaniki gry

# Eventy specjalne

## Funkcje wymagające implementacji oraz wprowadzone ficzery

- `[silnik]` Dodano mechanizm wymiany przedmiotów.
- `[NPC]` Dodano mechanizm wymiany przedmiotów.
- `[multiplayer]` Dodano mechanizm wymiany przedmiotów.

# Podsumowania techniczne

## Technologie

Należy wybrać technologię zdolną obsłużyć do 20,000 graczy jednocześnie - tak, aby u żadnego nie wystąpiły zacięcia / lagi.

Infrastruktura musi być skalowalna oraz nie posiadać bootlenecków.

Rozbudowa musi być łatwa oraz niedroga / oszczędna w środkach.

## 🖥 Ostateczny wybór technologiczny

`Język: `
`Baza danych: `
`Klient: `
