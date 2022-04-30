### Made by [/shxrks/pokeclicker](https://github.com/shxrks/pokeclicker)

![shxrks-tm-watermark](https://miro.medium.com/max/1200/1*z_Q3vhdUcOIpOVs3Velymg.jpeg)


## These are the commands to gain a random egg, gain a pokemon by its id, or progress eggs.

### Gain random egg
Hit CTRL+Shift+I on the tab. Then go to console and type the following:
App.game.breeding.gainRandomEgg()

### Gain PKMN by ID:
Hit CTRL+Shift+I on the tab. Then go to console and type the following:
App.game.party.gainPokemonById(IDofPKMN, ShinyOrNot, KillNotifOrNot)
The ShinyOrNot or KillNotifOrNot are bool statements, meaning either true or false.

### Progress all current eggs
Hit CTRL+Shift+I on the tab. Then go to console and type the following:
App.game.breeding.progressEggs(NumberThatIsGreaterThan0)
