---
description: >-
  A Champion Monster is a monster dynamically summoned by the server after
  certain conditions are met.
---

# 🏆 Champion Monster

<figure><img src="../.gitbook/assets/mmmm.gif" alt=""><figcaption><p><mark style="color:red;"><strong>Champion Monster in Action</strong></mark></p></figcaption></figure>

## **Characteristics**

* When a **Champion** appears, it is announced to all players on the map.
* **Champions grant 30 times more experience and have 10 times the item drop rate.**

***

## **Summoning Formula**

The calculation applied when killing a monster to determine whether a Champion is summoned is as follows:

```
mathematicaCopiarEditarSummon Chance += [(Monster Level / 100) * Number of Players on the Map]%
```

### **Example:**

\
If you are in a group with 5 friends on the map and kill a level 25 monster **25 times**, then:

The chance for this monster to become a Champion is **1.25%**.

If the summoning does not occur, the next chance will increase to **2.50%**, and so on.

***

### **Champion Types**

* The type of Champion summoned is random. The table below shows the characteristics of each monster.

<table><thead><tr><th width="84.22222900390625">Type</th><th width="112.6944580078125">Damage</th><th width="99.6666259765625">Health</th><th width="131">Movement</th><th width="139.2222900390625">Resist</th><th>Feature</th></tr></thead><tbody><tr><td>Ventus</td><td>+700%</td><td>+900%</td><td>30</td><td>Wind = 90%</td><td>Nome</td></tr><tr><td>Solid</td><td>+700%</td><td>+900%</td><td>700</td><td>Earth = 90%</td><td>1% chance to break weapon</td></tr><tr><td>Necro</td><td>+700%</td><td>+900%</td><td>1500</td><td>Undead = 90%</td><td>Recovers 3% of mob's HP</td></tr><tr><td>Fairer</td><td>+700%</td><td>+900%</td><td>Uninterruptible</td><td>Fire = 90%</td><td>Has [Endure] active</td></tr><tr><td>Elusive</td><td>+700%</td><td>+900%</td><td>Uninterruptible</td><td>Nome</td><td>Takes no physical damage</td></tr></tbody></table>

## **System Specifications**

<table><thead><tr><th width="169">Specification</th><th>Type</th></tr></thead><tbody><tr><td>Link</td><td>None</td></tr><tr><td>Restrictions</td><td>Does not work with <strong>epic monsters</strong>, and only one <strong>Champion Monster</strong> is summoned at a time while another is still alive on the same map.</td></tr></tbody></table>
