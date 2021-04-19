# fvtt-wild-magic-surge
Revised DnD5e Wild Magic Surge Tables for FoundryVTT

Download and import all modules into world.
Roll on the **01: Revised Wild Magic Table**

Macro
> const table = game.tables.entities.find(t => t.name === "01: Revised Wild Magic Table");
> table.draw();

go into each Rolltable and uncheck "Display Roll to Chat?" 

## Issues
01: Revised Wild Magic Table may error out if the additional tables aren't added

**Resolution:** add the tables if the entry is blank

**Result Type | Result Details | | Weight | Range**

Entry | RollTable | 01-03: Extreme Wild Magic | 3 | 1-3

Entry | RollTable | 04-09: Moderate Wild Magic | 6 | 4-9

Entry | RollTable | 10-20: Nuisance Wild Magic | 11 | 10-20
