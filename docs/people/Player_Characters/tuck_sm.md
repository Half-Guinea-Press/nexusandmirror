---
hide:
  - toc
  - navigation
---

<style>
.slidecontainer {
  width: 50%;
}

.slider {
  -webkit-appearance: none;
  width: 100%;
  height: 25px;
  background: #d3d3d3;
  outline: none;
  opacity: 0.7;
  -webkit-transition: .2s;
  transition: opacity .2s;
}

.slider:hover {
  opacity: 1;
}

.slider::-webkit-slider-thumb {
  -webkit-appearance: none;
  appearance: none;
  width: 25px;
  height: 25px;
  background: #04AA6D;
  cursor: pointer;
}

.slider::-moz-range-thumb {
  width: 25px;
  height: 25px;
  background: #04AA6D;
  cursor: pointer;
}
</style>

# Tuck - ESTOC Class 4th Line 2nd Iteration

<div class="slidecontainer">
  <input type="range" min="0" max="123" value="50" class="slider" id="myRange">
  <p>Value: <span id="demo"></span></p>
</div>

<script>
var slider = document.getElementById("myRange");
var output = document.getElementById("demo");
output.innerHTML = slider.value;

slider.oninput = function() {
  output.innerHTML = this.value;
}
</script>

??? abstract "Medium Vect Lawful Evil"

    Lvl 5 Gadgeteer(Futarist)/ Lvl 5 Fighter(Battlemaster)

    Str 18(+4) Dex 20(+5) Con 19(+4) Int 19(+4) Wis 14(+2) Chr 13(+1)

    Saves: Str +8 Dex +9 Con +8 vs Spell +8

    Init +2 | AC 19 | Spd 30<br>
    HP Max:123 | Hit Dice: 5d6/5d10

    Resistance: Exhaustion | Immune: Poison, Charmed, Sleep, Non-Magical Disease

    Skills: Athletics +7, Perception +7, Stealth +9, Survival +6, Tech +7

    Senses: Thermalsight(30ft)<br>
    Passive Perception: 17 | Passive Insight: 12

    Languages: Common

| Attack Name        | Atk/ Dam (Type)                   | Range  | Properties                          |
| :----------------- | :------------------------------   |:------ | :---------------------------------- |
| Antimatter Carbine | +10/2d6 :material-skull:          | 30/120 | Automatic, Blaster, Foregrip        |
| Blitz Cannon       | +10/2d8 :material-lightning-bolt: | 10/30  | Blaster, Hvy, Scatter(2d10), 2-Hand |
| Arm Blade (L Arm)  | +9/1d6+5 :material-sword:         | 5      | No Disarm, Fineese, Light           |

<div class="grid cards" markdown>

-   Action Economy

    === "Actions"
    
        Cloaking Device. Become invisible until next turn,can't use following rnd.
    
        Blink Button: teleport to seen unoccupied space within 15'
    
        Gravity Manipulator Levitate: target <=L Creature or obj <=500 lbs. w/n 30', move/orient tgt, 1 min dur, Con save DC 15<br>
    
    === "Bonus Actions"
    
        Flashbang. Within 5 feet no reactions till next turn, can't use following rnd
    
        Forcefield Projector. Till next turn AC+3 (Int), can't use following rnd.
    
        Grappling Hook. Seen target loc w/n move no opp atk,  can't use following rnd.
    
        Second Wind: 1d10+5 (per S/L rest)
    
        Gravity Manipulator Repel: Tgt pushed 60' if T/S, 30' if M, 15' if L, obstacle and tgt take 2d8 bludgeoning
    
    === "Reactions"
    
        Grappling Hook. Seen target loc w/n move no opp atk,  can't use following rnd.
    
        Parry: Upon melee damage expend s. die to reduce damage 1d8+5(Dex)
    
        Feedback Electrodes: ipon taking damage from target w/n 5' deal 2d6 lighting dammage

-   Notes

    === "Maneuvers"
    
        Superiority Dice: 4d8
    
        Maneuvering Attack: upon hit expend s. die, add to dam, friendly use reaction to move 1/2 spd w/o opp atk from hit opponent
    
        Precision Attack: upon atk roll expend s. die, add to atk, can be befor or after atk roll
    
    === "Adv. Subroutines"
    
        One active at a time
    
        Genetic Algorithm: Cumulative +1 dam reduction max +3(Int) when taking damage, reset 1 min
    
        Heatmap: when adv on atk add prof bonus to damage
    
        Neural Network: cumulative +1 atk bonus max +3(Int) when miss, reset 1 min

    === "Fighter"
    
        Close Qtr: Ignore 1/2 & 3/4 cover w/n 30', no d.adv w/n 5' of attacker
    
        Action Surge: Take 1 additional action (per S/L rest)
    
        Extra Attack: Take 2 atks when taking atk action

    === "Weapon"

        Overcharge: Per turn blaster dam +2 die

        Foregrip: When used 2-handed +50'/+200'

        Scatter: Higher damage within 5'

</div>
