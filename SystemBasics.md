# System Basics

This document describes the entire basis of the system. All other documents in this repo were either created with this system or support this system.

## Overview

The cost of a model starts with the Standard Attributes and the Racial Standard Model Cost. The Standard Attributes are an attribute block that is the baseline for all models in game. To get a model with the Standard Attributes, the cost is based on race. You can find the value in the Racial Standard Model Cost table. This racial cost represents the potential ability of each race, based on the racial maximums described next.

The racial cost is based on the attribute maximums that are found in the table below. **Ignore all the attribute maximums found within any of the Mordheim rulebooks and adhere to this table instead**. The costs are based on this standardization of maximum attributes for the models.

The next factor in cost of a model is the attributes they have over the Standard Attributes. The Attribute Cost Table describes the cost associated with an increase in each of the attributes. For example, each point of movement a model has over the standard 4 will increase the cost of the model by 5 GC. Some attributes, like wounds, do not scale linearly in the cost associated with each point.

Special rules also contribute to the cost of a model. Review the [Special Rules document](SpecialRules.md) for the cost associated with many of the special rules found throughout the warbands. If the special rules you're trying to associate a cost with aren't found within this document, come up with a cost that is similar to other special rules of similar strength and make sure that all the people you're playing with can agree on the cost. *Write it down* so that you don't have to have the same discussion twice (and consider contributing it to this project!).

Finally, experience is the last factor. Each experience point a hero starts with is worth a single gold crown.

*Note on rounding:* If your attribute cost comes out to have a decimal, truncate it before adding it to the total cost. Total costs need to be rounded to the nearest multiple of 5.

## The Calculation

The cost is a linear combination of the 4 different contributing factors described above. As noted, please round the total cost to the nearest multiple of 5.

`std + attr + SR + exp = total cost`

- **std**: The Standard Racial Cost from the table.
- **attr**: The cost associated withe additional attributes over the Standard Attributes
- **SR**: The special rules cost based on the value of all rules combined.
- **exp**: The cost of the model's starting experience, 1 GC per exp point.

See the sections below for all the important tables.


### The Standard Attributes

This stat block is the basic attributes that you receive on a model for pay its Racial Standard Cost

**M**|**WS**|**BS**|**S**|**T**|**W**|**I**|**A**|**Ld**
:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:
4|3|3|3|3|1|3|1|7

### Racial Attribute Maximums

**Race**|**M**|**WS**|**BS**|**S**|**T**|**W**|**I**|**A**|**Ld**
:-----|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:
**Human**|4|6|6|5|4|3|5|3|9
**Elf**|5|7|7|4|4|3|7|4|10
**Orc**|4|5|5|5|5|3|5|3|8
**Goblins**|4|5|5|4|3|3|5|3|7
**Beastmen**|5|5|5|5|5|3|6|3|8
**Vampire**|6|8|6|6|5|4|7|4|9
**Ghouls**|4|5|4|4|5|3|4|3|7
**Ogre**|6|6|5|6|6|5|4|5|8

### Racial Standard Cost

This table lists the costs of purchasing a model of a given race with the Standard Attributes. These costs represent the potential strength the unit has, as limited by the attribute maximums above.

**Race**|**Model Cost**
-----|-----
Human|25 GC
Elf|35 GC
Orc|30 GC
Goblins|15 GC
Beastmen|30 GC
Vampire|50 GC
Ghouls|20 GC
Ogre|60 GC

### Attribute Costs

This table has the cost of each additional point of an attribute. Note that wounds and attacks do not scale linearly, rather each point costs significantly more than the previous.

**Attribute**|**Cost**
-----|-----
M   |5 GC / point
WS  |2.5 GC / point
BS  |2.5 GC / point
S   |5 GC / point
T   |5 GC / point
W   |15/25/40 GC/ point
I   |2.5 GC / point
Ld  |2.5 GC / point
A   |10/20/30 GC / point

## Example Calculation
Here’s an examples for calculating the cost of a model. Here’s the unit profile for the Questing Knight from the Bretonnian Warband.

---
**Questing Knight**
**M**|**WS**|**BS**|**S**|**T**|**W**|**I**|**A**|**Ld**
:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:
4|4|3|4|3|1|4|1|8

*Starting Experience: 20*

**Special Rules:**

- **Leader** - Any warrior within 6” of the Way-Warden may use his leadership when taking a Leadership test.
- **Knights Virtue** - The model is a Chivalrous warrior who is superior to ordinary warriors. He never panics and breaks from combat and so does not have to pass a Leadership test for being all alone.

---


The Standard Cost for the Questing Knight comes from the fact that he is a human model. In the table, humans cost 25 gold crowns for a model with the standard attributes.

Attribute Cost is calculated based on what the unit has over the Standard Attributes. Note that when the model has the same attribute value as the Standard Attributes, there is no addition cost. The Questing Knight’s attribute cost can be calculated as follows:

Attribute | Cost
-----|-----
M|The Same – No Cost
WS|+1 – 2.5 cost
BS|The Same – No Cost
S|+1 – 5 cost
T|The Same – No Cost
W|The Same – No Cost
I|+1 – 2.5 cost
Ld|+1 – 2.5 cost

This table shows the Attribute cost for the Questing Knight is 12.5. In the case of decimal points, truncate to get the final result of 12 points for attributes.

The Special Rules cost for the Questing Knight comes from his two special rules. *Leader* is worth 5 gold crowns and *Knight's Virtue* is also worth 5 gold crowns. This totals to a Special Cost of 10 gold crowns. These costs are in the [Special Rules Document](SpecialRules.md).

Finally, the Questing Knight starts with 20 experience points, costing an additional 20 gold crowns.

Adding up the 25 standard cost, 12 for attributes, 10 for the special rules, and the 20 for experience comes out to 67. This total is not an even multiple of 5 and thus needs to be rounded. 67 rounds to 65, so the overall model cost of a Questing Knight is 65 gold crowns.


