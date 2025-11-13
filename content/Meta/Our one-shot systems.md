---
title: Our one-shot systems
draft: true
tags:
enableToc: "false"
---
 
Before diving into System V2.2, I want to take a moment to reflect. Every version has been shaped not only by my own learning as a DM but also by my wonderful players, who graciously sat in and tested the system even on short notice.

While the main Wyrda campaign is deeply built on the 2024 5e Rules, things shifted when we explored one-shot territory. Some rules worked well, but others did not. When the idea of a gritty, darker Zombie one-shot came up, one that could test the aspects of humanity, I loved it. It probably helped that I naturally lean more sci-fi dystopian than fantasy. The core issue, however, is that 5e can sometimes be difficult to adapt to such vastly different themes.

Though plenty of DMs could make that conversion, as a newer DM, my instinct was, "Okay, I'll just find one designed for it." That led me to research systems like Savage Worlds, All Flesh Must Be Eaten, and even Fallout to see if I could use them in Foundry.

The core issue quickly reared its head. I simply couldn't pick up the new rules fast enough. The documentation was clear, but my personal understanding was *lacking*. I didn't have the time *(or patience)* to teach my players an entirely new system in Foundry _and_ master it well enough to answer questions quickly. So, I pivoted to something more *manageable*: **building my own system**.

