

# FAQ

- [Who are you, what do you play?](#Who-are-you-what-do-you-play)
- [How can i contact you?](#How-can-i-contact-you)
- [What is this?](#What-is-this)
   - [What am i seeing, caption?](#What-am-i-seeing-caption) 
   - [Why did you create it?](#Why-did-you-create-it)
   - [How was it made?](#How-was-it-made)
   - [What trees.CFR did you use to build the cards/questions?](#What-treesCFR-did-you-use-to-build-the-cardsquestions)
   - [Whitch subset did you used and why?](#Whitch-subset-did-you-used-and-why)
   - [What is the EV diff?](#What-is-the-EV-diff)
   - [How did you choose interesting and important questions?](#how-did-you-choose-interesting-and-important-questions)  
- [What is Anki?](#What-is-Anki)
   - [More about Anki](#More-about-Anki)
- [**THE SECRET OF GTO**](#What-is-the-secret-of-GTO-in-poker)  
   - [The paradoxes of GTO](#The-paradoxes-of-GTO)
- [**Buy Anki cards packages NOW**](#Buy-Anki-cards-packages)
   	- [The spot i am interested is not listed,what can i do?](#The-spot-i-am-interested-in-is-not-listed)  
	- [I want to buy the program to create the Anki cards myself, blunderhunter.](#I-want-to-buy-the-program-to-create-the-Anki-cards-myself-blunderhunter)
	- [How do i import what i just bought?](#How-do-i-import-what-i-just-bought)

<h1 id="Who-are-you-what-do-you-play">
  Who are you, what do you play?
</h1>

Poker-player and programmer, i can speak English, Spanish, French.  
I played pretty all modalities and stakes online for 10+ years, lately mostly MTTS.

<h1 id="How-can-i-contact-you">
  How can i contact you?
</h1>

The best is to send me an email : *blunderhunter.poker@gmail.com*  

<h1 id="What-is-this">
  What is this?
</h1>   

It is a study tool; the main goals are:
- Train Your intuition.
- Find situations where you are totally wrong for study them deeply.

<h1 id="What-am-i-seeing-caption">
  What am i seeing, caption?
</h1> 

![Ledgend](https://i.imgur.com/UCw9XRj.png)
		 
		 
<h1 id="Why-did-you-create-it">
  Why did you create it?
</h1> 

Mostly to win time, but also to offer the benefits of Spaced Repetition.  
When you study GTO with Piosolver for example:  
- It takes huge time to solve the tree.
- There is a lot of 'useless' information.
- It is easy to fall into a 'passive' while studying...
- ... and again, more time in front of the computer!
      
I try to solve these problems and create new ways of learning.
I build it alone as a passionate, as i love programming, poker and Game Theory Optimal.  
I made it first for use it myself, as i tried all the others competitors, and i feel something was clearly missing and i could do better.


 <h1 id="How-was-it-made">
  How was it made?
</h1> 

- Build the trees.cfr with Piosolver, Subset of 40 strategically different Boards  
- I build algorithms in order to know witch information of a tree is interesting/important. I extract it
- I import this information into Anki.

 <h1 id="What-treesCFR-did-you-use-to-build-the-cardsquestions">
  What trees.CFR setting did you use to build the cards/questions?
</h1> 

I build them with top players from all formats, using GTO ranges, 0.2% accuracy and many sizings.  
When you purchase any pack you get all the configuration of the trees.cfr
     
 <h1 id="Whitch-subset-did-you-used-and-why">
  Which subset did you used and why?
</h1> 

I made a subset of 40 different flops myself.  
They are all strategically different.  
I didn’t use pio subsets as they are made for a different purpose. (preflop solving)  
For example, the 49 flop subset of pio include 3s4s6s and 5s7s9s.  
I consider these two boards very similar strategically...  
I looked at distribution percentage as well, for example, monochrome boards appear only 5% of the times.  
It makes no sense to include a lot of them in the subset.


<h1 id="What-is-the-EV-diff">
  What is the EV diff? 
</h1>


How big the error between two options in relation to the pot is, example:  
- We can only **bet pot** or **check**,  
- Ev of betting is **110** chips and the ev of checking is **95** chips  
- The **pot is 80** chips  
- The difference of EV between bet and check is **15** (110-95)  
- Witch is **18.75%** of the pot (15*100/80)
- EV Diff % = **18.75%**  

Usually when the EVDiff% is less than 2%, it doesn’t matter what you do, and you should play exploitatively.

<h1 id="How-did-you-choose-interesting-and-important-questions">
  How did you choose interesting and important questions?
</h1>

The algorithms i made follow couple of principles and adjust all the settings automatically depending of the situation:
- If We never Continuation bet of the flop QQ, it should never ask if barrel or not on the turn..
- Same logic if opponent is never Betting big on flop, the anki cards will never ask you what to do in turn after opponent Bet big on flop.. As this line is never taken.
- If all the Evs are similar , it is useless to ask what to do.
- If all the Evs are too different , it is useless to ask what to do. (we never fold top set on flop vs a bet..)
- More secret stuff

[Video with more details](https://www.youtube.com/watch?v=7Bb0wTtsbeA)

<h1 id="What-is-Anki">
  What is Anki?
</h1>

- https://apps.ankiweb.net/
- Anki is an opensource software frequently updated since 2012,
    - It comes blank and you have to add 'Cards' in 'Decks' with thing you want to learn.
    - A Card have two sides, Front (the question) and back (the answer)
    - If your answer is wrong or it was hard, anki will ask you again soon.
    - But if it feels easy the card might not show again until next month for example.
    - Heavily used for lean new languages, and by medical students etc.

<h1 id="More-about-Anki">
  More about Anki:
</h1>

- APP available on PC MAC ANDROID and iOS .
- Spaced repetition memorization:
![Forgetting curves](https://www.supermemo.com/assets/images/frontpage/graph/9-3-1-en.png)
- Have a LOT of plugins.
- Here few interesting articles:
- [13 Lucky Tips for using Anki and Spaced Repetition in 2019](https://getpolarized.io/2019/05/25/13-lucky-tips-for-using-anki-and-spaced-repetition-2019.html#)
- [Chasing 10X: Leveraging A Poor Memory In Engineering](https://senrigan.io/blog/chasing-10x-leveraging-a-poor-memory-in-software-engineering)
- [The use of spaced repetition memory systems has changed my life over the past couple of years. Here's a few things I've found helpful](https://twitter.com/michael_nielsen/status/957763229454774272)
- [Augmenting Long-term Memory](http://augmentingcognition.com/ltm.html)
- [Supememo](https://www.supermemo.com/en)

<h1 id="What-is-the-secret-of-GTO-in-poker">
  What is the secret of GTO in poker?
</h1>

Even if GTO frequency is 100% for X combo in Y node.  
When you play, in a LOT of the cases, **you don’t want to follow GTO.**  
Check the EVs...  
When the **EVs are very close**, it doesn’t matters what you do, and **you should always play exploitatively.**  

In both images the pot is 58:  

This information is totally useless...  By misunderstanding a lot of players will try to learn that KQs is a check...  
![Useless](https://i.imgur.com/FPjoikw.png)

But here, if we were thinking about checking this combo it is a clear mistake..  
We are losing 7 chips in a pot of 58 by checking instead of betting!  
![Impotant](https://i.imgur.com/AeksVDW.png)  
But it **doesn’t matters** at all if we bet big or small, (even though PIO choose to bet 99% of the time)..  
..In the theory, in practice you better choose the line you think your opponent will make mistakes or the line you studied more than him.

The difference is so close that **any small change from the inputs can change radically the frequencies**:  
- If the preflop range of HERO or villain is not the same in table than in the pio sim.  
- If HERO or villain **don’t play exactly the same strategy** in this node, from the table to the pio sim.  
- If HERO or villain don’t play exactly the same strategy in **FUTURE nodes**, from the table to the pio sim.  
- Etc..  

<h1 id="The-paradoxes-of-GTO">
  The paradoxes of GTO:
</h1>

- Usually the earlier in the hand, the closer are EVs.
- When you can bet or check, the EVs are closer than when you are facing a bet.
- The later in an hand, the more possible it is your opponents play differently than the equilibrium.

That’s why you may find relatively few questions for CBeting Flop for example, the evs are just too similar and for most of the combos it just doesn’t matters..

<h1 id="Free-Anki-cards-Trial">
  Free Anki cards (Trial)
</h1>

<h1 id="Buy-Anki-cards-packages">
  Buy Anki cards packages.
</h1>

Email me witch pack(s) you are interested in :  
**blunderhunter.poker@gmail.com**  
And i will let you know how to pay (Skrill Neteller BTC ..)  

I am currently building the website to automate the sells,   
Consider yourself lucky to buy it now, as the prices will go up when is it open.  

I currently have ready: 
- CASH 100bb OR BUvsBB 
- CASH 100bb OR EP/MPvsBB
- CASH 100bb 3B SBvsBU
- CASH 100bb OR COvsBU
- CASH 100bb 3B HU
- MTT 50bb 3B HJvsBU
- MTT 30bb OR BUvsBB
- MTT 30bb OR EP/MPvsBB
- MTT 17bb OR HJvsBB
- SPIN 25bb Limp HU
- SPIN 25bb OR HU

Every pack comes with :  
- Around 50000 Anki Card/ questions in total.  
	- Every pack is very well arranged in a similar way:  
	- ![good order clean](https://i.imgur.com/aK1am2J.png)
	- There is a BIG file and 3 smaller files, (you might want to take the smaller ones in your phone, and keep you big one on your computer )
- Picture of Piosolver setting used; sizings, ranges etc
- Text document explaining the very few steps for importing the pack in windows/mac/iOS/android.

**READY TO USE, SMARTPHONE AND DESKTOP.**

<h1 id="The-spot-i-am-interested-in-is-not-listed">
  The spot i am interested in is not listed,
</h1>

- Email me **blunderhunter.poker@gmail.com**  witch situation you are interested in, and i will give you a price and how many days i can create it depending of the complexity of the trees.
- Or you can [Vote here](https://linkto.run/p/FZ5SZ3DN) which situation you are interested in, i will pick the most voted.

<h1 id="I-want-to-buy-the-program-to-create-the-Anki-cards-myself-blunderhunter">
  I want to buy the program to create the Anki cards myself, blunderhunter.
</h1>

That was my first idea, but i choose to create the cards myself, BlunderHunter is a bit challenging to use, it require a lot of time to make the CFR, extract from them, convert to anki format and on top of that you need to rent a cloud supercomputer.

Selling the cards have those advantages:
- Between the time you buy them and you can start to study is less than one minute.
- Anyone can use them, no need to pourchase Piosolver license,
	- But If you dont have it and take you game seriously, just pourchase it, you will not regret it.
	- As i mention, one of the goals of the cards i am selling is to find spot were you are totally wrong for study them with piosolver with a more global view than my cards.
- You have the guarantee of studying good trees, GTO preflop ranges, perfect sizings.

If you really want it, contact me.

<h1 id="How-do-i-import-what-i-just-bought">
  How do i import what i just bought?
</h1>

Congratulation! You will now study the equilibrium much more efficiently!  
As you can see, the files of the pack are relatively smalls, but they are compressed,  
When you import them, it is possible your app will freeze for a moment,  
Please Be Patient! :)

- For Windows/MAC/LINUX:

Just download the official application here:

https://apps.ankiweb.net/

Once it is open, go in file / import 
And choose the “.apkg” you want.

- Android:

The 'AnkiDroid' app is really good, 
Just download (or sync with dropbox/evernote) the file .apkg you want,
If the icon's file show anki, just click it.
IF not, then touch hold it and choose 'open with ankidroid'

- iOS

You can purchase the official app https://itunes.apple.com/us/app/ankimobile-flashcards/id373493387

It is the only source of income of the developer.

If you don’t want to pay for it, you have (AsFarAsIKnow) three options:
- Use ankiapp :
	- https://www.ankiapp.com/index.html 
	- Create an account and download 'ankiapp' in your iPhone
	- With your computer, go here https://api.ankiapp.com/nexus/ and login
	- Import the .APKG file you want to study in you iPhone
	- Wait for the email confirmation and it will sync in your phone.


- Use the web version of the official anki application https://ankiweb.net/about in safari.

- Consider buy a cheap android tablet/phone just for study.
You won’t be distracted.



