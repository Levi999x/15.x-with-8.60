# 15.x-with-8.60

Hi,

I’ve downgraded the 15.x assets to 8.60 DAT and SPR using SpiderClientConverter. All original 8.60 outfits, items, and effects have been added. This gives you a complete 8.60 client that includes content from versions up to 15.x.

Every single 8.60 item was manually converted from asynchronous to synchronous. As a result, outfit idle animations now work perfectly, with no bugs or visual glitches.

Note:
We’ve also imported all outfits from version 9.83 (up to ID 537). This adds 3-frame animations and full mount support while still preserving the 8.60 look and feel. If you prefer the original 8-frame outfit animations, you can switch back to them yourself without any issues 🙂

Required OTCv8 features

    To use this properly, you must enable the following features:
    g_game.enableFeature(GameEnhancedAnimations)
    g_game.enableFeature(GameIdleAnimations)
    g_game.enableFeature(GameSpritesU32)

    Enable this only if your source supports mounts:
    g_game.enableFeature(GamePlayerMounts)
    

Important RME configuration
To avoid map-saving issues, update your RME configuration file:

otb client="8.60" version="3" id="20"

to

otb client="8.60" version="3" id="64"


The Tibia.otfi file must be placed in:
RME and OTC (860 folder)

To avoid bugs or unexpected issues, create a blank map first, then import your old map into it and save it. That’s it.

By the way, if you want to use this SPR with the CipSoft client, check out the 860-cip branch :D