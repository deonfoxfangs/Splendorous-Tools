# Splendorous-Tools

RebornBuddy Order Bot profile to obtain Splendorous Tools for all DoH jobs in Final Fantasy XIV..

## Dependencies

**NOTE:** All of these dependencies are automatically downloaded by [UpdateBuddy](https://rebornbuddy.wiki/users/#installing-updatebuddy-and-other-add-ons) and this is the recommended way to obtain them.

- The latest version of [LLamaLibrary](https://github.com/nt153133/LlamaLibrary)
- The latest version of [Lisbeth] (paid) (https://lisbeth.io/downloads/EN/Lisbeth.zip)
- The latest version of [Exbuddy](https://github.com/Entrax643/ExBuddy)

## Required Settings and Warnings

- Any Splendorous Tools you already have from any step **must** be in your inventory or armory chest so the profile can see you have them and skip over them or resume from the appropriate step. This **will** cause problems if you have them and they are not on your character!
- Have another tool (i.e. Indagator's) on your character for each job you're gearing. This is because you need to be on the job with the Splendorous Tool in your inventory/armory to turn in quests. If you don't have any it _should_ go buy a cheap one but I haven't tested this.
- Make sure your Lisbeth settings are set appropriately: set up a Home so you don't craft in the middle of a zone like a robot, and set up food/syrup (these speed up the process immensely for anything past step 3). Setting up masterpieces for white scrips is optional if for some reason you want to change them, but Lisbeth normally favors Giant Popoto Pancakes which are the fastest and easiest white scrip collectable.
- You should have _at least_ 50 or so inventory spaces available. The script should still run with at least 5 slots open, but you will be teleporting back and forth more and generally being inefficient, if not suspicious.

## How to Use

- Open "Splendorous Start.xml" in any text editor. Look for the various "ENTITY" entries that correspond to each job. Set the value for each one to be 1 if you wish to obtain that weapon, and 0 if you wish to skip it. You don't have to set it to 0 for tools you already have, it'll see those and skip automatically.
- In RebornBuddy, select "Order Bot" as your botbase, then click "Load Profile." Load "Splendorous Start.xml"
- Wait for the profile to do its thing. It's pretty self-sufficient but do make sure to check up on it regularly as with any long-term botting profile.
