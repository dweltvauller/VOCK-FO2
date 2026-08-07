# Lara — VA Script
**Character:** Lara, leader of the second gang (the Slags) in the Den

**Total recordable lines:** 78 (`larad1`–`larad78`)

---

> **Direction:** A tough, businesslike gang leader in her twenties or thirties, running a crew
> fighting a turf war against a rival gang led by Tyler. She's wary of strangers by default —
> blunt, transactional, quick to size someone up as either useful or a waste of her time — but
> warms into a genuine strategist and ally once the player starts doing real work for her. There's
> a personal edge underneath the business: Tyler wronged her brother once, and beating him is
> partly payback, not just territory. If the plan goes well she's triumphant and openly grateful;
> if it falls apart (Metzger dies, the player skips a step, or the player betrays her) she turns
> bitter and sarcastic rather than sad. If genuinely crossed, she goes cold and hostile, ready to
> fight.

---

## Greeting

`larad1:` The name's Lara; I run this gang. You better not be here to cause trouble or you're in for a world of hurt.

*Repeat visit.*

`larad2:` Hi again. Need something?

## Confused Response
*Plays if the player gives a nonsense/low-intelligence answer.*

`larad3:` We don't have any doctors in town and I can't help you.

`larad4:` Sorry, I still don't understand.

## Asking About Vic

`larad5:` The name doesn't ring a bell, but then again I don't keep track of who comes in and out of town. Check with Becky. Everyone ends up going through there. She might know.

## Just Looking Around

`larad6:` If you didn't come to the Den for a specific reason you should probably leave. It's not very safe around here.

*Repeat visit.*

`larad7:` Oh, okay.

## "I Can Handle Myself"

`larad8:` No doubt. Otherwise you probably wouldn't have made it here alive.

*Repeat.*

`larad9:` Uh, yes, so I heard. You said that already.

## Got Any Work?

`larad10:` Well it depends on what you're good at. There is something I'm curious about. If you can find out, I'll pay you a bit.

*Repeat.*

`larad11:` As I said, I'm looking for more information on a certain something... or someplace. I'll pay of course.

## Declining For Now

`larad12:` Let me know if you change your mind.

## The Job: What's In The Church?

`larad13:` Well, there's a church east of here. Metzger has some people guarding whatever is inside. Find out what and I'll pay you $200.

`larad14:` Thanks. Don't get in a fight... yet. I have a plan.

## Reporting What's In The Crates

`larad15:` What's that?

`larad16:` That makes sense actually. Thanks. Here's your money.

`larad17:` I've seen caravans from Vault City come in and then some of it gets picked up by caravans from New Reno.

`larad18:` New Reno is the drug capital around here. They have to get the raw materials to make their drugs from somewhere, right? It seems like they're getting some, or all of it, from Vault City.

`larad19:` Not sure exactly. Somewhere to the south I think. I've never been there, I just see their caravans stop by once in a while - once in a long while.

## A Second Job

`larad20:` You looking for some more quick and easy cash? $50. Easy money.

`larad21:` I need you to check with Metzger to see if he'd be okay if Tyler and I settled some old matters. He'll understand what I mean.

`larad22:` Because I don't want Tyler to see any of my people going into or out of Metzger's place. I don't want to tip our hand.

*Same beat, pressed further.*

`larad23:` Don't you get it? If Tyler sees me all of a sudden talking to Metzger he might catch wind of something fishy.

## Following Up On The Crates

`larad24:` So did you find out what's in there?

## Following Up On Metzger's Answer

`larad25:` So did you talk to him yet? What did he say?

`larad26:` Great. I was hoping as much. I hear he's been complaining about them lately. Here's your money.

`larad27:` I have one more job for you. I'm not sure how you'll do it, but since you were able to get inside maybe they trust you.

`larad28:` I'm sure you can figure something out.

## Finding A Weakness

`larad29:` We can't take them at their present strength. They have extra funding and slightly outnumber us. If you can find some kind of weakness we could use to balance out the odds or something we can exploit...

`larad30:` We'll give you $150. There's no way we can get close enough to find out by ourselves.

`larad31:` I don't know. That's why I'm asking you to help.

## Reporting The Weakness

`larad32:` Did you find anything?

## The Attack Plan

`larad33:` Excellent! They're sure to leave a skeleton crew. Those should be good odds. We'll take out those at the party after we hit the church.

