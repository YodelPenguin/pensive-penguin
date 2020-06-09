:purple_heart: **Current commands for PokeHeart** :purple_heart:
===========

**Syntax:**
*`<>` = Optional command addition*
*`{}` = Command substitute (i.e. use instead of, usually before/after)*
*`X` = Pokemon ID*
*`S` = Stirling, PokeHeart's currency*
*`M` = Pokemon move, find this from `p!learnset` or `p!moves`*

 **General**
------------

:baseball: `p!catch` *Pokemon*  /  {`p!balltype` *Pokemon*}
> **Catches** Pokemon **currently spawned** on screen
> / with **`balltype`** (great, ultra etc.)

:page_with_curl: `p!info` <`latest`> < *`X`*> <`p!nickname` *`name`*>
> **Info** on chosen Pokemon / latest caught
> /** ID No *`X`* **
> /** Nickname *`X`* *`name`* **

:bookmark_tabs: `p!pokemon` <`PageNo`>
> **Displays owned Pokemon** as paged list

:ballot_box_with_check: `p!select` <*`X`*> <`latest`>
> **Select** Pokemon *`X`* (for checking moves, training & nicknaming)
> /Select **latest Pokemon in your list**

:feet: `p!friendship` *`X`*
> Shows **friendship level** of Pokemon *`X`*
> (Use `1` for your **default starter**)
> Currently **not implemented**

## SPLIT HERE (Discord message character limit) 1/2

**Pokemon Teams & Moves**
------------

:arrow_heading_down: `p!teamadd` *`X`*
> Add Pokemon *`X`* to **your team**
> Added Pokemon **cannot be removed** from a team currently

:four_leaf_clover: `p!team`
> Displays your current team

:cyclone: `p!moves`
> **Displays currently known moves** for selected Pokemon

:bulb: `p!learnset` {`p!learn` *`M`*}
> Shows all moves your selected Pokemon **can currently learn**
> /**Teaches selected Pokemon** move *`M`*
> This command **is incomplete** and will be improved on in the future

**Items & Trading**
------------
:convenience_store: `p!shop` <`stone`> <`forms`> <`misc`> <`images`>
> **Evolution** Stones / **Form Items**
> **Miscellaneous** / Image **Variations**
> *Shop is currently* ***view only***

:pound: `p!bal`
> Displays your **Sterling balance**  

:credit_card: `p!card`
> Displays your **trainer card**, with stats.

:love_letter: `p!trade` *`@DiscordUser`* {`p!confirm`} {`p!deny`}
> **Open a trade** with *`@DiscordUser`*
> *`@DiscordUser`* enters `p!confirm` or `p!deny` to accept or decline the trade request

:open_hands: `p!add` *`X`* {`p!remove` *`X`*}
> Add or remove Pokemon *`X`* to/from trade with *`@DiscordUser`*
> Use `p!pokemon` to **show your Pokemon list** for Pokemon's ID

:money_with_wings: `p!s add` *`S`* {`p!s remove` *`S`*}
> Add/remove *`S`* **amount of Stirling** to the trade

:white_check_mark: `p!confirm`
> Confirms the trade with *`@DiscordUser `*
> ***Cancelling the trade doesn't seem to work right now (at least for me), wait for it to time-out if you want to cancel***

## SPLIT HERE (Discord message character limit 3/3)

**Server & Misc**
------------
:grey_question: `p!help`  
> Displays built-in **help**
> ***Currently not implemented***

:alarm_clock: `p!time`
> Shows **current game time** relative to your time zone  

:computer: `p!servers`
> **Stats** on how many servers PokeHeart is currently running on

:arrow_up: `p!levelup`
> Toggles **level-up** notifications on/off

:loop: `p!redirect` <*`channelID`*>
> Redirect spawns to *`channelID`*, requires admin permissions

**About & Revision Info**
-----------
:penguin: Feel free to PM me on Discord ( @Yodel Penguin#9982 ) if this needs updating or something in this guide doesn't work the way it's typed!

This guide has been released under the Apache 2.0 licence, see https://github.com/YodelPenguin/pensive-penguin/blob/master/LICENCE for details.
|| 1.3.3 - rev 09/06/20  ||
