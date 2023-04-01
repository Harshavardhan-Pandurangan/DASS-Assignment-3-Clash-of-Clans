# DASS Assignment 3 - Changes Made

## Harshavardhan P - 2021111003

-   Sneaky Archers
    -   characters.py
        -   Sneaky Archers Class same as Archers class with modifications
            -   invisibility property added with inital value 10, acts as timer
            -   Remove from sneaky_archers list when dead
        -   Spawn
            -   Spawn function into sneaky_archers list
        -   Move
            -   Move function for sneaky archers
        -   Clear troops updated
    -   map.py
        -   sneaky Archer Color same as normal archer
        -   Added sneaky archers to printMap function
            -   Named the tiles SNEAKY in same format as ARCHER
    -   points.py
        -   Added sneaky archers to troop limit with limit 7, same as archers
    -   spells.py
        -   Added rage and heal spell effects to the sneaky archers
