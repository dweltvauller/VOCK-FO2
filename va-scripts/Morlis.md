# Morlis — VA Script
**Character:** Morlis, one of the Chosen One's aunts, Arroyo village

**Total recordable lines:** 26 (`mor1`–`mor27`, `mor19` intentionally skipped)

---

> **Direction:** Elderly adult female, perpetually busy and perpetually put-upon — treats her own nephew/niece, the Chosen One of the village, like an errand-running child who's always underfoot. Impatient and dismissive as a baseline, sharpening into real scorn if she's crossed (caught being stolen from, or asked to just hand things over for free). As the game's time limit closes in, let some genuine dread creep into the "people are dying" lines — she's not just nagging anymore, she means it.

---

## Greeting Floats
*Plays instead of full dialogue on approach, or as talk_p_proc's fallback once nothing else applies. Varies by PC sex.*

`mor21:` Why do you bother me, nephew? Can't you see I'm busy?

`mor22:` Why do you bother me, niece? Can't you see I'm busy?

## Asking About the Flint

`mor1:` What is it? You know I have a lot to do!

`mor2:` Mynoc said what? Out with it, child!

`mor3:` I do. You want some, is that it?

`mor4:` Well... I want three doses of healing powder. Bad times are coming and I'm going to be ready. Bring them to me and you can have the flint. Now get to it!

## Turning In the Healing Powders

`mor5:` Now don't waste my time. Do you have the powders?

`mor6:` Here is the flint. Now off with you! I don't have time to gossip.

`mor7:` Again you waste my time, worthless nephew! How did you ever become the Chosen One?

## Persuasion — "Just Give Me the Flint"
*Speech-check outcome when the PC argues she should hand over the flint and let them keep the powders for themselves.*

`mor10:` Well... Oh, very well. Here is the flint. I wish you a safe journey, child.

`mor11:` No, I don't. Now stop wasting my time and get out of here!

## Caught Stealing the Flint
*Only reachable if the PC is caught pickpocketing her — drops straight into dialogue instead of a normal greeting. `mor9` plays if she's caught the PC a second time and gives up the flint outright.*

`mor8:` What do you think you are doing, child? This is no way for the Chosen One to act. Now get out of my sight!

`mor9:` If this flint is so important that you are willing to disgrace the name of the Chosen One, then here. Take the flint and get out of my sight.

## Quest Check-Ins — Timeline Progress
*Each pair of lines corresponds to one of the game's escalating time-limit checkpoints on a later visit.*

`mor12:` So you've returned. Did you find the holy Thirteen?

`mor13:` Then get yourself out of here and find it! People are depending on you!

`mor14:` Well, here you are again. Have you once again failed to complete your quest?

`mor15:` Then get yourself out of here and don't come back until you do! Why waste time coming back here, when you could be using that time to continue your search!?

`mor16:` The fact that you are standing here must mean that you have completed your quest. You wouldn't waste precious time returning here empty-handed, would you?

`mor17:` So, child. Once again you stand before me. Are you empty-handed yet again?

## Final Warning — the GECK
*Includes "Chosen One" as part of the recorded line — read the name in naturally, not as a separate insert.*

`mor18:` Listen, Chosen One. People are dying, cattle are dying, and crops are failing. Everyone is either hungry, sick, or both. Our time draws near. If you do not find the GECK soon, we are doomed. Do you understand me?

`mor20:` Then get yourself out of here and find the GECK! People are depending on you!

## If the Flint's Already Gone
*Variant apology/scolding lines depending on whether the flint was stolen out from under her or already handed over earlier, and whether the powders got turned in along the way.*

`mor23:` Well, I seem to have misplaced the flint. Oh well, at least I got my powders. Now off with you! I don't have time to gossip.

`mor24:` Well, I can't seem to find the flint. I'm sure you took it from me when I wasn't looking though. I caught you before. Now off with you! I don't have time to gossip.

`mor25:` Well... Oh, I'm sorry but I seem to have misplaced the flint. I wish you a safe journey though, child.

`mor26:` I already gave you the flint, stupid. Now stop wasting my time and get out of here!

`mor27:` I already gave you the flint, stupid. Oh well, at least I got my powders. Now off with you! I don't have time to gossip.

---

*End of script*
