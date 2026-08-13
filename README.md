# obr-initiative-tracker
An attempt to create a simple DnD Initiative Tracker for use in Owlbear Rodeo VTT. 

Disclaimer: This project is meant mostly to teach myself "vibe coding" using Claude AI, ChatGPT and also Gemini. 
I know AI is a sensitive topic in the RPG community, so if you don't like it simply don't load this Tracker.

Special thanks to the Dev's of OBR for including a SDK and tutorial for this - I have learned a lot.
Also special thanks to the helpful extension coders in the Discord server - Special thanks to Andrew. 

The default Init-tracker in OBR is great! I just wanted to see if I could add a few more features or controls. 

# So what's different?
1) Ability to track rounds of combat. 
2) Ability to track "Concentration" and rounds concentration are used. 
3) Ability to auto-generate Initiative stats randomly upon adding a name. These scores can also be manually changed by clicking on them.
4) Ability to add your character's (or Monster's) initiative modifier and have that math done automatically.
5) When you reset the tracker for a new combat, it will keep all the "players" so you won't need to re-add those each time, but it will delete the "monsters".
Players/Monsters/NPCs can of course be removed manually - even during combat. 
6) I have added an audible "ding" (with a mute button to turn it off), but because of a limitation to how OBR handles sound in browser windows, you will only hear the "ding" if you are the one who pressed the "Next Turn" button. 
7) The tracker has a limit of 30 characters for each combatant (including spaces). It will break into multiple lines based on the 'spaces' but if you type in a REALLY long name, it will extend outside of the visual box. (You can scroll to the right to read it all if need). It looks ugly, but I think I will keep this as is, as there is not a clear fix that will work for every situation. My advice... Abbreviate long names as best you can, and try to keep names (including spaces) under 15 characters in length. 

Pro tip: like the original OBR tracker, if you get two initiative scores that are equal to one another, you can manually edit the numbers using a decimal point to keep a set order (example 19.3 will be before 19). 

This is a work in progress as of 08-13-26. 
