


# FAQ

- [Who are you, what do you play?](#Who-are-you-what-do-you-play)
- [How can i contact you?](#How-can-i-contact-you)
- [What is this?](#What-is-this)
   - [What am i seeing, caption?](#What-am-i-seeing-caption) 
   - [Why did you create it?](#Why-did-you-create-it)
   - [How was it made?](#How-was-it-made)
   - [Why did you choose this name? BLunderHunter?](#Why-did-you-choose-this-name-BLunderHunter)
   - [What trees.CFR did you use to build the cards/questions?](#What-treesCFR-did-you-use-to-build-the-cardsquestions)
   - [Whitch subset did you used and why?](#Whitch-subset-did-you-used-and-why)
   - [What is the EV diff?](#What-is-the-EV-diff)
   - [How did you choose interesting and important questions?](#How-did-you-choose-interesting-and-important-questions)  
- [What is Anki?](#What-is-Anki)
   - [More about Anki](#More-about-Anki)
   - [How to configure Anki for Poker?](#How-to-configure-Anki-for-Poker)
- [**THE SECRET OF GTO**](#What-is-the-secret-of-GTO-in-poker)  
   - [The paradoxes of GTO](#The-paradoxes-of-GTO)
   - [So, Why is GTO soo usefull? The loosing game.](#So-Why-is-GTO-soo-usefull-The-loosing-game)
- [Download Free Anki Cards Sample](#Free-Anki-cards-Sample)
- [**Buy Anki cards packages NOW**](#Buy-Anki-cards-packages)  
   - [The spot i am interested is not listed,what can i do?](#The-spot-i-am-interested-in-is-not-listed)  
   - [I want to buy the program to create the Anki cards myself, blunderhunter.](#I-want-to-buy-the-program-to-create-the-Anki-cards-myself-blunderhunter)
   - [Do i need piosolver to use this?](#need-piosolver)
   - [How do i import what i just bought?](#How-do-i-import-what-i-just-bought)

<h1 id="Who-are-you-what-do-you-play">
  Who are you, what do you play?
</h1>

Poker-player and programmer, i can speak English, Spanish, French.  
I played pretty all modalities and stakes online for 10+ years, lately mostly MTTS.

<h1 id="Why-your-website-is-so-ugly">
  Why your website is so ugly?
</h1>

Because i just wanted something clear and usefull,  
Marketing and website are not 'my area', in order to deliver at the lowest price possible i made it quick.  
On the other hand, building good software yes it is my area, and it is where i feel the most important to spend my efforts.  
Thats why i didnt invest much (time and money) in website and marketing :)  


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
- Use your study time more efficiently.

<h1 id="What-am-i-seeing-caption">
  What am i seeing, caption?
</h1> 

![Ledgend](https://i.imgur.com/R9Zrmih.png)

Video:  

[![What-am-i-seeing](https://proxy.duckduckgo.com/iu/?u=https%3A%2F%2Fih1.redbubble.net%2Fimage.25011287.7046%2Fap%2C550x550%2C12x12%2C1%2Ctransparent%2Ct.u1.png&f=1)](https://www.youtube.com/watch?v=EMAGFn85Bb8 "What-am-i-seeing")

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

<h1 id="Why-did-you-choose-this-name-BLunderHunter">
  Why did you choose this name? BLunderHunter?
</h1>
Easy, A Blunder in chess is doing a big mistake, so i wanted to filter all the useless stuff from GTO and focus on what matters. More below.


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

- Excluding most of the hands with close EVs between the possible options, 
	- It is useless to know what GTO does, if it is close you just need to play exploitatively.
	- Only aim to find big theoretical misunderstandings.
- Excluding most of the combo mixing,
	- If GTO is mixing with a hand, by definition EVs are close, so it is irrelevant to know(study) GTO is checking 90% or only 20%
- Excluding obvious hands,
	- Obviously we are never gone fold the nut on the flop (the difference between folding and calling vs a bet, will be huge, and again useless to study)  
- Excluding all hands with low combo weight,
	- If QQ only come 1% of the time in river  (because it does not play the same way on flop for example,) it is useless to know what to do with that hand in that node..because it almost never comes here..(never been played that way)
- Excluding every low frequency line, 
	- If the flop is never being betting small, again, it is useless to know how to play against small flop bets..
	
- etc etc etc, more secret stuff!

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

<h1 id="How-to-configure-Anki-for-Poker">
  How to configure Anki for Poker? :
</h1>

I made a video for this :

[![cfgANKI](https://proxy.duckduckgo.com/iu/?u=https%3A%2F%2Fih1.redbubble.net%2Fimage.25011287.7046%2Fap%2C550x550%2C12x12%2C1%2Ctransparent%2Ct.u1.png&f=1)](https://www.youtube.com/watch?v=YaMYy0jh_DA "cfgANKI")

Here are the setting i suggest:

![alt text](https://i.imgur.com/OshHNm6.png)  

But look at the video for see how sync phone and PC (easy), restructure the fields (for example study all the river vs bet randomly) etc   


<h1 id="What-is-the-secret-of-GTO-in-poker">
  What is the secret of GTO in poker?
</h1>

Even if GTO frequency is 100% for X combo in Y node.  
When you play, in a LOT of the cases, **you don’t want to follow GTO.**  
Check the EVs...  
When the **EVs are very close**, it doesn’t matters what you do in theory(even if pio does something 100%),   
And in practice **you should always play exploitatively.**  

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

- Usually the **earlier in the hand and the deeper we are, the closer are EVs.**
- When you can bet or check, the EVs are closer than when you are facing a bet.  

So as we see in the previous section, you might think play exploitativly in flop and a more GTO style is river is the winning combination, but :  

- **The later in an hand, the more likely it is your opponents play differently than the equilibrium.**  

That’s why you may find relatively few questions for CBeting Flop for example, the evs are just too similar and for most of the combos it just doesn’t matters..  

<h1 id="So-Why-is-GTO-soo-usefull-The-loosing-game">
  So, Why is GTO soo usefull? The loosing game.
</h1>

Poker is a very complex game, we are still in the stage of ‘loosing game’   

'Loosing game' means **most of the winning does not come from being playing actively,**     
**But because the opponent made a mistake...**   
To **win this kind of game, you just need to not make stupid mistakes..** (AKA blunders in chess :P)      

That is what i had in mind creating BlunderHunter.  


<h1 id="Free-Anki-cards-Sample">
  Free Anki cards (Sample)
</h1>

<a href="https://github.com/jrmtoubRHL/jrmtoubRHL.github.io/raw/master/Free_sample_100bb_3B_HU.apkg" download>Download 100 free anki cards (HU CASH 3betpot)</a>  
*Some phone display the cards in a weird way, if you see only two color deck, there is an easy solution, let me know.*


<h1 id="Buy-Anki-cards-packages">
  Buy Anki cards packages.
</h1>


I currently have ready: 
- [CASH 100bb OR BUvsBB](https://payhip.com/b/qg9J) 
- [CASH 100bb OR EP/MPvsBB](https://payhip.com/b/bEkr)
- [CASH 100bb 3B SBvsBU](https://payhip.com/b/Iakb)
- [CASH 100bb OR COvsBU](https://payhip.com/b/WyAc)
- [CASH 100bb 3B HU](https://payhip.com/b/mvQB)
- [MTT 50bb 3B HJvsBU](https://payhip.com/b/dRXt)
- [MTT 30bb OR BUvsBB](https://payhip.com/b/QhIm)
- [MTT 30bb OR EPvsBB](https://payhip.com/b/cGdr)
- [MTT 17bb OR HJvsBB](https://payhip.com/b/9RlA)
- [SPIN 23bb Limp HU](https://payhip.com/b/xUnv)
- [SPIN 25bb OR HU](https://payhip.com/b/gmSo)
- [SPIN 25bb OR SBvsBB (3max)](https://payhip.com/b/QXGN)
- [SPIN 25bb OR BUvsBB (3max)](https://payhip.com/b/quQw)  

[The online shop link](https://payhip.com/BlunderHunter)  

I give discount if you buy a Bundle (all your modality packs include)  
You **keep the discount % for any new spot i add in future**;  

- [CASHGAME BUNDLE](https://payhip.com/b/Xpk3)
- [SPIN BUNDLE](https://payhip.com/b/1Kk6)
- [MTT BUNDLE](https://payhip.com/b/q2KR)
- [POKERMASTER BUNDLE](https://payhip.com/b/gpT0)

If you want to pay with **Skrill€/Neteller$/BTC** just email me:
**blunderhunter.poker@gmail.com**  

Every pack comes with :  
- Around 50000 Anki Card/ questions in total.  
	- Every pack is very well arranged in a similar way:  
	- ![good order clean](https://i.imgur.com/aK1am2J.png)
	- There is a BIG file and a smaller file with diferent questions, (you might want to take the small one in your phone, and keep you big one on your computer.. )  
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

<h1 id="need-piosolver">
Do i need piosolver to use this?
</h1>

No, Anyone can use them, no need to pourchase Piosolver license...
- But If you dont have it and take you game seriously, just pourchase it, you will not regret it.
- As i mention, one of the goals of the cards i am selling is to find spot were you are totally wrong for study them deeply later with piosolver, it give you a more global view than my cards. It is a diferent and completary study tool.


<h1 id="How-do-i-import-what-i-just-bought">
  How do i import what i just bought?
</h1>


Congratulation! You will now study the equilibrium much more efficiently!  
As you can see, the files of the pack are relatively smalls, but they are compressed,  
***When you import them, it is possible your app will freeze for a moment, even for 5minutes, 
Please Be Patient! :)***   
If it still lagging a bit just after the import, restart anki software and it will be ok.  
*Some phone display the cards in a weird way, if you see only two color deck, there is an easy solution, let me know.*

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



