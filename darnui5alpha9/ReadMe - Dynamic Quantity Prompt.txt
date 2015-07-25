
Name: Dynamic Quantity Prompt Beta
Author: pintocat
Version: 1.0
Date: 6/9/2011
Category: User Interface

===============
Description:
===============

Ctrl-clicking a stack of items will take one, Shift-clicking will take the whole stack. Scrollwheel works on Quantity and Sleep/Wait prompts. 

NVSE 2.4+ required.

===============
Details:
===============
*************************
Requires NVSE 2.4 BETA or higher: 
http://nvse.silverlock.org/beta/nvse_2_beta4.zip
*************************

Features:
 * Ctrl-clicking a stack of items will take one, 
 * Shift-clicking will take the whole stack. 
 * Scrollwheel works on Quantity and Sleep/Wait prompts.

Requires NVSE 2.4 beta or higher. The 1.x Series is NOT sufficient.

How does it work? 
A script runs in while in certain various Menu modes (barter, container, inventory). 
While Ctrl is held, the GameSetting iInventoryAskQuantityAt is changed to 99999 so that it will not ask, and just take one.
While Shift is held, the Gamesetting iInventoryAskQuantityAt is changed to 1 to always ask; when a Quantity prompt comes up, "R" is automatically input to accept the stack.
While in a quantity/wait mode, scrollwheel will "tap" the left or right keys.

The script increases its rate only while in relevent menu types (container, barter, inventory), and even faster in quantity/wait promps (detecting the scrollwheel can fly by fast).

When not in any of these modes, its frequency reduces to once per second. 


===============
Compatibility:
===============

No compatibility issues. 

===============
Bugs/Issues:
===============

No known issues so far, please let me know if you find any.

===============
History:
===============


1.0 6/9/2011 - Initial Release


===============
Credits:
===============

Thanks to Bethesda/Obsidian for creating Fallout NV.


===============
Tools Used:
===============

GECK
Fallout 3 ReadMe Generator

===============
License/Legal:
===============

This file is provided as is and the author holds no responsiblity for anything that may come to happen from using this file.
