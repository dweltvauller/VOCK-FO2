# Doctor Andrew — VA Script
**Character:** "Doctor" Andrew, unlicensed medic running the Auto-Doc, Vault City

**Total recordable lines:** 57 (`andr1`–`andr57`)

---

> **Direction:** Andrew isn't really a doctor — he operates a loaner Auto-Doc ("the ol' Doctor") out of a back room and charges for the privilege. Scruffy, folksy, a bit of a huckster, but not malicious: he genuinely thinks the machine mostly works, and gets nervous when it doesn't. Casual grammar throughout ("gonna," "ain't," "ol'," dropped g's). Warm and eager when there's money on the table, sheepish when the autodoc misbehaves, and morbidly matter-of-fact during the botched-surgery lines. Middle-aged male voice, backwoods/rural cadence.

---

## Greeting — Injury Assessment
*Andrew's opening line on approach, chosen by how hurt the PC looks. `andr5` always follows whichever severity line plays.*

`andr1:` Looks like you've seen some fighting, friend. You here to get patched up?
`andr2:` Whoa... looks like you've seen some serious action, friend. You here to get patched up?
`andr3:` Whoa... looks like you've been in some heavy fighting, friend. You here to get patched up?
`andr4:` Holy...! You're bleeding all over the floor! You here to get patched up?
`andr5:` You here to get patched up?

## Healing Cost Quote — Auto-Doc Fixed
*PC asks to be healed. Line trails off before the game inserts the price.*

`andr6:` All right... from the looks of it, it's gonna be pricey. (Scribbles $[PRICE] onto a blood-stained prescription pad.) You got the cash, then you're good to go.

## Healing Cost Quote — Auto-Doc Broken
*Merged recording — `andr6` is repeated.*

`andr7` *(merged recording)*:  All right... from the looks of it, it's gonna be pricey. (Scribbles $[PRICE] onto a blood-stained prescription pad.) You got the cash, then you're good to go. No guarantees with the ol' Doc in the back room, of course...

## Healing Accepted — Self
*PC pays (full price or successful haggle) and agrees to be healed. `andr8` only plays if the PC haggled the price down.*

`andr8:` Well... all right. That sounds fair.
`andr9:` Let's get to it, then. I'll just hook you up to the ol' Doctor here... slip your arms into the slots there, and I'll tighten the braces and secure the clamps...

## Healing Successful — Self
*The Auto-Doc works. PC is healed.*

`andr10:` All right! Knew the ol' Doctor wouldn't let me down.

## First Bonus Ride Offered
*PC has full HP but rides the Auto-Doc anyway. Andrew warns there's a one-time HP bonus available, with a catch.*

`andr11:` Uh, well now, that might not be the safest thing for you, friend. Seems like you already took a few trips in the ol' Doctor from the way you talk. But if you want to...
`andr12:` Uh... how you feel? Any better? Any worse?

## Repeat Ride — Outcome
*PC rides again after already taking the bonus or penalty ride. `andr56` (see Repeat Autodoc Ride After Toe Removal) plays instead of `andr13` if returning from the mutated-toe path.*

`andr13:` Uh, well, I warned you...
`andr14:` Uh-oh. Looks like the ol' Doctor took a pound of flesh this time.

## Refuses Robobrain
*PC has Robobrain in the party and asks about healing them specifically; Andrew can't help with mechanical companions.*

`andr15:` Well, now I ain't a mechanic, so I can't help that brain whazzit you got with you. Sorry, friend.

## Healing Cost Quote — Larger Party
*Three or more party members, at least one injured. Price is tripled. Line trails off before the game inserts the price; the tail changes slightly if Robobrain is present (untagged, no recording needed either way).*

`andr16:` Well, now... tell you what.

## Healing Accepted — Party
*PC pays to heal the whole party (also reused for the mutated-toe procedure — see Toe Removal Accepted). `andr8` (reused) only plays first if the PC haggled.*

`andr17:` Let's get to it, then. I'll just hook up the ol' Doctor here... Have 'em lay down, and I'll tighten the braces and secure the clamps...

## Healing Successful — Party
*All injured party members are healed in one visit.*

`andr18:` There, all stitched up! Knew the ol' Doctor still had some life left in 'im.

## What Is This Place?
*PC asks about the building.*

`andr19:` This here's the common body shop for Vault City. Me an' the ol' Doctor in the back patch up whoever needs some attention.

## About the Auto-Doc
*PC asks about "the ol' Doctor" specifically. `andr20` plays if it's currently broken; `andr21` plays instead if the PC already repaired it. (The old shared intro line for this node was removed — each of these two now plays correctly on its own, matching the actual repair state.)*

