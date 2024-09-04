I tried to make a custom fork of the RPG Adventure Flavour Pack but I couldn't get it working, so here is an attempt to make the same changes using patching.

Changes have been made to 1.5 branch only.

My changes:

Removed:    
-Medieval Overhaul defs: DankPyon_Book_AncientCodex, DankPyon_Book_IntoTheRuins, DankPyon_Book_TheBeginning. (causing errors)
-Medieval Med: MO Edition eye patch if [CZK] Eye Prosthetics (Continued) is loaded.

Added:
-Compatibility for [CZK] Eye Prosthetics (Continued):
 -changed research to align with Medieval Overhaul.
 -made tribal eyepatch recipe use any leather instead of just light leather.
 -made regular eyepatch recipe use cloth or Medieval Overhaul's linen.
 -made glass eye use glass from Rebuild: Doors and Corners if mod is loaded.
        
-Compatibility for Medieval Medicines: Medieval Overhaul Edition added to cryptosleep casket patch.

-Added Tordune subspecies to Loxodon xenotype if mod is loaded. Adds a new head type and a new gene.

-Traveling Apothecary Artificer caravan added to MO Noble Houses that sells small quantities of:
 -Medieval Med: MO Edition prosthetics and medicine
 -Medieval Overhaul Drugs
 -Neutroamine
 -Occasional natural body part
 -more

-Library trader caravan now sells all Medieval Overhaul books, but will not always have them all available.

-Added no-facial-animations gene to certain xenotypes where they look better without it. I will add more as I notice them in my game.

Replaced:

-Oken's Medieval Quest Rewards with Botch Job's (uses patched base game defs).

Changed:

-Nerfed the amount of tanning liquor the Medieval Overhaul tanning rack uses.
-Broombug spawns less often in biomes.
-Made it possible to use WizardTales xenotypes, but you'd need to add a number of additional gene mods to get them to work as intended. See the loadbefore section in About.xml in Mr. Samuel Streamer's RPG Adventure Flavour Pack to see what mods you would need if you're interested.
