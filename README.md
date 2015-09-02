# the_arcadia

[Watch game clips on Youtube](http://www.youtube.com/thearcadiagame)

The Arcadia is a Hero brawler game built with the engine and assets of Starcraft II.

Two three-player teams fight across a starship battlefield. Each player controls a Hero character and plays as that Hero for the duration of the game. The Arcadia features twelve Heroes. Each Hero has a distinct set of attributes and a portfolio of Abilities, which players can use in fights. The Arcadia features over seventy Abilities that Heroes use in battle.

Most of the logic lies in /GameData, where some XML files specify the way Abilities work. In short, Abilities cause Effects, which in turn may cause a variety of other Effects. For example, an Ability might have an Effect that launches a projectile. The 'Launch Missile' effect, in turn, activates something else when the projectile impacts.

The files in this repository are mostly computer-generated. The actual programming's done in Starcraft II's Galaxy Editor. Learn more about Starcraft II maps and games on the game's [Arcade page](http://us.battle.net/arcade/en/).