`andr20:` It can be a little ornery sometimes, but mostly it does its job. Mostly.
`andr21:` Been running a lot smoother lately, which is good. Cuts down on repeat visitors.

## Thanks for the Repair
*PC previously fixed the Auto-Doc for free and Andrew acknowledges it.*

`andr22:` Eh... well... thank you very much. That was decent of you to volunteer to fix it like that.

## Demands Payment for Repair
*PC asks for money for having fixed the machine; Andrew refuses, backed by the guards nearby.*

`andr23:` Hell, no! I didn't ask you to fix it, so you don't get jack. I wouldn't push your luck as long as the guards are in earshot.

## Return to Topics
*Falls back to the main topic list. `andr24` plays if returning from the repair conversation; `andr25` is the default "what do you need" prompt.*

`andr24:` So... was there something else I could help you with?
`andr25:` What can I help you with?

## Combat Implants — Introduced
*PC first mentions the implant schematics.*

`andr26:` Combat implants? What do you mean?

## Combat Implants — Explained
*Andrew realizes what's being asked and figures out he could perform the operation with parts from a suit of Combat Armor.*

`andr27:` Huh. Well, I suppose with help from the ol' Doctor I could do that operation. Course, I'd need some impact plates and dissipaters first... might be able to pry some out of a suit of combat armor, if you can find one.

## Combat Implants — Risk Warning
*Andrew warns this is against Vault City policy and risky for him.*

`andr28:` Heh! You're serious then, I see. Well, now, this is a risky venture. The Citizens find out I'm using the ol' Doctor for this, an' they'll take it right back.

## Implant Menu
*PC asks which implant. `andr29` plays the first time; `andr30` (shorter) plays on repeat visits to this menu.*

`andr29:` Depends what you want. You want low impact, high impact, low thermal, or high thermal? Each one's got its price tag.
`andr30:` Which one? Low impact, high impact, low thermal, or high thermal?

## Dermal Impact — Low Quote
*PC asks about the basic Dermal Impact Armor implant.*

`andr31:` Standard Dermal Impact Armor takes the kick outta most explosions, punches, kicks, stuff like that. Say, 5%. I'll need to strip some Combat Armor for the plates, and it'll take two days to do the grafts. 7K oughta cover it.

## Dermal Impact — High Intro
*PC asks about the upgraded "high impact" version. `andr32` plays if the PC already has the basic dermal graft (its own standalone line); `andr33` is a merged recording for the "doesn't have it yet" branch.*

`andr32:` Well, technically, "high impact" is standard Dermal Impact Armor with extra assault-issue impact plates crammed under your skin.
`andr33` *(merged recording — PENDING SCRIPT CHANGE)*: Well, technically, "high impact" is standard Dermal Impact Armor with extra assault-issue impact plates crammed under your skin. So you're gonna need the basic dermal graft first.

## Dermal Impact — High Explained
*PC pushes for details on the upgrade.*

`andr34:` Well, I'm gonna need another set of combat armor to get the extra assault plates. Good thing is, the plates'll double the strength of the original grafts, so they'll absorb 10% of the kick. Except...

## Dermal Impact — High Cost and Risk
*Andrew names the price and timeline.*

`andr35:` It'll take a stretch, a few days at least, assuming the ol' Doctor don't mess it up. An' it's expensive. 40K, as I see it. Plus... well, it ain't gonna help your looks none.

## Dermal Impact — High Cosmetic Warning
*Andrew describes the visible side effects. `andr36` for a male PC, `andr37` for a female PC — each is a merged recording that now includes the charisma-hit follow-up in the same take.*

`andr36` *(merged recording)*: All the curves you got are gonna become right angles, near as I can tell. Shoving all those plates into your body means your charisma's gonna take a hit. You still game?
`andr37` *(merged recording)*: You're gonna be all blocky-looking when I'm done. Shoving all those plates into your body means your charisma's gonna take a hit. You still game?

## Phoenix Armor — Low Quote
*PC asks about the basic Phoenix (fire/laser/plasma resistance) implant.*

`andr38:` The Phoenix Implants take the bite outta fire, lasers and plasma burns... about 5%. I'll need to strip some combat armor for the thermal membranes, and it'll take two days for the operation. 10K oughta cover it.

## Phoenix Armor — High Intro
*PC asks about the upgraded "high thermal" version. `andr39` plays if the PC already has the basic Phoenix graft (its own standalone line); `andr40` is a merged recording for the "doesn't have it yet" branch.*

`andr39:` Well, technically, "high thermal" is standard Phoenix Armor with some thermal dissipaters layered over the membranes.
`andr40` *(merged recording — PENDING SCRIPT CHANGE)*: Well, technically, "high thermal" is standard Phoenix Armor with some thermal dissipaters layered over the membranes. So you're gonna need the basic Phoenix implant graft first.