Of course, in hindsight, coding a full system is incredibly difficult. I was confident with my coding skills, but I quickly realized the depth required not just for the mechanics, but for usability. After test after test and countless YouTube videos, I had nothing. With an impending deadline, I pivoted to something more trustworthy: Excel. That is how V1 was born (names are hard, as you've seen me struggle with on stream).

*Avia’s Thoughts for Other DMs*

> Since then, I've met some amazing DMs with amazing systems built entirely on Excel.
> 
> Don't be afraid to just sketch out a fun idea on Excel and test it out!

That gave me the flexibility I needed, and after some early playtests with my ever-patient ~~victims~~ players, the first version came to life.

## V1

The first iteration, **System V1**, was initially intended for a Zombie One-Shot but morphed into an **Alien One-Shot** - _Escape Penance_. The core idea was to place the players on a ship with an alien predator hunting them down. To sow anxiety, I decided to "spice things up" by adding a traitor player. I told the group, "One of you is a traitor." What I _didn't_ tell them... or even the players I selected was that there were **two** traitors, and each one thought they were the only one.

*Avia's Thoughts for Other DMs*

> Don't do what I did here. Common Rookie mistake. Using traitors _and_ telling the players slows the scenes down.
> 
> It's fine if you have a lot of time to build it, but I only had two sessions of three hours. If you try this idea, 100% **don't set an end time** for the players; it ends when it ends.
> 
> Give them time to explore the ship, talk to each other so the traitors feel conflicted or emboldened. Treat it like a longer session of Among Us.
> 
> Also do your best to test PVP combat! This will come up if you're using traitors... (Which I neglected to do)

A scheduling issue meant we ran an unnamed **Zombie One-Shot** _before_ the Alien one-shot, and that's when my first major issue surfaced: **playtesting**. I hadn't playtested V1 enough. I had run some minor roleplay scenes with the players, but never combat, and that’s precisely where the system’s weaknesses showed.

To my players' credit, they killed it. It was a memorable night! For me, though, it meant the following week was dedicated to fixing the system and ironing out its issues.

### V1 Mechanics

V1 was designed with a heavy focus on **groundedness and grittiness**. It included:

- **8 Stats:** Agility, Charisma, Constitution, Intelligence, Luck, Perception, Strength, and Willpower.
    
- **Stamina & Sanity:** These resources would drain based on actions taken (Small, Medium, or Big cost).
    
- **Traits:** Special abilities based on the maxed stat.
    
- **Inventory:** Capacity based on your **Strength (STR)** score.
    
- **Armor:** Items players could find.
    
- **Cover System:** A mechanic to increase your **Defense Rating (DR)**.
    
- **Targeting:** Specific body parts had different DR ratings but with damage multipliers (e.g., attacking the head was harder but did more damage).
    

### V1 Post-Mortem: What Didn't Work

Very quickly, I realized several features were unnecessary or clunky:

- **Cover:** Never used. This might be suited for military or pure shooting one-shots, but here it felt like dead weight.
    
- **Traits:** They rarely came up. The only two used were _Ghoststep_ (+1 to DR and evasion from traps once) and _Tactician_ (Hints on puzzles and identifying tech).
    
- **Armor:** Didn't come into play until the very end, and modifiers made its effect mostly inert.
    
- **Targeting Specific Body Parts:** Felt unnecessary; players would just aim for the kill shot, making this an additional hoop to jump through.
    
- **Stat Imbalance:** **Luck** quickly felt like the essential stat to have, while **Charisma** was a clear dump stat.

**A Note on Legacy**

Fun fact: One of the players from _Escape Penance_, Magnolia, potentially will be running it again and its sequel. That world is now theirs, and I’d love to see how they expand and grow it.

## V2

**V2** was designed specifically to address the clutter of V1. _Escape Penance_ was a massive step in my DM journey, a story every DM has where they tried to do too much and were brought back to reality. 

While the players enjoyed the story and world, it was clear the system was a bit half-baked, requiring more time and streamlined planning. A lot of the mechanics were overly complicated and unused.

V2 shifted away from horror/realism and was focused more on a **Cyberpunk** theme. I felt I wanted to step into something a little more familiar to me and away from the grit of horror (it probably didn't hurt that I got really into _Cyberpunk 2077: Phantom Liberty_).

**V2 never actually had a one-shot; it was dedicated entirely to system tests.**

*Avia's notes for other DM's*

> This is recommended, even if it sounds like I swung too heavily in the opposite direction. Do **a lot of playtests**.
> 
> Add new players. Add new ideas. Every iteration needs to test something new for you, the DM. Be prepared for a lot of constructive criticism and for people to say, **"Why though?"**

### Reworked Mechanics

The key inclusions and fixes for V2 were driven by the need for more cinematic moments but also simplicity:

*Whether that happened is another question*.

- **Stats were reworked:** Stats were shifted into **3 main groups** (Agility, Mind, Strength), leading to **11 total stats** based on those groups.

| GROUP    | STAT      |
| -------- | --------- |
| AGILITY  | AWARENESS |
| AGILITY  | MOBILITY  |
| AGILITY  | PRECISION |
| AGILITY  | REACTION  |
| MIND     | CONTROL   |
| MIND     | FOCUS     |
| MIND     | INSIGHT   |
| MIND     | SENSE     |
| STRENGTH | ENDURANCE |
| STRENGTH | FORCE     |
| STRENGTH | PRECISION |
| STRENGTH | PRESENCE  |

- **Classes & Combat Triangle:** The three main groups led to three primary classes (with a secret fourth class never tested). They work like a rock-paper-scissors situation: **Maulers** beat **Wraiths**, who beat **Psykers**, who beat **Maulers**.
    
    - **Maulers:** Inspired by Bane and All-Might (_MHA_).
        
    - **Wraiths:** Inspired by the Flash, Zoom, and Hel (_Ghostrunner Project HEL_).
        
    - **Psykers:** Inspired by Songbird (_Cyberpunk Phantom Liberty_) and Jean Grey.

- **Combat Flow:** **Freeflow combat** was replaced by **Act-React** mechanics to prevent players from repeatedly ganging up on a single boss enemy.

- **Cover:** Completely abandoned, as **mobility** was intended to be the focus of the game.

- **Targeting:** Targeting specific body parts was **removed**.
    
- **Tokens:**
	- **Luck** was moved to a **token system**, inspired by _Daggerheart_, to avoid its over-reliance as an essential stat.
	- **Sanity** was removed. **Stamina** was also converted into **tokens**, with the class you pick determining your starting amount.
- **Traits Reworked:** Traits were redesigned as **Ultimate Moves** and **Class Abilities**.

| Class      | Class Ability | Ultimate      |
| ---------- | ------------- | ------------- |
| **Wraith** | *Ghost*       | _Flashpoint_  |
| **Mauler** | *Shockwave*   | _Unbreakable_ |
| **Psyker** | *Pulse*       | _Dominate_    |
*Avia's notes for other DMs*

> When doing tests like this. Be sure to have amazing players who aren't afraid to tell you when something isn't working. 
> 
> Just be warned. They will get good at it and they will test you just as much as you test them. 


## V2.1

As cool as the Cyberpunk setting is but what do you do when you don't want to do Cyberpunk? 

V2 was a little too heavy on the Cyberpunk elements and this led to the question being asked "How do we adapt this to other genres and stories". *Uh Oh*. This led to a bit of a rewrite.

In hindsight V2.1 was significant enough to be called V3 but at the time it didn't feel like so much of a huge step and more so just a natural progression. 

V.2.1 redid everything. 