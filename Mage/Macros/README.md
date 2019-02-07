# Macros

<h3 align="center"> Freeze - Summon Pet </h3>

```
#showtooltip
/cast [nopet] Summon Water Elemental; Freeze
```

> This macro combine 2 spells, when ever you have no pet, this will allows you to summon it; however if your pet is on the field the macro will perform freeze (*pet nova*).

<h3 align="center"> CounterSpell </h3>

```
#showtooltip
/stopcasting
/cancelaura Ice Block
/cast [mod:shift, @focus] Counterspell; Counterspell
```

> Lets study a bit this macro, beacause it's a really usefull one. 
> - `/stopcasting` : when ever a player is casting a spell, you can imediatly interrut him on cast, even when you are casting on your own. Normally you have to walk to stop your cast and then press **Counterspell**, but with this macro you just have to press it.
> - `/cancelaura Ice Block` : it may happen that you are inside your block and someone cast a spell, its the same logic as before, press your macro allows you to get out of it and lock on cast.

<h3 align="center"> Ice Barrier </h3>

```
#showtooltip Ice Barrier
/cancelaura [mod:alt] Ice Barrier
/cancelaura [mod:alt] Power Word: Shield
/cast [nomod] Ice Barrier
```

> It may happen that sometimes you face that mage who just spam that **Spellsteal** and you just wanna `/slap` his face... well i have a solution for ya! When ever you feel you have advantage, feel free to press `alt-[Keybind]` to cancel your **Ice Barrier**. On my part im using `alt` modifier, do not use `shift` modifier its pretty much waste of keybind, because that case wont happen really often! (*check out how to keybind spells*).

<h3 align="center"> Mage Bomb </h3>

```
#showtooltip
/cancelaura ice block
/cancelaura slow fall
/dismount [mounted]
/cast [mod:shift, @focus] Mage bomb; Mage bomb
```
> Wow, there is soo much going on in this macro!
> - `/cancelaura ice block` : as a mage you want have at least one spell to cancel your **Ice Block**, on my part i decided to put it on my **Mage Bomb** (*mage bomb is the default... .. Mage Bomb* x) *it represent* (**Nether Tempest**, **Living Bomb** and **Frost Bomb**), but you can chose other spell on your side (*dont add this script on your ice block!!*).
