What to do:
- delete old dates (all or specific date or range of dates)
- delete names/users (all)
- add new dates (specific date or range of dates)

Reihenfolge:

1. Derzeitige Termin-Values zurückgeben
2. Neue Termine einspeichern
3. Alte Termin-Values löschen (muss in dieser Reihenfolge erfolgen, da immer ein Termin vorhanden sein muss)

## Xoyondo
Functions:
- delete_date:
    - input possibilities:
        - date: one date (string) e.g. "2023/09/25"
        - dates: multiple dates separated by comma (string) e.g. "2023/09/25,2023/09/26,..."
        - range of dates: two dates separated by minus (string) e.g. "2023/09/25-2023/09/30"
        - integer: 0 = all dates, 1 = first date, 2 = second date, ..., -1 = last date, -2 = second last date, ...

## TODO
- add functionalities to xoyondo class
- change functionalities of xoyondo class
    - range of dates and range of integers -> print out of bounds message if too large (similar to integers)
- integrate xoyondo class to bot class