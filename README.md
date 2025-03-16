# The Good Vibes Club

Repository of Blood on the Clocktower scripts and homebrew creations for use by the members of our Discord server.

# Contents

## Custom Scripts

Scripts using standard characters only.

| name | author | notes |
| :--- | :---: | :--- |
| [A Few Good Men](custom/A_Few_Good_Men.json) | capt'n jakub | [database](https://botcscripts.com/script/6761) |
| [Delegation of Duties](custom/Delegation_of_Duties.json) | capt'n jakub | [database](https://botcscripts.com/script/6763) |
| [Don't Take My Word For It](custom/Dont_Take_My_Word_For_It.json) | capt'n jakub | [database](https://botcscripts.com/script/6764) |
| [Miss-a-Line](custom/Miss-a-Line.json) | capt'n jakub | [database](https://botcscripts.com/script/6595) |
| [Stuff Happens](custom/Stuff_Happens.json) | capt'n jakub | [database](https://botcscripts.com/script/6765) |
| [Suspicious Brew](custom/Suspicious_Brew.json) | Puck | |


## Homebrew

### Characters

| name | type | author |
| :--- | :---: | :---: |
| [Dream Eater](homebrew/characters/dream_eater.json) | Minion | Puck |
| [Martyr](homebrew/characters/martyr.json) | Townsfolk | Puck |
| [Rampage](homebrew/characters/rampage.json) | Minion | capt'n jakub |
| [Serpent](homebrew/characters/serpent.json) | Demon | Puck |
| [Siphon](homebrew/characters/siphon.json) | Minion | Puck |
| [Skulker](homebrew/characters/skulker.json) | Outsider | Puck |
| [Torment](homebrew/characters/skulker.json) | Minion | Puck |

### Scripts

Most of these are intended for play-testing particular a homebrew character - these characters are mentioned in the notes. For full homebrew scripts, refer to the almanac and/or the [script database](https://botcscripts.com) entry.

| name | author | notes |
| :--- | :---: | :--- |
| [Fangs and Teeth](homebrew/Fangs_and_Teeth.json) | Puck | Serpent |
| [I Like My Friends Close...](homebrew/I_Like_My_Friends_Close.json) | Puck | Skulker |
| [On a Roll](homebrew/On_a_Roll.json) | capt'n jakub | Rampage |
| [Our Hands In Prayer](homebrew/Our_Hands_In_Prayer.json) | Puck | Martyr, Skulker |
| [Play Meta Games](homebrew/Play_Meta_Games.json) | Puck | Torment, Hooligan |
| [Taste This](homebrew/Taste_This.json) | Puck | Martyr, Skulker, Siphon |
| [The Dude Abides](homebrew/the_dude_abides/the_dude_abides.json) | capt'n jakub | [almanac](https://www.bloodstar.xyz/p/captn_jakub/thedudeabides/almanac.html), [database](https://botcscripts.com/script/6594) |
| [Withered Whispers](homebrew/Withered_Whispers.json) | Puck | Dream Eater |


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