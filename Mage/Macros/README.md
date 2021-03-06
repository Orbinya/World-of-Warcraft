# Macros

<h3 align="center"> Freeze - Summon Pet </h3>

```
#showtooltip
/cast [nopet] Summon Water Elemental; Freeze
```

> This macro combine 2 spells, when ever you have no pet, this will allows you to summon it; however if your pet is on the field the macro will perform freeze (*pet nova*).

<h3 align="center"> Polymorph </h3>

**Macro 1**

```
#showtooltip
/cast [mod:shift, @focus] Polymorph; Polymorph
```

**Macro 2**

```
#showtooltip
/cast [@arena1] Polymorph
```
> As you can see i dont have anything special on my **Polymorph** macro. The variant `/cast [@arena1] Polymorph` is very usefull when you are playing on 3v3 bracket. It allows to focus a specific player without switching it. On my side i have 3 of them for `@arena1`, `@arena2` and `@arena3`.

<h3 align="center"> CounterSpell </h3>

**Macro 1**

```
#showtooltip
/stopcasting
/cancelaura Ice Block
/cast [mod:shift, @focus] Counterspell; Counterspell
```

> Lets study a bit this macro, beacause it's a really usefull one. 
> - `/stopcasting` : when ever a player is casting a spell, you can imediatly interrut him on cast, even when you are casting on your own. Normally you have to walk to stop your cast and then press **Counterspell**, but with this macro you just have to press it.
> - `/cancelaura Ice Block` : it may happen that you are inside your block and someone cast a spell, its the same logic as before, press your macro allows you to get out of it and lock on cast.

**Macro 2**

```
#showtooltip
/stopcasting
/cancelaura Ice Block
/cast [@arena1] Counterspell
```

> Same as **Polymorph** macro, create 3 of them for `@arena1`, `@arena2` and `@arena3`. If you keybind them you will be greatly reconstituted for this, beacause when ever you will face a hunter, you can replace `@arena1` by `@arenapet1`, which will allows you to **Counterspell** his pet!

> *But why CS pet ?* Well, I think you know that the hunter has a pet, and if he's a cunning specialist, he can order his pet to use [**Roar of Sacrifice**](https://www.wowhead.com/spell=67481/roar-of-sacrifice) (*RoS*), but he will not be able to use if his pet is silenced!

<h3 align="center"> Ice Barrier </h3>

```
#showtooltip Ice Barrier
/cancelaura [mod:alt] Ice Barrier
/cancelaura [mod:alt] Power Word: Shield
/cast [nomod] Ice Barrier
```

> It can happen that sometimes you meet this mage who just spam **Spellsteal** and you just wanna `/slap` his face... well i have a solution for ya! When ever you feel you have advantage, feel free to press `alt-[Keybind]` to cancel your **Ice Barrier**. On my part im using `alt` modifier, do not use `shift` modifier its pretty much waste of keybind, because that case wont happen really often! (*check out how to keybind spells*).

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
    Then remove_alter_time And stay_in_last_spot

If (use_macro_with_modifier)
  Then use_presence_of_mind And use_alter_time
  
  If (use_macro_without_modifier)
    Then remove_alter_time And stay_in_last_spot
  Else If (use_macro_with_modifier)
    Then back_in_time
```

<h3 align="center"> Ice Lance </h3>

```
#showtooltip
/cast [@mouseover] Ice Lance
```
> This macro is a really usefull tool, but it need some time to master it. It will allows you to shoot your **Ice Lance** on your cursor's target. It's handy when you want to kill **Psyfiend**, Shaman totems or Druid's **Wild Mushroom**.

<h3 align="center"> Arcane Brilliance </h3>

```
#showtooltip
/cast [@player] Arcane Brilliance
/tm [@player] 1
/tm [@party1] 2
/tm [@party2] 3
```

> Just by rebuffing you can put marks on the entire team. Here is the table of all marks :

| Symbol | Index |
|:------:|:-----:|
| ![Star](https://vignette.wikia.nocookie.net/wowwiki/images/f/fd/IconSmall_RaidStar.png/revision/latest?cb=20071030173506) | 1 |
| ![Circle](https://vignette.wikia.nocookie.net/wowwiki/images/2/23/IconSmall_RaidCircle.png/revision/latest?cb=20071030173533) | 2 |
| ![Diamond](https://vignette.wikia.nocookie.net/wowwiki/images/2/2f/IconSmall_RaidDiamond.png/revision/latest?cb=20071030173555) | 3 |
| ![Triangle](https://vignette.wikia.nocookie.net/wowwiki/images/8/86/IconSmall_RaidTriangle.png/revision/latest?cb=20071030173731) | 4 |
| ![Moon](https://vignette.wikia.nocookie.net/wowwiki/images/5/5e/IconSmall_RaidMoon.png/revision/latest?cb=20071030173751) | 5 |
| ![Square](https://vignette.wikia.nocookie.net/wowwiki/images/d/df/IconSmall_RaidSquare.png/revision/latest?cb=20071030174116) | 6 |
| ![Cross](https://vignette.wikia.nocookie.net/wowwiki/images/e/e0/IconSmall_RaidCross.png/revision/latest?cb=20071030173844) | 7 |
| ![Skull](https://vignette.wikia.nocookie.net/wowwiki/images/7/73/IconSmall_RaidSkull.png/revision/latest?cb=20071030174221) | 8 |
