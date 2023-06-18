# dc-blackmarket
## QBCore QB-Menu + QB-Input based black market script

Used the same logic as the qb-shops so the config is self explanatory.

( For any help you can reach us at Discord: (https://discord.gg/RcMmcPMA4u) )

- Easy to setup items
- Multiple blackmarkets supported
- Random or fixed locations (when random, location changes after each script restart)
- Multiple checks for inventory size and slot limits
- Localisation : Translated to languages ; English, Dutch and Turkish
- Ability to open the shop with a configured item
- Ability to use black money (markedbills or other itemname) or Q-Bit as payment method
- When using the blackmoney option, you can add a multiplier to the price if you want to sell items for more when paid by blackmoney.
- Random item option, if you set this on true your blackmarket will get a random item from your list. If you have disabled random location then all your markets will get different random items.
- Option to use a timer for changing the location of the black market after X amount of minutes
- Optional minigames to wiretap and get the blackmarket location


Item needed:

```lua
	["crocodile_clips"] 			 = {["name"] = "crocodile_clips", 			["label"] = "Crocodile Clips", 	   			["weight"] = 150, 		["type"] = "item", 		["image"] = "crocodile_clips.png", 			["unique"] = false,   	["useable"] = false,   	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "Do some wiring work..", },
```

This is an edited version of [jim-shops](https://github.com/jimathy/jim-shops)
Wire minigame : [minigameFixWiring](https://github.com/mxlolshop/minigameFixWiring)