## Phoenix Armor — High Explained
*PC pushes for details on the upgrade.*

`andr41:` Well, I'm gonna need to scavenge thermal dissipaters from another set of combat armor. Good thing is, the dissipaters'll double the thermal resistance, absorbing 10% of the bite. But...

## Phoenix Armor — High Cost and Risk
*Andrew names the price and describes the nastier side effects (blistering skin).*

`andr42:` It's gonna make your skin blister. Bad. You'll look a lot like that bubbly pre-war packaging material, so don't expect to be getting too many dates after this. And it's gonna cost you. 50K. Up front.

## Implant Surgery — Auto-Doc Malfunctions
*PC pays for any implant, but the Auto-Doc is broken and the surgery is aborted before it starts. `andr43` only plays if the PC haggled the price.*

`andr43:` Well... that sounds fair.
`andr44:` All right, let me just bolt you into the ol' Doctor here... hope the anesthesia reservoir ain't clogged again... maybe you better bite down on this piece of brahmin hide just in case.

## Implant Surgery — Result
*Surgery completes (successfully or not, depending on which implant/branch led here). Reuses `andr43`/`andr44` from the section above if this is a repeat of that same acceptance beat. Exactly one of the four result lines below plays, matching whichever implant was purchased.*

`andr46:` Well, they're in, I guess. Uh, about the swelling and soreness, I'm pretty sure that both are just temporary side effects. Oh, that stabbing sensation you feel when you move your arms and legs should fade in a few weeks.
`andr47:` Can you hear me? Whew. I didn't think there was any room left for those impact plates, but I was able to pry a lot of muscle tissue and cartilage out of the way. They're in a jar over there, if you want a souvenir.
`andr48:` Mercy... that was trial and error surgery if I ever saw it. I ended up having to amputate some of your nerve endings... that's the burning and itching sensation you're feeling right now. It'll probably fade in a few weeks.
`andr49:` I hope to heaven you can hear me right now. Look, when you regain feeling in your extremities, you'll feel an incredible itching sensation all over. Don't scratch! If you do, those pus-crusts over the drainage incisions'll burst and leave scars. Give 'em a few weeks to heal, okay?

## Healing Failed — Self
*PC pays for a regular heal, but the broken Auto-Doc fails instead. Reuses `andr8` (see Healing Accepted — Self) if the PC haggled.*

`andr50:` Let's get to it, then. I'll just hook up the ol' Doctor here... Let me tighten the braces and secure the clamps...
`andr51:` Hmmph. Looks like the ol' Doctor's being stubborn again. Piece of junk... still, I was glad I was able to pop the clamps before it started the exploratory surgery routine. Maybe it'll work better next time.

## Threatened Over a Failed Heal
*PC demands a refund after the botched heal; Andrew refuses, citing "no guarantees."*

`andr52:` Sorry, no guarantees, no refunds. You take your chances. If you got a problem with it, take it up with the guards.

## Mutated Toe Removal — Intro
*Only available if the PC has mutated (Bishop research plot). PC asks to have the growth removed.*

`andr53:` Well, I can try. No guarantees with the ol' Doctor in the back room, of course. It's gonna cost you... and there's no telling if the operation'll take. Might grow back.

## Mutated Toe Removal — Quote
*Andrew names the flat price for the amputation.*

`andr54:` Hmmmmm. Five hundred, and we'll call it a deal. I'm not authorized to perform amputations with the Auto-Doc, and it'll be my job if they find out.

## Toe Removal — Accepted
*PC pays and agrees to the procedure.*

*(Reuses `andr17` — see Healing Accepted — Party above. Reuses `andr8`, see Healing Accepted — Self, first if the PC haggled the price down.)*

## Toe Removal — Result
*The mutation is removed, successfully or not (there's a chance it grows back).*

`andr55:` That little friend of yours should be gone now. I hope. It's hard to squeeze out all of that mutated pus out of the bone marrow. Anyway, here you go.

## Repeat Autodoc Ride After Toe Removal
*PC rides the Auto-Doc again after having had the toe removed previously. Replaces `andr13` in that scenario.*

`andr56:` Uh, well, okay... but I warned you last time that it might not be safe.

## Fatal Autodoc Malfunction — Float, Part 1
*Scripted death sequence (broken Auto-Doc, triggered elsewhere). Andrew moves the PC to a new autodoc, then this float plays right as it starts.*

`andr57:` All right. Here we go.

## Fatal Autodoc Malfunction — Float, Part 2
*Final beat of the death sequence, right before the PC explodes. Plays after an untagged PC scream.*

`andr45:` Uh-oh.

---

*End of script — 57 lines total (`andr1`–`andr57`, tag numbers not necessarily sequential to reading order above)*
