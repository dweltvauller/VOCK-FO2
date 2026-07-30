# Lydia — VA Script
**Character:** Lydia, Bartender of the Vault City Downtown bar

**Total recordable lines:** 47 (`lydia1`–`lydia47`)

---

> **Direction:** Vault City's bartender — brisk, business-like, no-nonsense with outsiders, noticeably more deferential toward Citizens and the Captain of the Guard. She's also running a bootleg real-alcohol side-hustle behind Vault City's synthetics-only law, so those lines should carry a knowing, hushed, "keep this between us" edge. Not evil, just self-interested and pragmatic. Adult female, functional working-bartender voice.

---

## Floats — Sleeping
*Plays overnight when found asleep.*

`lydia47:` Zzzzzzzz.

## Floats — Hero's Welcome
*One plays at random after the Enclave has been destroyed.*

`lydia34:` Welcome! Care for a drink, Chosen One?

`lydia35:` Welcome, Chosen One! Please, take a seat in the bar.

`lydia36:` Please! Take a seat, rest for a while!

`lydia37:` It's the Chosen One! Everybody give it up for the HERO of Fallout 2!

## Floats — Greeting a Citizen or the Captain
*One plays at random, depending on the PC's rank.*

`lydia38:` Good day, Captain.

`lydia39:` Vault City prevails, Captain.

`lydia40:` Good day, Citizen.

`lydia41:` Vault City prevails, Citizen.

## Floats — Hostile Reaction to a Companion
*Triggered if the PC brings a mutant or ghoul companion into the bar.*

`lydia42:` A mutant! Guards! Guards!

`lydia43:` A ghoul! Guards! Guards!

## Floats — Closed for the Night
*One plays at random after hours.*

`lydia44:` We're closed. Come back in the morning.

`lydia45:` Sorry, last call was a while ago. Come back in the morning.

`lydia46:` We're closed. Once I finish making this list of our stock, I'll be closing up.

---

## First Meeting — After the Enclave's Defeat

`lydia1:` Hey there, Chosen One! We were just talking about your adventure... can I get you anything to drink?

## Low-Intelligence PC — Not a Citizen
*Escalating annoyance at a low-INT PC's babbling; ends with her calling the guards and having them thrown out.*

`lydia2:` Uh... so I smell. Um, thanks again for saving the world and all.

`lydia3:` Look, maybe you saved the world and all, but a poet, you're not. Now cut it out.

`lydia4:` Look, take these and get out of here, okay? They ought to keep your mouth busy for a while.

## Standard Greeting
*Varies by the PC's citizenship/rank.*

`lydia5:` Uh... what can I do for you, Captain?

`lydia6:` What can I do for you, Citizen?

`lydia7:` Yes? Can I help you?

## Low-Intelligence PC — Not a Citizen (Reported to the Guards)
*Same low-INT babbling as above, but from a first "standard greeting" pass — leads to expulsion.*

`lydia8:` That is perhaps the most fascinating thing I've ever heard. Hold on a second... I want the guards to hear it, too.

## Low-Intelligence PC — Citizen or Captain
*Same babbling, but she lets it go since the PC already has standing.*

`lydia33:` I... see. Well, uh, take care now. Okay?

## The Bar Menu

`lydia9:` We have synthetic beers and liquor... vodka-H, tequila derivatives W and W2. Oh, and water. And brahmin milk. Beer or liquor is ten bucks, water or milk's three bucks.

`lydia10:` Like...? *(repeat visit — recapping the menu)*

## Ordering the Brahmin Milk

`lydia11:` The brahmin milk's not on tap... well, not exactly. I'd have to go out and snag some really quick.

## Serving the Drink

`lydia12:` There you go. Anything else?

## Information Hub

`lydia13:` Oh? Like what?

## Who's in Charge of Vault City?
*Varies by citizenship status.*

`lydia14:` Uh, First Citizen Lynette... you are a Citizen, aren't you?

`lydia15:` First Citizen Lynette. She's in the council building up north if you need to talk to her.

## Where's the Vault?
*Varies by citizenship status.*

`lydia16:` Uh, it's the big hole in the side of the mountain to the east of here... say, you are a Citizen, aren't you?

`lydia17:` It's that big hole in the mountain to the east of here. You can't miss it. You also can't get inside unless you're a Citizen, though.

## Calling Out Forged Papers
*Triggered if the PC is passing off Skeev's forged citizenship papers as real.*

`lydia18:` Sure you are. I'd just be careful who you say that to, "Citizen." Somebody's gonna recognize whatever stolen papers you bought from that bloodsucker Skeev. So keep your head down, all right?

## Asking About Slavery

`lydia19:` Look, first thing I have to say is that you better not call it "slavery" around here or you're going to get yourself in a whole mess of trouble. They're called "servants," not slaves. Just a word of advice.

## Contact With the Outside World

`lydia20:` Not much. Most contact we have with Outsiders is merchants travelling the Big Circle caravan trail from Broken Hills, New Reno, and Redding. Only other place outside the caravan trail that I know of is Gecko.

## City Info — Broken Hills

`lydia21:` It's a mining community like Redding, except it's located to the far South. We get many of our uranium shipments from there.

## City Info — New Reno

`lydia22:` It's a ways to the southwest. I hear conflicting reports about Reno. Some merchants, especially the slavers, really love it there. Other merchants... don't. City with a lot of glitter... and a lot of trouble, I hear.

## City Info — Redding

`lydia23:` It's a mining town far to the west. We haven't seen too many caravans from them recently, and it's got some of the high-ups a little worried. Senior Councilman McClure especially.

## City Info — Gecko

`lydia24:` A town of ghouls less than a day's travel to the northeast, as I understand it. Rumor is they prey on any travelers that enter their territory. Best stay away.

## Bootleg Alcohol — Opening the Deal (Non-Captain/Citizen)

`lydia25:` Why? You looking for something with some more kick than these synthetic drinks?

`lydia26:` That's for sure. I used to have a... well, I used to know this merchant who had a bottle of Maddog 30/30. Bitter stuff... couldn't feel my tongue afterwards, but it was refreshingly different.

`lydia27:` It got drunk. Or so I heard. There were a few other "friends" here in Vault City who helped this merchant friend drink the stash. They were willing to pay a good price to have the real stuff for a change.

`lydia28:` Is that so? Well, if you happened to be looking to relieve yourself of some real alcohol, then I could make it worth your while. If you could keep quiet about our deal. And get the contraband past the gate.

`lydia29:` Say, a case of ten bottles of premium alcohol, and ten bottles of beer. And none of that radioactive stuff I hear comes out of Gecko. Just good old "booze," all right?

## Bootleg Alcohol — Refusing the Captain
*Lydia won't risk the deal with the Captain of the Guard asking.*

`lydia31:` No, those wasteland concoctions they call alcohol are illegal here in Vault City. I don't even want to know how they brew them. Now did you want something to drink, Captain...?

`lydia32:` I wouldn't know anything about that. I only serve synthetic alcohol here. If any real alcohol were to enter Vault City, I wouldn't know anything about it.

## Delivering the Bootleg Shipment

`lydia30:` Excellent! Here's something for you... that amount's double the price the cases are worth. And this transaction never happened, all right?

---

*End of script*
