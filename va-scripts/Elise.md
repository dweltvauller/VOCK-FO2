# Elise — VA Script
**Character:** Elise, Ranger Chief, New California Rangers (scelise, NCR Map 1)

**Total recordable lines:** 56 (`elise1`–`elise56`)

---

> **Direction:** A confident, no-nonsense young woman who leads a small anti-slavery militia — the New California Rangers — out of the edge of NCR. Businesslike and measured by default; she's used to giving orders and having them obeyed, and it comes through even in casual conversation. Warms up considerably and sounds genuinely moved once the PC proves themselves — freeing slaves, wiping out a slaver camp. Turns cold and clipped fast with anyone wishy-washy or morally indifferent about slavery, and goes flatly hostile — sharp, warning, not shouting — if the PC turns out to be a slaver themselves or has wronged someone close to her.

---

## Greetings

`elise1:` What do you want?

`elise2:` You again?

## Referred by an Ally
*If Karl or Doc Jubilee vouched for the PC.*

`elise3:` Did he now? What did he tell you?

## "Who Are You?" — Explains Herself

`elise4:` I'm Elise. That's Gond. We're members of a 'group' that's trying to do right for folks.

## "Who Are You?" — Hostile Brush-off
*Bad reaction instead of the line above.*

`elise7:` None of your business. Now get out.

## Low-Intelligence Dismissal

`elise5:` Just get yourself out of here. Saloon's back on Main Street.

## Not Interested in Car Repairs

`elise8:` We've gotten out of the car business. Closed permanently. Goodbye.

## "I Thought This Place Was Deserted"

`elise9:` It's not. Goodbye.

## Recognized by Reputation
*If the PC already knows of the Rangers and asks about them directly.*

`elise6:` Hates slavery, huh. Interesting. What would you do if you found this outfit?

## Her Opinion of Slavers

`elise10:` All right, so tell me. What's your opinion of slavers?

## Money Motive, Pushed Back On

`elise11:` Money all you care about?

## Approving of Aggression Toward Slavers
*Response to "I'd kick their butts."*

`elise17:` Well, it's your lucky day.

## Dismissing an Uncommitted Answer

`elise12:` Don't bullshit me. I can see what kind of person you are. Goodbye.

`elise13:` If you don't know, then I'm wasting my time. Goodbye.

## Turning Away Indifference
*Response to "If they leave me alone, I leave them alone."*

`elise18:` That's the kind of attitude that allows the atrocity of slavery to exist in the first place. I'm sorry, but there is no place for you in our organization.

## Turning Away a Pro-Slavery Answer
*Response to "Some of my best friends are slavers."*

`elise28:` That being the case, I have to ask you to get out of my sight. Now!

## Clarifying They're Not Religious

`elise14:` No, we are not a religious organization. Mind if I ask you a question?

## Explaining the New California Rangers

`elise26:` I see. Well, I represent a group called the New California Rangers. Someone with views such as yours could qualify for membership. You interested?

## Explaining the Rangers' Cause — First Time
*Plays the first time this comes up. On every visit after that, elise30 below plays instead.*

`elise23:` Simple. We believe slavery is wrong and we'll do what we must to fight it. In NCR, we got a lot of friends in high places. Thanks to them we've already banned slavery down south, but now we're hoping to spread the word north.

## Explaining the Rangers' Cause — Repeat Visit
*Shorter version she gives once she's already told you this once.*

`elise30:` We've got agents and sympathizers in some of the towns up north. We're spreading the word and hitting slavers wherever we can.

## Offering the Membership Test

`elise15:` Not so fast. You've got to pass a test to join the Rangers.

`elise16:` There's a slaver just outside town. Maybe you've seen his place. Free the slaves there and then come back and talk to us.

## Declining Someone Who Won't Commit

`elise27:` I see. Well thanks for stopping by but I can't see that we have anything more to say to each other. If you change your mind, come back and see me.

## Welcoming Back Someone Who Reconsidered

`elise19:` So, changed your mind? Ready to prove your worth?

`elise31:` Hello again. Have you changed your mind about joining us?

## Sent Off to Prove Themselves

`elise20:` Shouldn't you be doing something? Don't come back here until the job's done.

## Slaves Already Freed — Ready to Join?

`elise21:` I've heard the news already. You freed the slaves. Good work! So, you ready to become a Ranger?

