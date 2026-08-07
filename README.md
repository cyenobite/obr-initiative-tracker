# obr-initiative-tracker
An attempt to create a simple DnD Initiative Tracker for use in Owlbear Rodeo VTT. 

Disclaimer: This project is meant mostly to teach myself "vibe coding" using Claude AI, ChatGPT and also Gemini. 
I know AI is a sensitive topic in the RPG community, so if you don't like it simply don't load this Tracker.

Special thanks to the Dev's of OBR for including a SDK and tutorial for this - I have learned a lot.
Also special thanks to the helpful extension coders in the Discord server. 

The default Init-tracker in OBR is great! I just wanted to see if I could add a few more details or controls. 

# So what's different?
1) Ability to track rounds of combat. 
2) Ability to track "Concentration" and rounds concentration is used. 
3) Ability to auto-generate Initiative stats randomly upon adding a name. 
4) Ability to add your character's (or Monster's) initiative modifier and have that math done automatically.
5) When you reset the tracker for a new combat, it will keep all the "players" so you won't need to re-add those each time, but it will delete the "monsters".
Players can of course be removed manually. 
6) Currently testing the ability to add a simple "ding" to indicate a turn is over - with the option to turn this off if it becomes annoying.
I'm told that adding this audio feature is a problem as owlbear has certain limitations with shared audio. So for now, you will only hear the "ding" if you're the person who clicks on the "next" button. It kinda defeats the purpose I had intended, but I do like the audible feedback so I'm keeping it in. Subject to change if I change my mind, or if I can figure out the code to make it work. 

Pro tip: like the original OBR tracker, if you get two initiative scores that are equal to one another, you can manually edit the numbers using a decimal point to keep a set order (example 19.3 will be before 19). 

This is a work in progress as of 08-07-26. 
