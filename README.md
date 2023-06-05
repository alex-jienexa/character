# character
Создание информационного блока для персонажа видеоигры

TODO:
Структура персонажа
-Character
|- name
|- level
|- exp
|- max_health
|- health
|- stats
|- |- (сила)
|- |- |- name: Strenght
|- |- |- char_name: str
|- |- |- value: XXX
|- |- (ловкость)
|- |- (интеллект)
|- |- (мудрость)
|- (ячейки заклинаний)
|- |- item
|- |- |- level: 1
|- |- |- items
|- |- |- |- ...
|- |- |- level: 2
...
|- (залкинания)
|- |- (заклинание)-item
|- |- |- name: XXX
|- |- |- description: XXX
|- |- |- damage: X-Y
|- |- |- damage_type: fire
|- |- |- level: X
|- |- |- usage: self|sphere|line
|- |- |- time_to_cast: XXX
|- Weapon:
|- |- name:
|- |- description:
...
|- amulets:
|- |- item
|- |- |- name:
|- |- |- type:
|- |- |- (качество)
|- |- |- description:
|- inventory
...
