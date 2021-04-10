--Simplified Combo Lock--
-Inspired by Dishonored-

Uses stock assets and a modified version of code included in "A New Job". Be aware this code replaces the existing combolock definitions - so if for some reason if your desire to use both they will need to be further modified

Instructions:

1. Extract .pk4 to the base directory of your fm, though you can burn this readme file after reading
2. If you have not done so already create a "/script" directory in your fm and create a file called "tdm_custom_scripts.script"
3. Open the file in a text editor such as notepad and add the followings lines 

#include "script/tdm_numberwheel.script"
#include "script/tdm_numberwheel_lock.script"

4. Save and close the document

The modified combo locks are still found with the stock assets under entities/movers
atdm:combination_lock
atdm:combination_lock_small