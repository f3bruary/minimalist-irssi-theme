# minimalist-irssi-theme
A theme for irssi, based on 'weed' by ronilaukkarinen with some personal
customizations.

Requires latest irssi (0.8.17).

When started you must /reload. This is necessary each time you restart irssi to
have alligned nicknames. No idea why..

Instructions:

0. Back up your shit.
1. Place all files in ~/.irssi
2. Start irssi and apply theme: '/set theme weed'
3. Add your servers/channels,hilights,username/realname/etc
4. Nicklist: I personally use tmux but in case you use screen you might want to
   configure it differently. Follow instructions at
   http://wouter.coekaerts.be/irssi/nicklist
5. For more info about nick coloring (neatcolors), you can open the plugin
   file, there should be some intructions in them.
6. '/save' & '/layout save', the latter so irssi remembers the position of the
   channel order.
7. That's it. Just don't forget to /reload when you restart irssi.
