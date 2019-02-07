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

<h3 align="center"> Alter Time </h3>

```
#showtooltip Alter Time
/cancelaura [mod:shift] Alter Time
/cast [nomod] Alter Time
/cast [mod:shift] Presence of Mind
/cast [mod:shift] Alter Time
```

> And here probably my favorite macro, it allows you to do exactly 3 things, yes 3!
> 1. If you use this macro without any modifier, its just gonna use your Alter Time
>   - If you repress it without any modifier, you will back in time.
>   - Elsewhere if you press it with the modifier `shift`, you will acctualy cancel your Alter Time. Its really usefull when someone is waiting for you at the location you used your **Alter Time**.
> 1. If you use this macro with the modifier `shift`, you will actually use your **Presence of Mind** and then right after use your **Alter Time**.
>   - If you
