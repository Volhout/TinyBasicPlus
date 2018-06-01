# TinyBasicPlus
A tinybasic plus interpreter for Arduino (UNO/NANO) boards, based on BleuLlama's earlier work

Optimisations to keep as much as possible free RAM for programs while fixing bugs and adding features

Added features
- abbreviation of keywords (saves memory). Example "N." instead of "NEXT"
- added SERVO command to control 2 servo's (UNO/NANO) or 3 servo's (MEGA) using HW timers
- added HELP (shows build in commandset) and VARS (shows all 26 variables and value)
- added MAX and MIN commands
- added MILS command showing miliseconds passed since previous MILS command.

Bug fixes
- changed BELL to '\a'
- fixed bug in DELAY, to allow multiple statements on one line
- fixed backspace issue, for better correction of mistakes
- added several fixes in input statemend issued by Brian O'Dell
