# Avenging Crusader

[![Tooltip](https://user-images.githubusercontent.com/4565223/39913530-79e7de88-5502-11e8-918c-5595752105fe.png)](https://beta.wowdb.com/spells/216331-avenging-crusader)

- Tier 90 talent
- **Replaces [Avenging Wrath](../../AvengingWrath.md)**
- Throughput cooldown
- 10,000 mana
- **Static** cooldown (unaffected by Haste)
- Instant - GCD

## About

Replaces [Avenging Wrath](../../AvengingWrath.md), does not gain any of its original benefits.

Increases the damage done by [Crusader Strike](../../CrusaderStrike.md), [Judgment](../../Judgment.md) and auto-attacks by 30%.

The cooldown recovery rate of [Crusader Strike](../../CrusaderStrike.md) and [Judgment](../../Judgment.md) is increased by 30%. This happens in-game by making every 1 second of cooldown elapse in 0.7 seconds (the cooldown ticks are quicker). The CDR also applies to abilities already on cooldown when AC is cast.

[Crusader Strike](../../CrusaderStrike.md) and [Judgment](../../Judgment.md) heal up to 3 injured allies for 175% of the damage dealt with those abilities. This healing is also replicated to beacons.

Target selection is **not** a [smart heal](https://wow.gamepedia.com/Smart_spell). It picks up to 3 injured allies at random, regardless of the health they're missing. If there are fewer than 3 injured players, it will randomly select full health players. The max range of the heals is 40 yards, which is unaffected by [Rule of Law](../30/RuleOfLaw.md).

You can use [this spreadsheet](https://docs.google.com/spreadsheets/d/1rkdTSbG3k3diyh5kak5ljS0Be4mrZbaACM2w2ImCxvM/edit#gid=0) to play around with different Haste values and see how Avenging Crusader interacts with [Crusader's Might](../15/CrusadersMight.md). In most cases [Crusader's Might](../15/CrusadersMight.md) will at best get you 1 more [Holy Shock](../../HolyShock.md) or [Light of Dawn](../../HolyShock.md) cast.

## Interactions

| Effect | Applicable | Explanation |
| ------ | :--------: | ----------- |
| Beacon transfers | 100% | Single target efficiency |
| Intellect | ✔ | CS/J scale with Intellect |
| Critical Strike | ✔ | If CS/J crit, the heal also [increases](https://user-images.githubusercontent.com/4565223/39959723-1ed3419e-5616-11e8-8986-6d66202f691f.png) |
| Haste | ✔ | Static cooldown, but Haste allows you to cast more spells that transfer |
| Mastery | ❌ | CS/J and AC's heal do not scale with Mastery |
| Versatility | ✔ | CS/J scale with Versatility |

## Bugs

- Swapping to Avenging Crusader while [Avenging Wrath](../../AvengingWrath.md) is on cooldown, allows you to cast AC right away #1
- Avenging Crusader has inconsistent transfer rates #3
