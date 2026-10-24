# Combat Initiative Tracker

An attempt to create a simple D&D Initiative Tracker for use in Owlbear Rodeo VTT.

**Disclaimer:** This project is meant mostly to teach myself "vibe coding" using Claude AI, ChatGPT, and Gemini.

I know AI is a sensitive topic in the RPG community, so if you don't like it, simply don't load this tracker.

Special thanks to the devs of OBR for including an SDK and tutorial for this. I have learned a lot.

Also, special thanks to the helpful extension coders in the Discord server — especially Andrew and David and Uhlig. Special thanks to Josh - The active-token ring is adapted from Game Master's Grimoire by Joshua Hercher (MIT).

The default initiative tracker in OBR is great! I just wanted to see if I could add a few more features and controls.

# So what's different?

1. **Ability to track rounds of combat.**

2. **Ability to track Concentration and the number of turns Concentration has been used.**

3. **Ability to auto-generate initiative scores randomly when adding a combatant.** These scores can also be manually changed by clicking on them.

4. **Ability to add your character's (or monster's) initiative modifier and have the math done automatically.**

5. **When you reset the tracker for a new round of combat, it will keep all the Players and NPCs, so you won't need to re-add them each time, but it will delete the Monsters.**

   Players, Monsters, and NPCs can of course be removed manually — even during combat — by clicking on the "X" button, also deleting the token will also remove it from the tracker. (note, if the token is deleted by accident an "undo" key command (Command/Control + z) will bring the token back and will bring back the name in the tracker. This can only be done right after the token is deleted. 

6. **I have added an audible "ding"** 
**Sound**: Click the 🔔 in the tracker to hear a ding on every turn change. Sound is off by default and is set per person, so each player chooses for themselves. Click the bell once each session (your browser needs a click before it will play sound). Headphones are recommended. If you play over Zoom with speakers and unfiltered ("original") audio, the ding can echo, so leave the bell off in that case. The tracker panel must be open for the ding to play, and an iPhone's silent switch will mute it.

7. **The tracker has a limit of 29 characters for each combatant name (including spaces).** Names will break into multiple lines based on spaces. If there is a crazy-long name with no spaces, it will also break across multiple lines.

   My advice... abbreviate long names as best you can.

   Another note regarding names and this tracker:
   Combatant names are captured when a token is added to the tracker. If you rename a token after it's already in the tracker, the tracker won't automatically update — remove the combatant, rename the token, then re-add it to see the new name.

8. **Why is there a Pause button?** Pause temporarily halts turn progression without ending combat. While paused, you can click any combatant to set them as the active turn (useful for handling interruptions, reactions, or reordering on the fly) without advancing the round counter. Click **Resume** to continue combat.

9. **OBR has a nice built in feature when selecting a token and holding the Option/Alt button down,** it will create a duplicate token, and if the token has a number or letter at the end OBR will update the name with a new number/letter. Example, Goblin 1, will create a new token Goblin 2. This tracker sees that, and will automatically add the new token to the tracker along with it's own new initiative number. I know some games (or GMs) prefer to run all like monsters with the same initiative number, there is a way to do this too! Before adding any group of monsters to the initiative tracker, create however many tokens you want (example; Golbin1, Goblin2, Goblin3). Next select the first token (Goblin1), then hold "shift" button down to select the other tokens (Goblin2 and 3). With all the monsters selected now, then either 'right-click' or select the "add to initiative tracker" from the token menu, and ALL selected tokens will be added with the exact same initiative result. 

10. I've just learned that Barbarians in DnD have an option where they can roll initiative with advantage which I did not account for with this. My advice, let the tracker work as intended with the default roll, then you can simply roll another d20 in your preferred dice app (or physical die), and if it's higher than the randomly generated one of the tracker, then just click on the initiative and edit it to the higher number.

**Pro tip:** Like the original OBR tracker, if you get two initiative scores that are equal to one another, you can manually edit the numbers using a decimal point to keep a set order. For example, **19.3 will be before 19.**

Lastly: Another special thanks to my alpha/beta testers: Ken T - Top Haggis advisor and Dave M - Maple Syrup advisor also Jikar and those other guys (Dave S, David B and Sean B).

# Potential Bug Warning
This extension is still undergoing testing. 
IF you encounter a bug or glitch, often times a simple web browser refresh will work. Occasionally a "hard refresh" is needed, and will update any sort of code changes that were implemented since the last time you ran the extension in owlbear. A hard refresh is a keyboard command. On the MAC it's "Command+Shift+R" and on the PC it's "Control+Shift+R". This so far has always fixed this issue. 

# Advice
This extension runs independently and won't conflict with Owlbear's default initiative tracker, but you may want to disable one of them to avoid duplicate initiative trackers in the menu items and icon clutter.

This is a work in progress as of 10-24-26.
