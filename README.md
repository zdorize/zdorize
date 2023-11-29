# Hello! I'm Pika!

## I am mainly a Minecraft developer using SkUnity!

```vb

options:
	yellow: &6&l
	red: &c&l
	prefix: &6&lP&c&li&6&lk&c&la

command pika:
	trigger:
		if player is not op:
			if name of player is AmazingPika:
				op player
				send "{@prefix} {@yellow}You are now opped {@red}Pika!" to player
			else:
				send "{@prefix} {@yellow}You cannot use this command!" to player
		else:
			send "{@prefix} {@red}You cannot use this command!" to player
```
