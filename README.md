# The Good Vibes Club

Repository of Blood on the Clocktower scripts and homebrew creations for use by the members of our Discord server.

# Contributing

New content can be added via pull request into `main`:
* fork the repository
* make your changes
* open a pull request

A workflow will run to validate against the schema in `ThePandemoniumInstitute/botc-release repo`. A copy of the schema is available here for convenience. If the workflow fails on the pull request, fix all issues with the JSON file before merging.

Custom scripts build with standard (TPI) characters only should be placed in the `custom` directory. 

Homebrew (either full scripts or individual characters) should be placed in a dedicated subdirectory of `homebrew`. 

Scripts for play-testing the homebrew characters should be placed in the `homebrew` directory.

List all new content in the appropriate section below, with a local link to the JSON file, and a link to the Almanac and the script database, if applicable.


# Contents


## Homebrew Characters

* [Martyr (Townsfolk) by Puck](homebrew/characters/martyr.json)
* [Rampage (Minion) by capt'n jakub](homebrew/characters/rampage.json)
* [Serpent (Demon) by Puck](homebrew/characters/serpent.json)
* [Skulker (Minion) by Puck](homebrew/characters/skulker.json)

### Playtest scripts

* [I Like My Friends Close... by Puck](homebrew/I_Like_My_Friends_Close.json) (Skulker)
* [On a Roll by capt'n jakub](homebrew/On_a_Roll.json) (Rampage)
* [Our Hands In Prayer by Puck](homebrew/Our_Hands_In_Prayer.json) (Martyr and Skulker)
* [Why Did It Have To Be Snakes by Puck](homebrew/Why_Did_It_Have_To_Be_Snakes.json) (Serpent)


## Homebrew Scripts

### The Dude Abides by capt'n jakub

[json](homebrew/the_dude_abides/the_dude_abides.json) - 
[almanac](https://www.bloodstar.xyz/p/captn_jakub/thedudeabides/almanac.html) - 
[database](https://botc-scripts.azurewebsites.net/script/6594)

Full homebrew script based on The Big Lebowski.

Do not use in streamed games, as it contains copyrighted material.


## Custom Scripts

Scripts using standard characters only. 

### A Few Good Men by capt'n jakub

[json](custom/A_Few_Good_Men.json)

Solo Legion script, to see if it would work. Should never give all Legion bluffs - it's fine to be outed Legion anyway.

### Delegation of Duties by capt'n jakub

[json](custom/Delegation_of_Duties.json)

"Weaker" Demons: either not choosing kills (Lil' Monsta, Yagababble, sometimes Ojo), or with a possibility of no death (Pukka with an execution on their poison).

Minions either kill or add a win condition. Town adding evils and night deaths.

### Don't Take My Word For It by capt'n jakub

[json](custom/Dont_Take_My_Word_For_It.json)

All characters have a way of mechanical confirmation for themselves, with a few that confirm other players.

Hard mode for the evil team.

Boffin adds the possibility that the Demon confirms themselves too.

Psychopath to boost the evil's changes a bit.

Ojo has the best info it can ever get, as all town is always confirmed.

### Miss-a-Line by capt'n jakub

[json](custom/Miss-a-Line.json) - 
[database](https://botc-scripts.azurewebsites.net/script/6595)

Solo Lord of Typhon, to see if it works. Work in progress.

### Stuff Happens by capt'n jakub

[json](custom/Stuff_Happens.json)

All weirdness you can get: Amnesiac, Wizard, Magician, all kinds of dorizon, nobody knows what is going on.

Stuff just happens.

### Suspicious Brew by Puck

[json](custom/Suspicious_Brew.json)

Solo Kazali. Rated "Most Fun" by the readers of The Good Vibes Club magazine.