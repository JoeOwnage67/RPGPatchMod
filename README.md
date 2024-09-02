I tried to make a custom fork of the RPG Adventure Flavour Pack but I couldn't get it working, so here is an attempt to make the same changes using patching.

Changes have been made to 1.5 branch only.

My changes:

Removed:

    Balrog xenotype.
    Medieval Overhaul defs: DankPyon_Book_AncientCodex, DankPyon_Book_IntoTheRuins, DankPyon_Book_TheBeginning.
    Medieval Med: MO Edition eye patch if [CZK] Eye Prosthetics (Continued) is loaded.

Added:

    compatibility for [CZK] Eye Prosthetics (Continued):
        changed research to align with Medieval Overhaul.
        made tribal eyepatch recipe use any leather instead of just light leather.
        made regular eyepatch recipe use cloth or linen.
        made glass eye use glass from Rebuild: Doors and Corners if mod is loaded.

    compatibility for Medieval Medicines: Medieval Overhaul Edition added to cryptosleep casket patch.

    "Tordune Head" textures and defs (Loxodon with an eyepatch) to Loxodon xenotype if mod is loaded.

    Traveling Apothecary Artificer caravan added to MO Noble Houses that sells small quantities of:
        Medieval Med: MO Edition prosthetics and medicine
        Medieval Overhaul Drugs
        Neutroamine
        Occasional natural body part
        more

    Library trader caravan now sells all Medieval Overhaul books, but will not always have them all available.

Replaced:

    Oken's Medieval Quest Rewards with Botch Job's (USES PATCHED BASE GAME DEFS).

Changed:

    Nerfed the amount of tanning liquor the Medieval Overhaul tanning rack uses.
    Broombug spawns less often in biomes.
