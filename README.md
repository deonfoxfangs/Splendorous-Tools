# Splendorous-Tools

RebornBuddy Order Bot profile to obtain Splendorous Tools for all DoH jobs in Final Fantasy XIV..

## Dependencies

**NOTE:** All of these dependencies are automatically downloaded by [UpdateBuddy](https://rebornbuddy.wiki/users/#installing-updatebuddy-and-other-add-ons) and this is the recommended way to obtain them.

- The latest version of [LLamaLibrary](https://github.com/nt153133/LlamaLibrary)
- The latest version of [Lisbeth (paid)](https://www.siune.io/)
- The latest version of [Exbuddy](https://github.com/Entrax643/ExBuddy)

## Items Needed

Some of the crafts require items that cannot be obtained by Lisbeth or require large amounts of mob grinding which should generally be avoided when botting. See below for details.

- 35 [Minium](https://na.finalfantasyxiv.com/lodestone/playguide/db/item/e75c79574e6/)\* (**Armorer** Step 4)
- 120 Kumbhira Skin (**Leatherworker** Step 4)
- 200 Almasty Fur (**Leatherworker**/**Weaver** Step 2, **Leatherworker** Step 7, **Weaver** Step 7)
- 60 Apkallu Down (**Leatherworker** Step 5)
- 240 Ophiotauros Hide (**Leatherworker** Step 5, **Weaver** Step 3)
- 100 Petalouda Scales (**Alchemist** Step 2, **Alchemist** Step 7)
- 160 Lunatender Blossom (**Alchemist** Step 3/4/6, **Weaver** Step 5)
- 180 Vampire Vine Sap (**Alchemist** Step 4, **Weaver** Step 5)
- 180 Hoptrap Leaf (**Alchemist** Step 4, **Weaver** Step 5)
- 120 Saiga Hide (**Weaver** Step 5)
- 150 Ovibos Milk (**Culinarian** Step 5)
- 60 Mousse Flesh (**Alchemist** Step 6)
- 60 Egg of Elpis (**Culinarian** step 6)
- 60 Berkanan Sap (**Alchemist** Step 7)
- 60 Amra (**Alcheist** Step 7)

_\* If you are high enough GC rank and have enough seals the profile will buy these automatically if you don't have them, but it will stop the bot with an error otherwise._

Retainer ventures are a very efficient way to get mob drop items essentially for free while the script is doing the other jobs.

## Required Settings and Warnings

- Any Splendorous Tools you already have from any step **must** be in your inventory or armory chest so the profile can see you have them and skip over them or resume from the appropriate step.
- Have another tool (i.e. Indagator's) on your character for each job you're gearing. If you don't have any it _should_ go buy a cheap one for quest turn-ins but I haven't tested this.
- Set up a Home in Lisbeth so you don't craft in the middle of a zone like a robot, and set up Smart Food/Medicine.
- For Lisbeth's suborder mode, you can choose between Quick Synth All and Quick Synth Non-Direct. Choosing All means you'll likely need multiple orders to complete steps 4 and 5, but choosing Non-Direct means you'll spend extra time HQ'ing submats. Up to you which you prefer, I think All is faster but I haven't tested.
- Have _at least_ 50 or so free inventory slots. The script should still run with at least 6, but you will be teleporting back and forth more and generally being inefficient, if not suspicious.

## How to Use

- Open "Splendorous Start.xml" in any text editor. Look for the various "ENTITY" entries that correspond to each job. Set the value for each one to be 1 if you wish to obtain that weapon, and 0 if you wish to skip it. You don't have to set it to 0 for tools you already have, it'll see those and skip automatically.
- In RebornBuddy, select "Order Bot" as your botbase, then click "Load Profile." Load "Splendorous Start.xml"
- Wait for the profile to do its thing. It's pretty self-sufficient but do make sure to check up on it regularly as with any long-term botting profile.
