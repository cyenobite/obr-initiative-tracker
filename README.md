# obr-initiative-tracker

An attempt to create a simple D&D Initiative Tracker for use in Owlbear Rodeo VTT.

**Disclaimer:** This project is meant mostly to teach myself "vibe coding" using Claude AI, ChatGPT, and Gemini.

I know AI is a sensitive topic in the RPG community, so if you don't like it, simply don't load this tracker.

Special thanks to the devs of OBR for including an SDK and tutorial for this. I have learned a lot.

Also, special thanks to the helpful extension coders in the Discord server — especially Andrew and David.

The default initiative tracker in OBR is great! I just wanted to see if I could add a few more features and controls.

# So what's different?

1. **Ability to track rounds of combat.**

2. **Ability to track Concentration and the number of turns Concentration has been used.**

3. **Ability to auto-generate initiative scores randomly when adding a combatant.** These scores can also be manually changed by clicking on them.

4. **Ability to add your character's (or monster's) initiative modifier and have the math done automatically.**

5. **When you reset the tracker for a new round of combat, it will keep all the Players and NPCs, so you won't need to re-add them each time, but it will delete the Monsters.**

   Players, Monsters, and NPCs can of course be removed manually — even during combat — by clicking on the "X" button.

6. **I have added an audible "ding" (with a mute button to turn it off),** but because of a limitation to how OBR handles sound in browser windows, you will only hear the "ding" if you are the one who presses the "Next Turn" button.

7. **The tracker has a limit of 29 characters for each combatant name (including spaces).** Names will break into multiple lines based on spaces. If there is a crazy-long name with no spaces, it will also break across multiple lines.

   My advice... abbreviate long names as best you can.

8. **Why is there a Pause button?** Pause temporarily halts turn progression without ending combat. While paused, you can click any combatant to set them as the active turn (useful for handling interruptions, reactions, or reordering on the fly) without advancing the round counter. Click **Resume** to continue combat.

**Pro tip:** Like the original OBR tracker, if you get two initiative scores that are equal to one another, you can manually edit the numbers using a decimal point to keep a set order. For example, **19.3 will be before 19.**

This is a work in progress as of 08-27-26.
