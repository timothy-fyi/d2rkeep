# D2RKeep - A time-keeping utility for Diablo 2: Resurrected

Have you ever wanted to know how much time you have spent playing this addicting ARPG? Battle.net nor the game has a built-in function to track your playtime. Well, now we have a solution! 

D2RKeep has a Time Keeper with a log, as well as a Graph tool that will graph your time played over your declared amount of days.

# Requirements
- Python 3.x
- Pandas
- Matplotlib
- Psutil
- yaml

# About the config.yaml file:
```days_to_review```: The number of days you would like to graph to display and the number of days to display under the total time played in the "Stats" section

```set_timeout```: Sets the timeout to look for D2R.exe (in minutes). Once the time has passed, the program will end itself

# How To:
1. (Optional) Edit the ```config.yaml``` to your desired settings
2. Run ```d2rkeep.py```
3. Select the tool you would like to use
   * Time Keeper - use this to begin to log your playtime
   * Time Graph - use this to view your playtime

# Planned Updates
- GUI
- Compile to exe so it's easier for end users to run

# Possible Issues
- You may run into weird Python errors when running. This is because it's quite possible I have not caught all the possible errors that can arise
