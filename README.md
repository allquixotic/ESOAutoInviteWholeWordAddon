Overview

This is an updated (2019) version of AutoInvite that supports "whole word" matching if you set the input string to begin with an "!".

For example, if you set the input to "!d", it will send an invite if someone says "I would like a DDD!!" but it won't match if someone says "hello dear".

To literally match (only) the string "!d", please set your input string to "\!d" (no quotes).

This version is based on AutoInvite 2.5.0 and is otherwise equivalent to it besides the new whole word matching feature.

Simple auto-invite addon - intended for use in Cyrodiil to quickly setup a group invite string without diving into menus. Since expanded to be a part of the group tab, but original slash commands still exist for quickly turning on and off.

Features

Slash commands to quickly enable or disable inviting, and regrouping
Stop sending invites when reach group limit
Change the group limit (when to stop invites)
Options panel as separate tab in group menu
Settings (except for actually running) are saved between loads
Option to only invite players in Cyrodiil (for guild invites)
Option to restart invite after someone leaves group
Option to auto-kick members after set amount of time offline
Button to re-form the group
Keybindings to reinvite or regroup the group


Localization
Translations have been provided by the following people

French - Provision
German - silentgecko
Japanese - Lionas
Russian - ForgottenLight


Usage
Open the group menu and there is a tab (far right) for AutoInvite settings. Set the invite string and any other settings then check enable. Now anyone who types that message (exactly) in chat will have an invite sent.

Alternatively you can use the slash commands to quickly start/stop and for when you want to start/stop without opening any menus.

Known Issues/Limitations

The regroup function doesn't work well through group leader bug.
Queue display is not in-order for position in queue.
No right click on the mini-group (for kick, travel to, etc).
Sometimes the mini-group list on the AutoInvite tab doesn't update properly. There is a button included to force an update if that's the case.


Slash commands
These are for very quick access or for debugging purposes.

/ai - Turn off AutoInvite. Emergency stop button of sorts
/ai foo - Set string to 'foo' and start inviting. If you put a ! at the beginning of the string, match any whole word containing that string.
/aidebug - Turn on debug logging to chat window. Note: this can be rather verbose.


Example
You're a raid leader and have some spots to fill.

Type /ai xx in chat message to start listening for 'xx' message in chat
Advertise yourself in chat ("Type xx for Bleakers raid group")
Sit back and let the addon manage sending invites