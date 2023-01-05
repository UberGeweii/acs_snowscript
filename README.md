# acs_snowscript
Here's an (almost) dynamic, multiplayer-friendly snow script. Unlike acs_rainscript this doesn't require repeated client-side script execution.
Instead, the clients are being updated only when server variables have been changed.

This works with ZDaemon only!

# Changing variables
To change the variables use 'pukename' in console and puke the following script: "Snow_ChangeVars" (int speed, int drdistance, int minheight)

Example:
pukename "Snow_ChangeVars" 5 1500 256