`larad34:` I don't think so. You'll have to come with us if you want your money. You won't have to fight but just to be sure it's not a trap. We'll give you $300 total.

*Repeat, waiting on the player.*

`larad35:` You ready?

## Final Countdown

`larad36:` Okay, but we've got to act soon so don't take too long or we'll ruin our chance.

## Backing Out (Coward Route)

`larad37:` You don't have to fight. Easy money.

*Repeat, checking back in.*

`larad38:` Well, have you changed your mind?

## If The Player Never Shows Up
*Random floats — plays when the fight goes ahead without the player and it goes badly.*

`larad50:` Because of you we blew our chance.

`larad51:` Coward!

`larad52:` You get nothing.

`larad53:` It was probably a trap anyhow.

`larad54:` Sorry, you're not reliable.

`larad55:` I can't trust you.

## Victory
*Random floats — plays after Lara's gang wins the war.*

`larad56:` We did it!

`larad57:` Thank you for your help.

`larad58:` Special thanks to you!

`larad59:` I've finally paid Tyler back for what he did to my brother.

`larad60:` Thank you again.

## Metzger Is Dead
*Random floats — plays if Metzger dies before things are resolved.*

`larad61:` Now that Metzger's dead, I don't know what'll happen.

`larad62:` Maybe we should just pack up.

`larad63:` Did you hear Metzger died? I don't know what to do now.

`larad64:` What's going to happen to the Den now? Maybe something better.

`larad65:` This could actually be for the better.

## Turning Hostile
*Plays instead of her normal greeting when she's about to fight the player. One line per player gender.*

`larad66:` Bastard!

`larad67:` Bitch!

## Paying Off The Coward Route

`larad39:` Thanks. Here's your money and $100 extra.

## Gang Wiped Out The Wrong Way
*Plays if the player killed off Tyler's gang directly instead of following Lara's plan.*

`larad40:` Did you kill Tyler and his guards? How are we supposed to prove ourselves to Metzger? He'll never hire us now. That was our only chance.

*Alternate version of the same beat.*

`larad41:` We don't have any work. Someone killed off Metzger's guards and now he won't talk to us. He thinks we did it. Oh well.

## Blame For The Ransacking
*One plays depending on which step the player skipped before wiping out the gang.*

`larad42:` I told you we would go together. Since no one was there to watch the place, it got ransacked and now Metzger's madder than hell.

`larad43:` I told you to find a weakness, not kill them! Since no one was there to watch the place, it got ransacked and now Metzger's madder than hell.

`larad44:` Damn it! I told you to ask Metzger, not to kill them! Since no one was there to watch the place, it got ransacked and now Metzger's madder than hell.

`larad45:` Damn it! I told you not to attack them! Since no one was there to watch the place, it got ransacked and now Metzger's madder than hell.

## Ambient Grumbling
*Random floats — plays on later visits after the gang was wiped out the wrong way.*

`larad68:` You really know how to screw things up, don't you?

`larad69:` We don't need any more of your help.

`larad70:` Go bother someone else.

`larad71:` Metzger better not take anything out on us.

`larad72:` I'm sorry. I can't help you.

`larad73:` Can't talk. I'm trying to figure out what to do now.

`larad74:` I hope Metzger doesn't think we were involved.

`larad75:` What are we going to do now?

`larad76:` We better leave soon in case Metzger thinks we killed his guards.

`larad77:` You ever been to New Reno? Maybe we'll head there - or north.

## Rallying The Gang
*Float — plays as Lara leads her gang into the fight.*

`larad78:` Alright! Let's go! Everyone follow me!

## Taking The Church

`larad46:` Alright, we took care of the skeleton crew here at the church, but there still is Tyler and his cronies over in the Residential area. They should be pretty drunk by now and we can easily catch them off guard. You ready to finish this?

*Repeat, once the player is ready to move on Tyler.*

`larad47:` You ready to take Tyler and his crew out?

*If the player strays too far without checking in.*

`larad48:` Well, don't stray too far. We need to finish this tonight or we'll do it without you.

`larad49:` We did it. I can't believe it! We're heading back to the church to take charge. Meet us back there for your reward.

---

*End of script — 78 lines total. Tag numbers follow ascending message-ID order, not this document's topical grouping.*