`elise22:` I hear you're the one who freed all the slaves outside the city gates. That was a fine thing you did and I just want to shake your hand.

## The Ranger's Oath

`elise24:` Do you swear to fight slavery whenever the opportunity arises and to help your fellow Rangers whenever they're in need?

## Encouraging Someone Still Undecided

`elise25:` Well, we're always looking for good people to further our cause. If you change your mind, look me up. Are you sure you won't take the opportunity to join now?

## Becoming a Ranger

`elise32:` Congratulations, you're now a Ranger. It is your sworn duty to fight slavery wherever it may appear. Take care, my friend.

## Superseded Confirmation Line
*Short alternate take of the line above — currently unused, record it anyway.*

`elise56:` Congratulations, you're now a Ranger.

## Welcome, Fellow Ranger — Return Greeting
*Float. Plays when a Ranger checks in and there's nothing new for them to do.*

`elise52:` Well-met, fellow Ranger. Afraid there's not much for you to do around here at this time. Most our people are already out on patrol. I'll spread the word that you're one of us now. I wouldn't want you getting shot by one of us.

## Reminder to Hurry
*Float. A nag once the PC has agreed to attack the slaver camp but hasn't gone yet.*

`elise55:` Please, don't delay too long. This attack is critical in our fight against slavery.

## Confronting a Known Slaver
*Triggered if the PC has a slaver reputation.*

`elise29:` A slaver! Get out of here before I remove that tattoo of yours with a bullet!

## Tampering Warning
*Float, red/angry text.*

`elise53:` That doesn't belong to you. Now leave or I will get violent.

## Threat Over Gond's Death
*Float, red/angry text.*

`elise54:` I don't know what you did to Gond, but you're going to pay!

## Offering Intel on Metzger's Slaver Camp

`elise33:` Alright, let's hear it.

`elise34:` Are you serious? Our northern Rangers have been trying to track down Metzger's slaver camps forever. This is excellent news, now we just need to destroy that horrible place. Do you know how well guarded it is?

## Slaver Camp Already Cleared

`elise35:` You have? That's amazing! I'll have to spread the word out to the other Rangers. Now's the time for us to rise up and strike while they're busy licking their wounds. I can't thank you enough. We are truly in your debt.

`elise40:` Money? Well, I suppose it is the least we could do. Here, $1000 for your trouble. Thank you again.

## Rallying the PC to Attack

`elise36:` We must attack them at once. Wanna take down these scumbags for us?

`elise37:` Excellent! Please report back when you have wiped out the camp.

## Deciding Whether to Send Reinforcements
*After the PC is asked whether they want backup.*

`elise38:` No, I am sorry. I don't have the resources to pull some men together. This is something you will have to do on your own.

`elise39:` You're right. I'll get a small group together and send them with you. Are you ready to go now?

## Ready to Move Out

`elise41:` Are you ready to attack the slaver camp?

`elise42:` Your fellow Rangers will meet up with you along the way. Best of luck to you.

## Returning After Wiping Out the Camp

`elise43:` I've heard the news. Thank you so much for your help. This will surely deal quite a blow to the slavers. We are truly in your debt.

## First Recognized, Before Officially a Ranger
*She's heard about the PC's raid on the slaver camp but doesn't yet know them personally.*

`elise45:` What are you doing here? This is a private -- Hey, wait a minute, I think I've heard of you. Aren't you the one that took out one of Metzger's slave camps?

`elise46:` That was a fine thing you did and I just want to shake your hand.

`elise47:` Not at all. In fact, I'd like to shake your hand.

`elise48:` Because that was a fine thing you did and I just want to shake your hand.

`elise49:` We don't have a lot of funds to spare, but you *did* do us a great service so I suppose we could part with some. Here's $1000.

`elise50:` I'm Elise. That's Gond. We're members of an anti-slavery group called the New California Rangers. We could use someone like you. If you're interested in joining us, I've got a task for you.

## One More Thing — Recruiting Pitch

`elise44:` Actually, one more thing. You look like someone to be trusted. Someone who doesn't take a liking to Slavers.

## Checking In With a Known Ranger
*If she already knows the camp's location but it hasn't been wiped out yet.*

`elise51:` Help you with something, Ranger?

---

*Tag numbers follow ascending message-ID order, not the order above. End of script — 56 lines total.*
