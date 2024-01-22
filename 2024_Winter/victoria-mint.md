---
title: Exploring the Sea of Darkness
category: Op-Ed
date: 2024-01-11T16:41:43.357Z
desc: While playing video games, you must have had those moments where you
  wished that you could make just a few more tweaks to make your experience even
  better. Well, this is exactly what open-source games offer and much more. Join
  us as we explore the depths (or expanse) of one such simulation game and delve
  into the lore, the gameplay, and the code within.
thumbnail: images/victoria-console-thumbnail.jpg
authors: Victoria Mint
starred: false
abio: none
---
### Intro:

It all began when I felt a cold coming on and knew that the chances of doing anything productive on the weekend were close to nil. Wanting a distraction from the misery that awaited, I considered trying out some game development; I had written Asteroids in Python earlier and wanted to see if I could implement missiles with an inertial navigation system. 

Halfway through solving the relevant kinematic equations, a thought struck me - I'm not the first person to have made such a game. Wouldn't my time be better spent playing a complete game and making contributions to it instead? And so I found [Naev](https://naev.org/), a clone of [Escape Velocity](https://en.wikipedia.org/wiki/Escape_Velocity_(video_game)). Since Naev\[1] was open-source, I knew that I would stand to learn a thing or two by studying the codebase. 

![](images/naev.jpg)

The developers had made the installation procedure quite easy for Linux, with a self-contained AppImage that let me jump straight into the game without compiling the whole thing from the source. After creating a profile, I began my journey into the Sea of Darkness.

- - -

### Gameplay:

I started out as all players do, with the generic starter ship on a planet deep inside Imperial space. The initial rules were quite clear:
If you attacked a merchant ship, they would send out a cry for help, which would be picked up by an Imperial ship which would eliminate you (if the merchant ship had not done so already). 

The Empire acted as a peace-keeping force in the region, deploying ships that seemed invincible to a new player. Naturally, I tested the supposed invincibility of the Empire - I tried shooting at large Imperial ships and running away before they could respond, only for them to send interceptors after me. 

It was clear to me that my starter ship was not meant to engage in combat, let alone challenge interplanetary militaries. Left with nothing to do, I land on a planet and start flying routine cargo-delivery missions and sightseeing missions to earn enough money to buy a better ship. 

As these missions took me further and further away from the safety of the Imperial Core, I started getting harassed by pirates. Engaging in combat with them is a fool's errand, since they tend to fly nimble ships, armed to the teeth. The only viable strategy I had was to run to the nearest Imperial ship and hope that the Empire would protect a neutral trader like me. 

Those pirates daring enough to follow me into the line of sight of an Imperial fighter were reduced to space debris. When no Imperial patrols were nearby, I was forced to bribe the pirates into leaving me alone. These bribes were often paltry sums of money compared to the money I was making, but a non-zero amount nonetheless. Every time a pirate flying a Hyena exclaimed "Lucky day!" after extorting me, my urge to hunt them down and destroy them grew stronger.

As the cargo missions grew tiresome, I tried out some sight-seeing missions under the assumption that a wealthy tourist might have a lot of money to offer me. However, the tourists always seemed discontent with being ferried around in a common trading ship, often not paying the full fare, stating that they prefer flying in a luxury sporting vessel. 

The express cargo missions tended to pay more, but failing to make the delivery on time resulted in no payment at all. As someone who did not explore much of Imperial space, finding a route to the planet I needed to make the delivery to was often too difficult to complete quickly, resulting in a lot of missed deliveries. The person who asked me to deliver the cargo did not give me a map to my destination, instead letting me find my way there myself.

As time went by, I managed to save enough to buy a new ship. My first instinct was to buy an interceptor class ship (the cheapest combat type) and have fun hunting down pirates. However, I had four important observations:

1. An interceptor, being larger than a pirate Hyena, would often be outrun
2. Pirates can fly interceptors too, and they are not easy to scare off
3. Hunting random pirates, while fun, could not be turned into an income stream
4. Buying an interceptor required me to get a license that allowed me to buy combat vessels. Such licenses actually cost money since a functional society cannot let military hardware be purchased willy-nilly without at least some background check.

On the other hand, my exploration of the stars had left me with a decent working knowledge of most systems in Imperial space, which made express shipping a viable activity. The problem of piracy could be solved by simply outrunning them, so I bought the fastest ship available - the Schroedinger. Designed to be a reconnaissance ship, it could move faster than most pirate ships (except those pesky souped-up hyenas the pirates flew). 

With a new ship acquired, I was ready to take on some high-risk-high-reward cargo missions, only to realize that the Schroedinger's speed came at the cost of cargo space, which significantly limited my ability to parallelize cargo runs - I had to complete one run before starting the next.

During a routine cargo run, I ran across a shady individual who told me that they needed a box of "cake" delivered to a particular location. The box weighed almost nothing, so there were no problems with cargo space. The catch was that the "cake" had very delicate "icing" which was not to be subjected to any scanning by Imperial ships. 

It was clear to me that the cake was a lie. Whatever was in that box was something that the empire did not like being moved around its territory. While getting on the empire's bad side was not something I wished to risk, the amount of money offered made the mission hard to turn down.

All ships came with a useful ability whereby one could, by sacrificing speed, make the ship hard to detect. I had no intention of fighting my way through an Imperial blockade, so sneaking around them with my cake seemed to be the best option. The time I spent dodging my way through the imaginary bubbles marking the radii of detection of Imperial scanners was more fun than every mundane cargo run or one-sided combat encounter I had till then. 

I found my calling in this virtual life - smuggling. Not only was it exciting and well-paying, but it also let me thumb my nose at the Emperor's edicts about the illegality of spicy burritos and pineapple pizza (which constituted most of the contraband I smuggled).

The spicy burritos must flow; their flow across the galaxy was matched by the flow of money into my coffers. By the time the novelty of smuggling wore off, I had the ability to buy another ship. Deciding to switch careers, I bought a mining ship - a Rhino - and equipped it with hyena drones. My plan was to traverse the galaxy looking for mineral-rich asteroids, mine them, and sell the minerals in commodity markets across space. 

Seeing my drones destroying any pirates who tried to mess with me was an added benefit. Any pirates that got past my drones would find themselves shredded to pieces by turrets (which swiveled around to aim, meaning I didn't even have to turn my ship around). This was to be the sweet life.

While seeing pirate hyenas being destroyed brought me great satisfaction, I began to despair of mining. Most asteroids had nothing other than water. As resources were mined, other miners would often swoop in and try to make off with my hard-won minerals. The mining equipment I used was sufficiently destructive that any truly rare minerals would be destroyed by the act of mining. The income stream slowed to a trickle.

One of the features of my Rhino was that it came with a large cargo hold to carry minerals. I decided to put the cargo hold to better use by trading commodities on margin. While mining, I noticed that certain minerals were often cheaper in some worlds than others. What if instead of mining minerals, I simply make money moving minerals from one world to another? Moving around would be no problem; my Hyena drones could eliminate even a pirate interceptor. Thus began my days as a cog in the grand galactic economy, acting as an agent of the invisible hand of the free market.

The problem with trading on margins is that the margins are quite thin, meaning that it takes a lot of trading to double the initial investment. Furthermore, markets tended to stabilize over time, so prices tended to reach equilibrium the more I traded. 

The Rhino, impressive as it was, was hardly the biggest cargo transport out here. That honor belonged to the Zebra, which was a massive behemoth designed solely to haul freight or act as a troop transport. The zebra was well outside my budget, so I once more began to look for a different career.

As I wandered around the galaxy, I eventually reached an independent system which was governed by House Goddard. The Great Houses, while nominally under the control of the Emperor, acted as quasi-independent entities which exercised a high degree of autonomy. House Goddard (as I was told by a patron of the local spacebar) was founded by Eduard Manuel Goddard, who received the honor of having a Great House named after him after he designed a massive battleship, the Goddard. 

This was the biggest ship I'd seen so far, something that could cruise through pirate-infested space majestically while drones hunted down any pirate ship it picked up on its scanners. However, a ship as powerful as a Goddard was not available to just anyone; one needed a special license to buy battleships. Such licenses were not available in the general market but given out by governments after sufficient favour had been curried.

Further exploration beyond House Goddard (which controlled just one system) took me to the territory of House Dvaered, whose internal politics and culture fascinated me. The Dvaered was founded during the Dvaered revolts, during which the salt-of-the-earth types in the Empire grew sick of Imperial administrative practices. Since most captains of Goddard battleships sided with the rebels, the newly emergent House Dvared's signature capital ship became the Goddard. The Dvaered remain the biggest customers of the battleships manufactured at the shipyards of House Goddard, which probably explains the real reason why House Goddard was allowed to exist in the first place.

The Dvaered are decentralized to the point of absurdity, where each planet is controlled by its own warlord ("warlord" not being a pejorative, but an official term used by the Dvaered High Command) who runs the place. Warlords are free to do almost anything they like in their own territory (and anything they can get away with elsewhere).

The decentralization is not limited to administration but extends to the military as well. What passes for a military in Dvaered is made up entirely of warlords, who do not hesitate to settle their personal grievances by engaging in "Goddard duels'' which consist of two Goddard battleships facing each other and unleashing a barrage of railgun ordnance while an umpire (another Dvaered officer) oversees the whole affair. 

Even routine operations like patrols of systems are assigned to miscellaneous warlords, who may or may not actually perform their duties. This gap in trust between the DHC and the warlords could be exploited for money, by offering to carry out censuses of Dvaered ships. Since the government couldn't trust their own military to be where they were ordered to go, they hired independent contractors to verify and report the positions of their own troops.

Often, upon entering a Dvaered system, a mercenary hailed me and told me that a showdown was happening between two warlords in this system and that I was free to attack either side. If the side I threw my lot in with ended up winning, I'd be paid; else I'd be hunted down. I was neither in any position to play kingmaker nor particularly interested in finding myself in the ranks of suicidally insane soon-to-be space-ronin, so I jumped out as soon as possible. 

Sometimes, when I felt particularly adventurous or bored, I'd drift at the midpoint between the two approaching fleets and watch the battle play out in front of me. When defeat was all but assured for one side, I'd jump in and get a couple of shots in to claim a bounty. Dvaered culture being what it was, the remnants of the defeated fleet often made heroic\[2] last stands instead of attempting to run or swear fealty to a new liege lord.

Sometimes, if one hung around the systems adjacent to the DHC long enough, one would hear public broadcasts like "Other warlords not letting you enjoy bloodshed? Join Lord Easytrigger's battalion today!" or "Let it be known that Lord Battleaddict is a Dunderhead. - Lady Killington". 

Delivering playground insults is another favourite pastime of the Dvaered; I once tried to make money by flying to a planet and dropping propaganda leaflets containing base insults about the honor of the local warlord. I barely had time to leave before multiple Vendetta fighters sent a barrage of missiles after me. Fortunately, my Schroedinger, being one of the fastest ships in the galaxy, allowed me to get away from the enraged Dvaered pilots desperate to restore the honor of their warlord by incinerating me.

A brief aside about Dvaered strategy - the Dvaered fervently believe in the maxim "the best defense is a good offense" and arm their ships entirely with kinetic weapons, which are simple to operate at large scales. Battles with Dvaered ships tend to be extremely short-lived, they either destroy their target with an initial volley of a large number of unguided missiles or exhaust their ordnance and turn into sitting ducks to be picked off. Thus the start of any Dvaered squabble is marked by a furious barrage, followed by ships milling around waiting for their weapons to reload while the Goddard battleships keep rushing headlong at each other with railguns blazing. The Dvaered's general ignorance of terms like "evasive maneuvers" and "strategic depth" is more than compensated for by their intuitive understanding of the power of an all-out frontal assault. Missile go boom and railgun go pew; simple as.

Upon venturing close to the nebula at the centre of the galaxy, one encounters the Frontier Liberation Front (or FLF). The Frontier is a region of space that remained independent from the Empire before the fracturing, and their government seems to offer tacit support to the FLF to wage asymmetric war against the Dvaered (who have designs on the frontier and would have conquered it a long time back had the squabbling warlords making up their military actually had the discipline to train their guns on a common target rather than each other). 

Any hope of politely minding one's business while the FLF and the Dvaered duke it out was dashed, as I was forced to pick a side pretty soon. Naturally, I chose the Dvaered since it was clear to me which way the galactic winds were blowing. Thankfully, my refusal to fall in with the FLF did not jeopardize my status with the Frontier governments that backed them, so I was allowed free passage through their space.

Beyond the Frontier lies House Sirius, which was established by an individual named Sirichana, who led people to safety during the Faction Wars before the establishment of the Empire. By the time the Empire had stabilized itself, the followers of Sirichana controlled enough planets that the Emperor did not want to start a war to bring them back into the fold. Thus, a compromise was made - Sirichana would be recognized as the leader of House Sirius.

With a newly acquired Pacifier (a Destroyer class ship designed for military operations), I began work as a private military contractor/bounty hunter, hunting down the enemies of the Sirii and patrolling their trade lanes. The Sirii often wanted their targets captured alive, which presented a problem for my fleet of Hyenas, which usually destroyed any ship I targeted.

My modus operandi was to jump into a system and sic my hyenas on the targets from afar. In the rare instances where they came within shooting range, I let them have it with my twin turreted kinetic weapons (a little trick I picked up from my time in Dvaered space).

As I explored Sirii space, I often came across pilgrims who wished to be ferried to Mutris, which was said to have housed Sirichana. The pilgrims were often disappointed by the fact that I was not flying a ship fabricated by a Sirian shipyard and used this disappointment as a pretext to dock pay. 

Another point of contention was that my reputation with the Sirii was not high enough for me to be allowed to set foot on Mutris, so the pilgrims would often settle for transport to a neighbouring system if my price was negotiable. Suffice it to say, I was not involved in many pilgrimages (which was fine by me, since the Pacifier was not designed to act as a ferry)

Soon enough, my reputation with the Sirii reached a level where I was trusted by them to buy any ship of Sirii design. Naturally, my first Sirii ship was the Divinity, which was a carrier-class ship designed to serve as a drone platform. To go with it, I also installed several Fidelity drone docks, which now allowed me to traverse unopposed through all of Sirii space. The local pirates were no match for me, and hunting them had lost charm since my drones destroyed them offscreen.

Travelling back the way I came, I stumbled upon another Great House - the Za'lek. Originally established as an Imperial research division, the concentration of scientists and academic types resulted in the formation of a new technocratic culture on the planets they colonized. Eventually, the Za'lek were granted the title of a Great House after it became clear to the Emperor that the brain drain happening from Imperial planets to Za'lek space was all but irreversible, and that any military solutions were off the table since the Za'lek had developed vastly superior technology by that point.

The Za'lek ethos is antithetical to order; this is reflected in everything from their academia-inspired government structure to their apathy towards pirates operating freely on their border with the Dvaered, from their drones which sometimes go haywire and attack nearby vessels to the very designs of their ships, which tend to be comically asymmetric. The Za'lek have idolized the pursuit of science and treat it in much the same way that the Sirii treat their religion or the Dvaered treat their railguns.

The Za'lek drones outclassed my Fidelity hangars, so I spent some time in Za'lek space making money and building a reputation to purchase their heavy drones and bombers. Upon seeing that I wasn't going to be able to convince them to let me buy one of their capital ships, I decided to travel to the last of the Great Houses - the Soromid.

The Soromid gained their independence during a great plague when the Empire abandoned their homeworld as a lost cause and bombed all spaceports from orbit to prevent the various plagues on it from spreading. Though left for dead, the Soromid managed not only to survive but thrive, via genetic engineering. This makes the average Soromid tribesperson look slightly off (eg. having the wrong number of eyes or limbs) since bioaugmentation is as firmly embedded in Soromid culture as LaTeX is in Za'lek culture.

![](images/naev-gameplay-1.png)

The Soromid bioships, produced by embedding ship components in an organic matrix, are some of the best in the galaxy. Each ship comes equipped with stinger organs for weapons, an organic computation unit, and a bioengineered hull.

I like to think that I arrived in Soromid space in style, flying a capital ship of a Great House at another end of known space. Maybe the Soromid who saw me thought I was a Sirii envoy there on important business. Nothing could be further from the truth; all I wanted to do was to move up Soromid ranks by killing local pirates and eventually be given permission to buy their capital ship, the Arx. Having acquired Za'lek bombers (which disabled ships before destroying them), I was able to take on bounty missions where the authorities wanted the target alive, which made me more than enough money to buy an Arx. 

Armed with three drone bays (each of them equipped with Soromid bioship generators), I felt close to invincible. I could decide the direction of Goddard invasion battles. I could capture any pirate alive. I could drop propaganda on any Dvaered planet and smoke every single Vendetta that came after me. I could travel deep into the heart of pirate territory without bothering to cloak my ship.

In one of these forays into pirate systems, I managed to bribe the port authority of a pirate-controlled planet to let me land. The pirates gladly sold me some of their best ships and weapons despite my poor reputation with them. I suppose my money (which had long-ago ceased to be an object) talked. 

It was here that I acquired the pirate Kestrel, the only ship more notorious than the Soromid Arx for being essentially invulnerable (in fact, this ship is so loved by the community that it is the icon used for the game). I travelled to the black hole at the edge of Za'lek space and realized that there were no worlds left for me to explore.

My journey was over. I'd done it all. I explored distant worlds, fought deadly foes, mined rare minerals, flew powerful ships and met interesting people. Wanting a poetic end to my celestial Odessey, I travelled back to the start point, landed and disembarked.

As you step out of your ship, the sunlight suddenly flickers. The local star in the sky turns blue, then a deep purple, and then goes dark. The whole planet plunges into darkness.

```
Then a voice speaks, louder than an earthquake. It seems to echo inside your bones and from the very centre of the galaxy. "Oh crap..." it says.
                             
Another voice laughs musically, as if the world itself were singing. "bobbens, did you just destroy the universe, again?"
                            
"Mmmm, hold on," the first voice rumbles. "...SIGSEGV... libc start main+0xe5... ah ha!  There's the problem."  You feel something fundamental in the fabric of reality change. The sensation is like sneezing and hiccuping at the same time. "There, that should fix it."
                               
A window opens in the darkness, infinitely far away and infinitely large. A face peeps down at you from the height of eternity.                
                             
"Everything all right in there?"
                            
```

Huh. This was new. I responded in the affirmative; everything was all right.

"Good. Sorry for the inconvenience. Please don't worry, I'll have reality reloaded again in just a sec."

```
The creator turns to go, then pauses.
                                 
"By the way, we're working hard on improving life, the universe, and all that, but we're a bit short-handed. If you like this existence but think the details could be improved, the universe creation team could use your help. We'd be especially happy to see you if you have any special skill in drawing planets, designing ships, scripting the underlying laws of nature, or composing the music of the spheres. For information on how to contribute, just point your web-of-reality browser to naev.org."
                 
The watchmaker lifts his eyes up beyond your frame of reference and smiles.
"OK then. Pushed. And we're back in 3... 2... 1..."                               
```

### Contributions

Seeing that message reminded me why I was here to begin with. I may have finished exploring the game, but the source code still awaits. I was quite excited to look behind the curtain and understand what made Naev tick.

Exploring the codebase required me to start by downloading it. I have been playing the game using an AppImage so far, which is a distro-agnostic portable format to distribute software. An AppImage could be run without any of the tedious sudo apt-get install or ./configure && make && make install command-line stuff. This is perfectly fine for a casual user, but doing anything substantial requires one to build from the source. So to the [naev github](https://github.com/naev/naev) I went.

After cloning the repo, I began by installing the required dependencies in the background while looking at the code. The codebase consisted mostly of C (for the game engine) and Lua (for missions); I was familiar with the former and had no idea about the latter. A cursory glance into the src folder showed a bunch of files with familiar names, like ship.c and pilot.c. The functions contained in them were well-documented and legible.

![](images/naev-code.jpg)

After all the dependencies were installed, the compilation failed. To be honest, I never expected it to compile correctly the first time; I'd have been very surprised if it did. Such is simply the nature of software - something always goes wrong. When reading the documentation failed to shed any new light on the error I was facing, I decided that I ought to try asking in some forum.

My first instinct was to check the [contact page](https://naev.org/contact/) of the Naev website, which took me to their discord server. I described the problem I faced, apologized in advance if the root cause of the issue was my own stupidity, and waited.

My worries about eliciting comments like "lurk moar", "read the wiki" or "What do you take us for, free tech support?" were proven unfounded when one of the developers pointed out the issue - one of the dependencies I had did not meet the minimum requirements.

So far, I have been using the package manager apt to handle all my installations. The library in question, SDL\[3], did not have its latest release available to apt, so I had to go to their homepage, download a compressed version of the latest version of the library and do the whole `./configure && make && make install` routine that I'd been trying to avoid.

After sorting out the issue with the dependencies, the compilation proceeded smoothly. I had a fully operational instance of Naev, this time built from source. The build process itself was managed by [meson](https://mesonbuild.com/)\[4], so I had to type only three commands to finish the whole thing. Nonetheless, I decided to put those three commands into a shell file, to reduce my work even further. Such is the nature of a software engineer - one would spend 10 minutes to automate a task taking 1 minute to do manually.

While playing the game, I had many ideas for improving the gameplay, and now I could actually try implementing a few features. This is one of the reasons FOSS games are superior to their non-FOSS counterparts - extending the game (or "modding") is easy by design. Since I was working with an unfamiliar codebase, I decided to start off with something simple - whenever a Sirii pilgrim changed their destination location from Mutris, the corresponding mission marker on the map remained on Mutris (despite the player's inability to actually land there).

Since the problem was one related to a mission, I knew that the relevant code would be in Lua. One problem - I knew absolutely nothing of Lua\[5].

In a post-GPT world, learning Lua syntax was unnecessary. The language was such that anyone with a passing familiarity with procedural programming could understand what was being written, and anyone who wanted to write Lua code could just describe what was needed and let chatGPT worry about getting the syntax exactly right.

My first job was to pinpoint where exactly the code I was looking for was written. In a smaller codebase, I might have read every single filename, trying to find something relevant like "pilgrimage" or "Sirius". However, there were too many files for me to even count manually, so this was out of the question.

What I did know was that the dialog boxes that popped up when ferrying Sirii often had the words "disappointed" or "unworthy", and locating the string with the dialog would lead me to the file I needed. VSCodium (my go-to editor) was capable of performing regex searches across every file in the codebase, so I composed a suitable regular expression:

`set.*foot.*(Mutris|holy.*ground)`

This took me straight to a file named `srs_ferry.lua`, and, after reading the whole thing, noticed the problem - the mission marker was not moved when the destination was reassigned. All I needed to do was to save the mission marker and then use the movement API to change the location of the marker. Studying other missions with dynamic mission markers provided me with a useful blueprint for how to proceed.

After fixing the issue, I rebuilt from the source and tested out my fix. By now, I had learnt that pressing F2 opened up the Lua console in Naev, so I could just use the API\[6] to teleport my ship into Sirii space and summon pilgrims out of the ether. After verifying that the mission marker moved as expected, I decided to let the developers know on Discord.

The developers suggested that I open a pull request on GitHub, so I did just that. GitHub helpfully showed everyone the nature of my changes - I had modified one line and added another. Given the small magnitude of the changes made, there wasn't much scrutiny before the PR was accepted. I had gone from playing Naev to helping develop it.

CS Engineers are a curious bunch - given something, their first instinct is to take it apart, see how it works and start modifying it to suit their own ends. Open-source software is the natural result of the type of community that such instincts result in.

Even more curious are the gamers - those who recognize that mere computer programs can transcend the realm of just the functional and enter that of art. Whether video games are art is not a question that can be answered here; many debates over this issue have occurred between individuals far more well-versed on both subjects than myself.

In some ways, the codebase of Naev reflected the in-game universe itself - a vast entity created by the collaboration of many people united by a common purpose, waiting to be explored and expanded. In the duality between these two seas of darkness, I saw something beautiful.

- - -

**Footnotes:**

* \[1] Naev, it is claimed by some, stands for "not another EV"
* \[2] at least, heroic by Dvaered standards, which differ considerably from those of the rest of the galaxy
* \[4] an open-source tool designed to automate the process of compilation
* \[3] A library to allow low-level access to hardware, often used in game development
* \[5] From glancing at the Wikipedia article for Lua, I understood that it owed its creation to the Brazilian government's trade barriers which, by making foreign software unaffordable, induced the creation of a homegrown programming language ("Lua" meaning moon in Portuguese).
* \[6] The Lua API lets one do many things, including but not limited to: paying oneself any amount of money one wishes, buying any weapon or ship, changing one's standing with any faction or going anywhere instantaneously