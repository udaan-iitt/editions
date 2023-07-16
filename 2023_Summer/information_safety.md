---
title: Algebra Of Safety
category: Op-Ed
date: 2023-07-14T12:30:00.393Z
desc: "Safety holds primal value within humans. Fundamentally, the absence of danger, early humans knew safety very well. The caves were safer. The fires kept us safe from the predators in the wild. But, today, as the world shifts to an information-rich regime, does the concept of safety stay the same? What constitutes as \"safe\"? Could we provide an all-encompassing definition? And the big question, could a rigorous study of information safety make the world any.....safer?"
thumbnail: ./Images/infosafety.jpg
authors: Cosmic Cutie
starred: false
abio: NONE
alt: "safety"
---

```
Sticks and stones
can break my bones
but words can never hurt me
```

So goes the [popular aphorism](https://en.wikipedia.org/wiki/Sticks_and_Stones) used to teach children to shrug off insults. However, when the power held by words is considered, the absurdity behind this statement is clear. Words decide who wields the sticks and where the stones are thrown.

That being said, there is more to this aphorism than a superficial analysis reveals. Words may indeed be capable of hurting people, but there is a clear distinction between verbal and physical violence. The fact that violence can be divided into two classes, that a line is drawn between an insult and a punch, is something useful. Teaching children that no verbal assault justifies a physical retaliation is a pragmatic way to prevent escalation.

Consider extending this line of thinking - if violence can be partitioned into two classes (verbal and physical), can violent words also be partitioned into subclasses? Would these subclasses be useful in generating social norms for different types of violent words?

When talking about violent words, I do not wish to focus on insults, since the effect that an insult has depends entirely on the receiver. This requires analysis of the mental state of the recipient and the relation between the words and the recipient, which gets quite complicated.

Let us restrict our domain of analysis to "statements". A "statement" is defined as an entity having a clear truth value. This restriction serves two purposes:

1. It allows us to evaluate the nature of the statement on its own merits instead of having to look too deeply at the broader contexts in which the statement is made.
2. It removes imperative sentences (like explicit calls for violence) from the domain of analysis, making our work easier.

Just as a statement is either `true` or `false`, consider constructing another dichotomy - a statement is either `safe` or `unsafe`. A statement is defined to be dangerous or unsafe if stating it results in risk to the legitimate interests of an entity worthy of moral consideration. However, this definition raises more questions than it answers - "When is an interest *legitimate*?" "Who decides which entity is worthy of moral consideration?" "What constitutes risk?" "why should I care about any of this?" etc.

Thus, let us skip making a rigorous definition of "danger" and go with an intuitive "I know it when I see it"-type definition.

Consider a statement that is trivially safe - for instance, the statement "2+2=4" - something that most reasonable people would not consider dangerous. Consider the characteristics of this particular example:

1. It is true.
2. It is public knowledge.
3. It does not refer to any real-world entity directly.

Let's use these properties to divide statements into classes and see if we can prove any results about safety.
********************
                          
### The true-false dichotomy

Is there any correlation between a statement's truth value and its safety? It is easy to come up with examples of false statements which are dangerous - for instance, slander which paints someone in a negative light could put them at risk. A historical example of this would be the [blood-libel](https://en.wikipedia.org/wiki/Blood_libel) myth, which arguably contributed to antisemitism and the atrocities which followed.

Consider the statement "There is a fire in this theatre", an often-used example to argue against the absolute nature of the doctrine of free speech. The argument goes something like this: "since shouting fire in a crowded theatre could result in a stampede, doing so ought to be restricted". Despite differing on the validity of this argument, most parties see why this statement is unsafe.

However, consider the same statement being uttered in a theatre which is actually on fire. The danger posed by this statement is not purely due to the potential for a stampede, since a stampede could occur whether or not a fire is actually present. No reasonable person would consider this statement unsafe if it results in lives being saved. Thus we have an example of a statement whose safety is correlated with its truth value - it's safe when true and dangerous when false.

However, this correlation is far from absolute. For one, falsehood does not imply danger; a white lie is an example of a statement which is both false and safe. That said, what about the inverse? Does truth imply safety? Is there such a thing as a true statement that is dangerous?

One obvious example would be the act of doxing, ie. leaking the private information of a semi-public figure online. The information is not dangerous _despite_ being true, but precisely _because_ it is true. If it were false, it would actually be safe.

Thus we have an example of a true factual statement that is nonetheless dangerous. The statement is not an explicit call to violence against the target - it merely exposes the target to potential violence from other entities. Even if no actual physical violence results from doxing, the constant threat of imminent violence hangs as a Damocles' sword above the target, forcing it to change its behaviour in ways potentially harmful to its own interests.

A more extreme example of this type of statement would be the propaganda used in [stochastic terrorism](https://en.wikipedia.org/wiki/Lone_wolf_attack#Stochastic_terrorism), a technique where one bombards the public square with negative information and opinions about a target without making any explicit call for violence against it. Each individual bit of information may be true, each individual opinion may be held in good faith, but the net result is an increase in the probability of physical violence against the target. Instead of explicitly calling for violence, one hopes that some lone wolf will do the dirty work and take the fall for the attack.

A famous instance of doxing is the tale of [Aldrich Ames](https://en.wikipedia.org/wiki/Aldrich_Ames), who was a CIA agent who leaked sensitive information about KGB agents who had defected to the USA. In other words, he was a turncoat who exposed other turncoats. Any statement Ames made about the whereabouts or allegiances of the KGB agents were dangerous in that it resulted in their capture, interrogation and possible execution. It was also indirectly dangerous to the USA as a whole since it harmed its ability to gather intelligence.

The common thread between all these examples is the fact that the statements all contained private information. Doxing results in an increase of the pool of people who had access to the information. In other words, the danger arises from the act of making the statement public in conjunction with the body of the statement.

Since the act of making a statement is inextricably linked with the statement itself, it is difficult to analyse such statements. What if we were to exclude statements containing private information from our analysis?
*************************
                
### The private/public dichotomy

Consider only those statements that are already public knowledge. In other words, information which anyone can learn about.

Some statements have always been in the public domain. Mathematical theorems are a particularly good example of this. Several cultures have independently discovered [Pythagoras' theorem](https://en.wikipedia.org/wiki/Pythagorean_theorem#History) and [Pascal's triangle](https://en.wikipedia.org/wiki/Pascal%27s_triangle#History). Mathematicians often discover theorems independently. If our civilization were wiped out and evolution resulted in another taking our place, it is likely that they would reconstruct parts of our mathematics.

Other statements start in a private domain and transition into the public domain. An example of this would be the location of a targeted military strike. Initially, only the attackers know this information. Once the strike occurs, the defenders also learn it. If no media blackouts are in place, the rest of the public soon follow.

The public domain has this property - all information in it must continue to be in it indefinitely. In other words, releasing information into it is an irreversible process.

Is it possible to claim that all statements in the public domain are safe? Any ill effect they might have would have been inflicted the moment they entered the public domain. Thus they become defanged, unable to cause further harm, analogous to the casing of a used grenade.

Constructing a counterexample requires a bit of preliminary work:

Let `S` be a set of true statements. Define the closure `S*` of S as the set containing all statements which can be determined to be true using the information in S. If a rational agent is told the statements in `S`, then it can deduce the contents of `S*` by itself. Thus revealing `S` is equivalent to revealing `S*`.

If all statements in the public domain are safe, then any true statement in the public domain is also safe. Let `S` be an arbitrary set of such statements.

Since `S` is a subset of the public domain, `S` has been revealed to everyone. Since revealing `S` is equivalent to revealing `S*`, `S*` has also been revealed to everyone. This implies that `S*` is also a subset of the public domain.

Now for the counterexample:

It was 2015 - the [Syrian Arab Republic](https://en.wikipedia.org/wiki/Syria) was teetering on the edge of collapse, already written off by most as a failed state. With an ascendant [ISIS](https://en.wikipedia.org/wiki/Islamic_State), ethnic tensions with the [Kurdish minority](https://en.wikipedia.org/wiki/Kurds_in_Syria), border disputes with [Turkey](https://en.wikipedia.org/wiki/Turkey), an [insurgency](https://en.wikipedia.org/wiki/Syrian_opposition) against the government in full swing and an [outpouring of refugees](https://en.wikipedia.org/wiki/Refugees_of_the_Syrian_civil_war), things looked bad for the [Al-Assad](https://en.wikipedia.org/wiki/Bashar_al-Assad) government (which controlled less than half of the state's territory at that point).

Al-Assad was one of the few "middle-eastern dictators" who managed to ride out the wave of reform caused by the [Arab Spring](https://en.wikipedia.org/wiki/Arab_Spring) in 2011. It did not help his case that being backed by the [Russian Federation](https://en.wikipedia.org/wiki/Russia) put him and his government in the crosshairs of the USA. 

Governments who earned the ire of the USA had a tendency to face [sudden increase in rebel activity]() - the [CIA](https://en.wikipedia.org/wiki/Central_Intelligence_Agency) had been [arming, funding and training](https://en.wikipedia.org/wiki/Timber_Sycamore) the Syrian rebels since 2013. Having the [Republic of Iraq](https://en.wikipedia.org/wiki/Iraq) (which played host to multiple US military bases) as a neighbour probably didn't help matters.

Add to this mess a recent case of a Russian aircraft being shot down by Turkey (a [NATO](https://en.wikipedia.org/wiki/NATO) member) and one has the perfect powder keg. Enter 4chan's /pol/

Some context - [/pol/](https://en.wikipedia.org/wiki//pol/), or "politically incorrect", is one of 4chan's most infamous imageboards. With anonymous posting and minimal moderation, it is a safe haven for what can charitably be called heterodox thought. The activities of /pol/ often spilled over into meatspace (a term coined by the terminally-online to describe the physical world) with violent consequences.

The /pol/ hivemind decided to use its collective intelligence scouring [Google maps](https://en.wikipedia.org/wiki/Google_Maps) for images of Syria, looking for locations of military installations. With so many eyes on the problem, it became trivial. The users on /pol/ were able to positively identify one of the training camps used by the Syrian rebels. Using nothing more than freely available data (and the power of the hivemind), /pol/ did what Russian intelligence agencies like the [FSB](https://en.wikipedia.org/wiki/Federal_Security_Service) could not.

One of the users promptly forwarded the information to one of their contacts in the Russian Ministry of Defense, who [called in an airstrike](https://www.youtube.com/watch?v=BSsw_xbAImA) on the location given to them. /pol/ verified the destruction of the camp using google maps. /pol/ was a force of chaos, meddling with an ongoing conflict for nothing more than entertainment. Calling in Russian airstrikes - a good way to spend a Saturday evening.

A few caveats - when a story sounds too good to be true, it usually is. The exact details of this event are hard to corroborate (understandable, given the circumstances) so the reader is advised to take this tale with a heaping spoonful of salt. It's more an interesting tale to tell at social events than a case study around which to base policy. Nonetheless, this tale sheds some light on our analysis.

The public domain contained statements such their closure was dangerous to the interests of whoever was on the receiving end of the airstrike. This leaves us with two possible conclusions:
1. either the public domain can contain dangerous information, or
2.  safety is not preserved under closure.

If we use our earlier proof of the preservation of safety under closure, we are left to conclude that information can be dangerous despite being in the public domain. That said, closer examination of our definition of closure leads to a few interesting places.

So far, we have modelled information as a set of discrete statements which interact with each other under the laws of logic to generate new statements when the closure operator is applied. Consider a different model - where information is modelled by nodes in a graph and their interactions are modelled by edges, much like the popular image of a conspiracy theorist connecting pins on a board using red string.

This model captures an aspect of information that our earlier model did not - computing closures is costly. In our earlier example, /pol/ had much more time than users than the FSB. Though the FSB might have had better resources in terms of classified intelligence, the open-source intelligence (OSINT) gathered by /pol/ was not significantly worse. What is more, OSINT has the advantage of continuous decentralised vetting which ensures that it is almost always accurate.

In other words, the FSB might have had more pins on their drawing board but /pol/ was better at connecting them. In the end, only some pins on the board matter; adding more pins makes the puzzle harder to solve.

![](Images/infosafety_1.jpg)

To generalise, the very act of exploring configurations of a graph generates new information. Though a list of nodes implicitly contains every possible set of edges which can exist between them, searching for a particular configuration requires a non-trivial amount of effort. Thus the closure operator generates "new" information (in a manner of speaking).

Following this train of thought to its logical end leads to an interesting place - if a statement can be derived from a set of statements, is there a minimal set from which all statements can be derived? 

If we constrain ourselves to true statements, we run into [Godel's incompleteness theorems](https://en.wikipedia.org/wiki/G%C3%B6del%27s_incompleteness_theorems) - something which is too complex to be explored effectively here. If no such constraint exists, the minimal set takes a very interesting form - the [library of Babel](https://en.wikipedia.org/wiki/The_Library_of_Babel).

The library of Babel is an imaginary place constructed as part of a thought experiment. It is an infinite library containing every book that has, will be or can be written; tessellating hexagonal chambers filled with dusty tomes extend to infinity. Every one of your darkest secrets are sorted alphabetically and indexed, printed in a Times New Roman 12 point font on off-white paper, somewhere in the library.

The library contains exhaustive lists of every dirty secret of every government in the world, a list of vulnerabilities in all the popular encryption libraries and possibly a book titled "The PLA soldier's essential guide - locating every military installation in ~~Taiwan~~ Chinese Taipei". Clearly, the library is teeming with dangerous information.

Since the library exists only in our imagination, the threat posed by it is inconsequential. However, it is still possible to access the library if one wants to. When the library is reduced down to its bare essence, it is simply an infinite random string. Thus all one needs to do to look into the library is to continuously generate random strings. Since the library contains all that can be written, every random string must be contained in the library. In other words, it is possible to access an arbitrarily large subset of the library.

Even if one could access the whole library at once, one runs into a problem - how does one separate the nonsensical books from the sensible books? Thus the inhabitants of the library formed a cult - to wander from chamber to chamber, inspecting books for "nonsense" and throw the inscrutable books over the railing, into the infinite abyss in the centre of every chamber.

It doesn't matter how many chambers they clear out, since the library is endless. In every "cleansed" chamber lies the doorway to six other chambers. Even if they were to be able to access every chamber at once, the problem of deciding what counts as "nonsense" is still unsolved.

Somewhere inside the library lies a book which classifies and indexes every other book in the library - a Universal Index, which the cultists vainly hope to find. The futility of their quest is self-evident; the library is also filled with books that misclassify other books while appearing indistinct from the actual Universal Index.

If all information is contained in the library of Babel and if the library of Babel can be generated by the public, does that make all information public? Not in practice, since generating the library of babel does not allow one to retrieve any useful information from it.

Diving into this rabbit hole, interesting though it might be, leads us away from the question of safety and towards the very nature of knowledge itself, which is a topic for another day.

One common feature of all our examples so far is that the statements referred to agents in the real world. For instance, the information used by /pol/ makes a reference to the Syrian rebels. What happens when we restrict our statements to not make any reference to concrete entities?
**************************

### The concrete/abstract dichotomy

Even statements that are purely abstract can be dangerous - for instance, consider a statement that contains detailed instructions on the synthesis of sarin or the construction of a nuclear device.

But by what mechanism does the statement present danger? Here is a possible explanation:

A statement is sometimes more than just a statement - it is also an action. Consider a statement like "I refuse". It is both an observation about the subject's revocation of consent and the act of the revocation itself. By saying "I refuse", one does not merely passively comment on refusal; one actively performs the act of refusal.

Consider the nature of an object - it is both *what it is* as well as *the potential of what it could be*. For example, a caterpillar is a potential butterfly. A banknote is a potential bunch of metal coins. Metal shavings, when served with rice, is a potential lawsuit.

Consider the example of a file that contains detailed designs for constructing a gun using a 3D printer. Such a file is abstract - it makes no reference to any particular printer, person or gun. It is not a call to violence against any entity or an endorsement of firearm use. It is simply a neutral piece of information.

This information, when published, turns every 3D printer in the world into a potential gun (or a gunFactory, for those inclined towards OOP). The associated action of the information is equivalent to arming every owner (present and future) of a 3D printer, which most governments consider dangerous.

The USA's [Department of State](https://en.wikipedia.org/wiki/United_States_Department_of_State) took this view when a private company published such information; the publication was viewed as a violation of the [1976 Arms Export Control Act](https://en.wikipedia.org/wiki/Arms_Export_Control_Act), which suggests an equivalence between a concrete firearm and an abstract representation of a firearm.

The State Department was accused of violating free speech through its actions, resulting in a legal victory for the [FOSSCAD](https://fosscad.org/fc/) communities. The genie was out of the bottle; designs for a 3D printed gun are widely available online and will likely remain so for the foreseeable future.

The point being this - the associated action of publishing abstract information can be dangerous. Separating the act of publishing information is difficult to disentangle from the information itself. If nobody knows a piece of information, it has no way of affecting the real world; it may as well not exist.

In the end, we are left with a piece of information that:

1. is true,
2. is public knowledge and
3. does not refer to any real-world entity directly
 
but is nonetheless dangerous.

If it is difficult to come up with universal laws that describe safety of information, could useful results be derived by assuming the safety or lack thereof of the given information?
***************************
                          
### Boolean operators:

#### Negation:

The negation operator (`~`) inverts the truth value of a statement. Since there is no absolute correlation between a statement's truth value and its safety, no useful result can be obtained using only this operator.

Let `S` be the statement "this is how you build a bomb: \<instructions to build a bomb\>". Its negation `~S` would be "This is *not* how you build a bomb: \<instructions to build a bomb\>". Clearly, negation has no effect on the safety of `S`.

#### Conjunction:

The conjunction operator (`∧`) produces a statement which is true if and only if both the operand statements are true. Here are a few interesting effects of applying this operator:

Let __n__ be a natural number such that running __2<sup>n</sup>__ cycles on a computer is infeasible. Imagine there is a password of size __2n__ bits, whose revelation will result in danger. Let __S<sub>1</sub>__ and __S<sub>2</sub>__ state the first and last __n__ bits of the password respectively. By our definition of __n__, both __S<sub>1</sub>__ and __S<sub>2</sub>__ are individually safe. However, __S<sub>1</sub>∧S<sub>1</sub>__ is dangerous, since it reveals the password. Thus the conjunction of two safe statements may be dangerous.

Now let __S<sub>i</sub>__ be the statement that the password is __i__, where __i__ ranges from __0__ to __2<sup>n</sup>__. Let the set of all such  __S<sub>i</sub>__ be __S__. __S__ covers every possible value the password can take, including the actual value of the password. Thus there is some statement in __S__ which is dangerous. Let __T__ be the conjunction of every statement in __S__. No useful information about the password can be derived from __T__ since searching for the correct component in __T__ is the same as trying out every combination of the password, which is infeasible by our definition of __n__. Thus the conjunction of safe and dangerous statements might be safe.

For another example of conjunction neutralising danger, let __S<sub>1</sub>__ be the statement that "There is a leak of an unknown gas in the theatre" and __S<sub>2</sub>__ be the statement that "The unknown gas is nitrogen, which makes up over 70% of air normally". __S<sub>1</sub>__ might cause a panic resulting in a stampede in a crowded theatre, while __S<sub>1</sub>∧S<sub>2</sub>__ will not.

#### Disjunction

The disjunction operator (`∨`) produces a statement which is true if either or both of the operand statements are true. Here are a few interesting effects of applying this operator:

The same technique used in the earlier example of listing all possible passwords produces a case where a dangerous statement can be made safe by applying the disjunction operator with other safe statements. Just as __T__ is the conjunction of every statement in __S__, let __T'__ be the disjunction of every statement in __S__. __T'__ is safe for the same reasons that __T__ is safe.

An example where the disjunction of only safe statements produces a true dangerous statement: consider a drone navigating a minefield. The drone can move front, back, left or right and must avoid mines. Imagine that there is a mine in front of the drone. The statement "there is a mine in front of the drone" is safe since it allows the drone to take an alternate path.

Let __S<sub>X</sub>__ be the statement "There is a mine at __X__". __S<sub>front</sub>__ is true and safe. __S<sub>back</sub>__ is false but safe, since the drone does not risk destruction by assuming that there is a mine behind it. When it comes to minesweeping, a false negative is much worse than a false positive.

Consider the statement __S<sub>front</sub>∨S<sub>back</sub>∨S<sub>left</sub>∨S<sub>right</sub>__ - while true, it is dangerous to the drone since it causes it to become paralysed by restricting all avenues of movement. Since this statement causes the drone to suspect that there could be a mine in every square around it, it is forced to remain where it is indefinitely.
************************

### Conclusion

Why is this analysis important? Given that we have a pretty good intuitive understanding of what is safe and dangerous, why the need to formalize and axiomatize?

Since governments use the safety (or lack thereof) of statements to decide what is censored or not, a legal framework for safety becomes important. Laws against libel and defamation often rely on the accuser demonstrating concrete harm to their interests as a direct cause of the offending statement. Distinctions need to be made between statements which are merely distasteful and those which pose actual danger to entities.

Another application of such a framework would be in the analysis of complex cryptosystems. Perhaps the results derived can be used to automatize the process of proving safety and finding leaks.

Identifying dangerous statements is one thing, but the question of what can be done about them is another thing entirely. Dangerous falsehoods are easy to counter using laws against defamation, but what about dangerous truths? One of the defences against an accusation of defamation is to prove that the statement, despite being harmful, was true.

Any mechanism to suppress dangerous truth will need to be used with surgical precision, since any heavy-handedness will result in accusations of silencing truth. On the other hand, those seeking to silence inconvenient truths will tend to abuse such mechanisms to their advantage. Add to this the reluctance to label as dangerous those statements that are harmful only to competing entities and we have a very difficult problem to solve.

Dangerous truths in the private domain are often suppressed using national security laws, though these are toothless when dealing with dangerous information in the public domain. If a whistleblower illegally leaks dangerous information to a journalist who publishes the same in a paper, it is usually only the leaker who is prosecuted for breaching non-disclosure contracts. The journalist, editor and the readers of the paper are usually immune, since they gained the information from the public domain.

The journalist is often seen as the agent responsible for publication, though that is really not the case - the publication is the sole responsibility of the whistleblower. Had the journalist not published the information, all the whistleblower needs to do is to find another journalist (or dump the information on places like /pol/). Sometimes the associated journalists mysteriously disappear, commit "suicide" or get a [free helicopter ride from the government](https://en.wikipedia.org/wiki/Death_flights).

Are there any measures against dangerous true statements in the public domain? Here is an example.

In countries which use the jury system, a peculiar phenomena arises as a consequence of the legal system - [jury nullification](https://en.wikipedia.org/wiki/Jury_nullification). A jury has the ultimate freedom to decide whatever they want without any fear of retaliation from the court. If the jury's verdict is too harsh against a defendant, the defendant may appeal to a higher court. On the other hand, if the jury's verdict is too lenient, nothing can be done since the rule against double jeopardy disallows prosecuting someone for the same crime twice. Thus the jury has the power to unilaterally and irreversibly shield someone from criminal prosecution, no matter how much evidence there is of their guilt.

![](Images/infosafe.png)
                       
An infamous example of this is the case of [Commander K. M. Nanavati vs. State of Maharashtra](https://en.wikipedia.org/wiki/K._M._Nanavati_v._State_of_Maharashtra), in which a naval officer who admitted to killing someone was acquitted by a sympathetic jury. The resulting outrage resulted in the judge overturning the verdict and a subsequent retrial.

In countries where the jury system is still used, creative workarounds are used by judges and lawyers who do not wish to let jury nullification occur, like [removing jurors](https://fija.org/library-and-resources/library/jury-nullification-faq/should-i-discuss-jury-nullification-with-my-fellow-jurors.html) who bring up nullification to the rest of the jury or [lying to the jurors](https://fija.org/library-and-resources/library/jury-nullification-faq/is-it-true-that-jury-nullification-is-invalid.html) by saying that jury nullification is not valid. The possibility of jury nullification is a true statement in the public domain, suppressed because of the danger it poses to the legal system.

The inherent fuzziness of a concept like "safety" makes it difficult to prove any non-trivial result about safety. In this article alone, all we did was come up with counterexamples to possible results; not a single proof has been produced. Even if we have a foolproof system to identify unsafe statements, there is much disagreement on what exactly ought to be done about such statements. For instance, contrary to popular belief, it is not necessarily illegal to shout "fire" in a crowded theatre.

In conclusion, just as the development of Boolean algebra did not really make the world more honest, it is unlikely that the development of an "algebra of safety" would make the world more safe.
