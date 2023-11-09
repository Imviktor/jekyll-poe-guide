---
layout: default
title: Cluster Jewels
description: How to craft cluster jewels
nav_order: 2
---

# Cluster Jewels

The cluster jewel is a very lucrative craft when the other players starts to build their builds. This method works for mid game when 
many players already have the currency and the level to invest in the cluster jewels.

  

## Large Jewels

### 8 Passives

The **large cluster jewels** are crafted using **prismatic fossils** 
<img src="https://www.poewiki.net/images/9/9f/Prismatic_Fossil_inventory_icon.png" width="25" height="25"/> and **primitive resonators** 
<img src="https://www.poewiki.net/images/d/dd/Primitive_Chaotic_Resonator_inventory_icon.png" width="25" height="25"/>. The idea is 
to hit at least 2 modifiers and use **exalts**<img src="https://www.poewiki.net/images/2/26/Exalted_Orb_inventory_icon.png" width="25" height="25"/> 
and **annulment** to get the 3rd skill. Jackpot if you get 3 skills with the fossils.

  

**Descriptive video**: [https://www.youtube.com/watch?v=MOYCROoD0u0](https://www.youtube.com/watch?v=MOYCROoD0u0)

| Type        | iLvl         | Cost | Looking for                                             |
|:------------|:-------------|:-----|:--------------------------------------------------------|
| Cold damage | 68 ~ 74      | 10co | 3 Skill mods: [Prismatic Heart, Doryani's Lesson, ...]  |
| Fire damage | 1 ~ (50*)/74 | 15co | Burning Bright, Prismatic Heart, Widespread Destruction |

(*) This can be expensive. Don't pay more than 30 ~ 40 co

Cold Simulation: [https://pastebin.com/jm2A9bGp](https://pastebin.com/jm2A9bGp)

### 12 Passives iLvl 84

These large cluster jewels can be crafted using fossils and looking for increased effect 35% ideally. % increased effect is also valid 
but then you need to **vaal** <img src="https://www.poewiki.net/images/2/2c/Vaal_Orb_inventory_icon.png" width="25" height="25"/> it 
and then use **tainted divine teardrop** <img src="https://www.poewiki.net/images/3/3f/Tainted_Divine_Teardrop_inventory_icon.png" width="25" height="25"/> 
to increase the tier to 35%. It really depends in the type of cluster.

| Type            | Cost  | Looking for                                             |
|:----------------|:------|:--------------------------------------------------------|
| Minion life     |  2d   | Attack & Cast speed, All elemental, Energy shield       |
| Spell damage    | 100co | All attributes, Strength, Intelligence                  |

You can also buy an already corrupted cluster with 25% effect and the desired mods and then apply the **tainted divine teardrop** 
<img src="https://www.poewiki.net/images/3/3f/Tainted_Divine_Teardrop_inventory_icon.png" width="25" height="25"/> but this is 
more unlikely to happen.

## Medium Jewels

The **medium cluster jewels** are crafted with **alteration** 
<img src="https://www.poewiki.net/images/d/d8/Orb_of_Alteration_inventory_icon.png" width="25" height="25"/> 
and **augment** <img src="https://www.poewiki.net/images/c/cb/Orb_of_Augmentation_inventory_icon.png" width="25" height="25"/> 
in a **iLvl:75+**. Use the item filter to highlight the item in case it hit a desired skill. If we reach at least one of the desired 
modifiers apply the **regal** <img src="https://www.poewiki.net/images/3/33/Regal_Orb_inventory_icon.png" width="25" height="25"/> . 
If it contains 2 skills, check price and finish. Otherwise, apply a **scouring** 
<img src="https://www.poewiki.net/images/5/51/Orb_of_Scouring_inventory_icon.png" width="25" height="25"/> and restart the process. 
It is not possible to achieve 2 skills with the **alt+aug** combo. Regal it is mandatory. The cost of the jewel might vary between 5 
and 15 co.


<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}">
<section class="tabs-wrapper">
    <div class="tabs-container">
        <div class="tabs-block">
            <div class="tabs">
{%
  include cluster_tab.html
  i="0"
  type="Critical" 
  ilvl="50+" 
  e="9Y2eVyKtK" 
  filter="press|quick|basics|reta"
  look="<li>Pressure Points + Quick Gateway</li><li>Pressure Points + Basics of pain</li><li>Pressure Points + Precise Retaliation</li>" 
%}

{% 
  include cluster_tab.html
  i="1"
  type="Burning" 
  ilvl="68+" 
  e="6ZkaG3jsG" 
  filter="blow|wast|flame|bright|flow|wrapped|decay"
  look="<li>Flow of life + Burning bright</li><li>Flow of life + Wrapped in flame</li><li>Flow of life + Fan of the flames</li><li>Blowback + Wasting affliction</li><li>Fan the flames + Wasting affliction</li><li>Fan the flames + Blowback</li><li>Burning bright + Brush with death</li>" 
%}

{% 
  include cluster_tab.html
  i="2"
  type="Chaos DoT" 
  ilvl="68+" 
  e="0B8qPXwFg" 
  filter="wast|flow|decay|brew"
  look="<li>Flow of life + Student Decay</li><li>Flow of life + Brewed for potency</li><li>Student Decay + Brewed for potency</li><li>Circling Oblivion + Wasting Affliction</li>" 
%}

{% 
  include cluster_tab.html
  i="3"
  type="DoT" 
  ilvl="68+" 
  e="gXWMPZKFQ" 
  filter="wast|flow|decay|brew|brush"
  look="<li>Flow of life + Student of Decay</li><li>Flow of live + Brewed for potency</li><li>Flow of live + Brush with death</li><li>Student of Decay + Brewed for potency</li><li>Wastig affliction + Brush with death</li>" 
%}

{% 
  include cluster_tab.html
  i="4"
  type="Minion life" 
  ilvl="68+" 
  e="lXjk0nnFV" 
  filter="renew|blessed"
  look="<li>Renewal + Dread March</li><li>Renewal + Feasting fiends</li><li>Blessed Rebirth + Renewal</li><li>Blessed Rebirth + Feasting fiends</li><li>Blessed Rebirth + Life from death</li><li>Blessed Rebirth + Hulking corpses</li><li>Blessed Rebirth + Dread March</li>" 
%}

{% 
  include cluster_tab.html
  i="5"
  type="Herald" 
  ilvl="75+" 
  e="PdDgGk7hL" 
  filter="purposeful"
  look="<li>Purposeful Harbinger + Empowered envoy</li><li>Purposeful Harbinger + Hearldry</li><li>Purposeful Harbinger + Lasting impression</li><li>Purposeful Harbinger + Endbringer</li>" 
%}
            </div>
        </div>
    </div>
</section>


{: .warning }
> These are examples for the ToTA league. It might vary depending on the builds. It's highly recommended to check the price before crafting and explore and discover new crafts. To do so, just access PoE Ninja and check the most played builds.