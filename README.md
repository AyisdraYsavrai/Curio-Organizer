# Lusternia Plugins


Curio Organizer:

        MUSHclient port of Pejat's mudlet plugin. 

        See the original thread (forums.lusternia.com/discussion/2147/mudlet-curio-organizer) for details. 
        This port has the same limits has the original.


Mapping Miniwindow:
        
        Takes the IG map and moves it into a moveable miniwindow.
        Requires IG map to be on (CONFIG MAPVIEW ON) to work. 
        
        
Esteem to Essence:

        This gives you how much your figurine is worth.
        Probing the figurine will give you the worth and the bonuses being used.
        
        Use 'SESTEEM (TATTOO|REALM|POTEEN) <number>' to set these bonuses.
        
        Tattoo uses weight, realm uses essence from inlfuencing one realmmob, and poteen uses '.5'.
        You will need to reset poteen to 0 after it runs out.
        
        The system uses the formula found at: 
        
        (Flat Esteem Value) * 100 * (1+Figurine Level Bonus + Miniaturize Level Bonus) * 
        (1+Realm Size Bonus + Divine Tattoo Bonus) * (1+Poteen Offering Bonus)

        Figurine Level Bonus = .05*level (max 2.0)
        Miniaturize Level Bonus = .02*level (max .8)
        Realm Size Bonus = (Essence generated from influencing 1 realm-mob/1000)-1
        Divine Tattoo Bonus = .001* tattoo weight (max .1)
        Poteen Pot Bonus = .5 (lasts 1 hour)

        As such, SupplicantsPrayer is not part of this total. 
        It also does not take in account for any affinity penalty.
        
        
        
