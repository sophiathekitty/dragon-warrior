# Dragon Warrior for Space Engineers

this is the source for the Dragon Warrior remake (demake?) i'm making for an [in game](https://github.com/sophiathekitty/TV) script in Space Engineers.

## Setup

if you want to use this in your own space engineers game you'll need to copy the text files into a "database" made of text panels in the game. these text panels should be named `DB:Dragon.Main.0` and `DB.Dragon.Tiles.0` etc.

### Game Info

for this one you will need to remove all of the line breaks from `game info.txt` and copy it to the *CustomData* for the text panel named `DB:Dragon.Main.0`

### Tiles

you can just copy the text from `tiles/tiles.txt` to the *CustomData* `DB:Dragon.Tiles.0`

### Characters

you can just copy the text from `characters/scene.txt` to the *CustomData* of `DB:Dragon.Characters.0`

### Maps

you'll need to remove the line breaks and copy the text from `maps/map_list.txt` to the *CustomData* of `DB:Dragon.Maps.0` and then you can reference it to copy the rest of the maps to the correct locations. the `maps/tantegel_throne.txt` goes in *PublicText* `DB:Dragon.Maps.0` text panel. and the `maps/charlockD.txt` goes in the *PublicText* of `DB:Dragon.Maps.12`

### Enemies

coming soon... will go in the *PublicText* of `DB:Dragon.Characters.0`

### Save

the `game save.txt` contains a default save that should be copied over to the *PublicText* of `DB:Dragon.Main.0` and the line breaks may need to be removed.

once i get everything working i'll see about getting a blueprint i can share to the steam workshop. i'll also publish the script to the workshop so you won't need to setup visual studio and the MDK stuff to deploy it.

## Notes about development

i wasn't really expecting to be able to make the whole game. leveling after 19 just uses the same random ranges to increase stats. i tried to make the experience costs go up slower than they would normally. (at least for the first few levels that i checked the math on) if i picked a hard coded value of a random range i generally picked the most generous options. i tend to prefer easier more forgiving games... and i feel like a game that's mostly just a novelty and distraction for while doing actual space engineer stuff it would be better to make it easier to get through more of the game. and i'm probably going to leave the dev chest in. at least in this repo. i could try to remove it from the sharable blueprint i plan on making.

### Sources and Resources used

sprites and tiles: [the spriters resource](https://www.spriters-resource.com/nes/dw/)
map references: [the spriters resource](https://www.spriters-resource.com/nes/dw/), [realm of darkness](https://www.realmofdarkness.net/dq/nes-dw-dungeon-maps/), [video game maps](http://www.videogamemaps.net/?maps/nes/dragonwarrior)
npc dialog and flavor text: [woodus](https://www.woodus.com/den/general/gamescripts.php)
game math and formulas: [gamefaqs](https://gamefaqs.gamespot.com/nes/563408-dragon-warrior/faqs/61640)
