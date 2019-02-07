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

> And here is probably my favorite macro, it allows you to do exactly 3 things, yes 3! Im rewrote this code into a pseudo-code for for a better understanding.
```Pascal
If (use_macro_without_modifier)
  Then use_alter_time
  If (use_macro_without_modifier)
    Then back_in_time
  Else If (use_macro_with_modifier)
    remove_alter_time And stay_in_last_spot

If (use_macro_with_modifier)
  Then use_presence_of_mind And use_alter_time
  If (use_macro_without_modifier)
    Then remove_alter_time And stay_in_last_spot
  Else If (use_macro_with_modifier)
    Then back_in_time

End
```
