# Lusternia Plugins


Curio Utility:
        
        Composed of the following:
                CurioOrganizer
                CurioRubber
		***I'm not responsible for any misrubs***
        
       CurioOrganaizer:
                Displays your curios pieces in a nice table.
                If you have missing pieces, a missing pieces button will show
                for you to click. Each double-digit number will also show you
                what piece that is if you hover over it (clicking it will do
                a CURIOS ALL on that piece...)
                If you have all the pieces, a BuildMe button will show that
                will build the curio in question.
                NOTE: FOR THIS TO WORK, YOU NEED THE masterCurios.lua FILE.
                PUT THIS FILE WHEREVER YOU PUT THE PLUGIN.

        CurioRubber:
                Using CRUB [SINGLE] <pattern> will show a list of curios matching
                via IG CURIOS ALL [<pattern>], and give a button to click to 
                start the rubbing. If you use the SINGLE word, the rubber will
                only rub doubles of your <pattern>
                **use rubber at own risk.**
                
        CurioInfo
        	Using CINFO <curio|collection> will display the pieces in curio, or show
        	possible curios if partial name is given. If given a collection, the curios
        	in that collection will be displayed. All curios using this command are
        	clickable.
        

Mapping Miniwindow:
        
        Takes the IG map and moves it into a moveable miniwindow.
        Requires IG map to be on (CONFIG MAPVIEW ON) to work. 
        
        
Esteem to Essence:

        This gives you how much your figurine is worth.
        Probing the figurine will give you the worth and the bonuses being used.
        
        Use 'SESTEEM (TATTOO|REALM|POTEEN) <number>' to set these bonuses.
        
        Tattoo uses weight, realm uses essence from inlfuencing one realmmob, 
        and poteen uses '.5'. You will need to reset poteen to 0 after it runs out.
        
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
        
        
        
