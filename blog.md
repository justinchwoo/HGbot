## HGbot Blog!

Welcome to a (semi-regular) blog documenting coding progress on my new bot! It's probably around 3 days old and its a basic adventure generator with a few twists:

- No limit on playerbase
- Battle-royale style
- Unlimited customisability on event flavour text for maximum shenanigans

(List created 27/01/2021, for current functionality please check readme on first release)

This game was inspired by the Hunger Games run in a server I am currently in. The event was based off this website [http://brantsteele.net/hungergames/reaping.php](http://brantsteele.net/hungergames/reaping.php) and I hope to run this in the discord to revive the Games as the original games was halted as people got busy (and planning the Games, screenshotting and uploading 2000ish screenshots of events onto discord took quite a bit of time and work). To that end I am also aiming for a few things:

- Custom image, custom nickname and Discord ID support (the old Games had all 3)
- Custom event(s) list, customizable and expandable (the old Games had that functionality
- Slightly less random fights (mild amount of stat checks, hurt players might die easier, armed players might win easier

But most importantly:
- Simplicity. The code must be as simple as possible while enabling all the fun. The users don't input anything into this code so the user experience is only involved in the       display and nothing else, so take shortcuts wherever possible to enable the same fun experience.

## Updates (Scroll down for the latest submission)

### 27/01/2021
Will try to keep it short here, quite a lot has already been done (currently in the alpha branch). The formats are as follows:

Player = Class (code containing each player as an object)
event text = List of strings (each event set would be a list of whatever needs to be written)
event = Function (each event subtype will become a function)

Event types are currently sorted into types:
- lethal(L), 
- semi-lethal(SL); and
- nonlethal(NL),

and the subtypes consist currently of:
- potion(NL, adds HP)
- item(NL, adds to player combat ability)
- injury(SL, reduces HP)
- fight(SL, comparison between different players' combat ability); and
- execute(L, immediately kills a player)

with a plan (currently) to add:
- global(SL, events that affect player HP/battle ability); and
- encounter(NL, events where players encounter ... interesting events)

Will keep working on it and report as progress continues.






 `Code` text
