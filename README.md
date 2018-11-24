# nexus-tradeskills
This is an ongoing package project that will give aliases and triggers for all the tradeskills in Achaea

Quick Note: It requires the use of the severside queue to use effectively. For more information about the serverside queue, look at HELP 	QUEUE while in game

Build Notes:
	
(8/5/2018)

	What some of the stuff does.

	For inkmilling:
	
			Aliases:
	
		(CASE SENSITIVE) mill(color) <numofbatches> <inkperbatch>: allows you to mill multiple batches and also customize how 
		many inks you can  make. EX. millgreen 20 5 will mill 20 batches of 5 inks per batch. No need to take stuff fromm rift
		as it does this for you.
    	
       
       		millstop: stops the inkmilling so that you do not have to stop all your scripts.
        
        	blueswitch: switches the default blue reagent between lumic and inkbladder
        
        	redswitch: switches the default red reagent between redclay and red chitin
        
        	startup: runs the onLoad function so you do not have to restart to set up
        

   		Triggers:
       
       		A trigger to take ink from mill and puts it into the rift automatically
            

	For Gathering:
	
		Aliases:
    	
		g <thing>: Allows you to just gather the thing you want without having to type in gather <thing>. Also has support for
		butchering by letting you type g <reagentname> (Ex. "g scales" will "butcher fish for scales" while "g inkbladder" will
		butcher
		squid.
       
       		refine <times> <thing>: Allows you to refine repeatedly how ever many times you need to. Need 100 sugar but do not want
		to press
       		enter 100 times? This alias is for you. Also puts the refined ingredient in the rift so you do not lose it.
        
        	refinestop: Someone walk in and you need to move? Your city is being raided and you need to move? Whatever the reason,
		if you
		need to stop refining before the number of times you planned on, just do stoprefine and you will stop.


   		Triggers:
     	
		A trigger that, no matter what you gather, it rifts what ever it is.
	
        	A trigger to rift stuff after you butcher
	
        	A trigger to empty your hands and wield the cleaver if you try to butcher without it
        
		A trigger that notifies you when you get a gold flake and makes you make a happygasp (Just a fun thing, can disable this
		or change the emote, has no effect on anything.)
        
(8/8/2018)
   	
    	For Gathering:
    		Aliases:
        
       	 	dg <thing1> <thing2>: This alias allows you to gather/butcher two items at once. This is useful for when you want to
		gather both lumic moss and diamond dust while in an underground room but do not want to retype it for both.
    
    
    	For Furnishing:
    		Triggers:
        
        	Added echoes for a few samples that you can run across
        
        
(8/10/2018)
     
     For Inkmilling:
     	Found out that the inkmilling aliases messed up and made a work around so it actually works now.

(11/23/2018)

	I had honestly forgot I had made this. Been busy with college and stuff so haven't really even been in realms. I am not sure if
	I made any improvements but incase I have, I uploaded what I have so far.

Eventually, the plan is to have this package have support for all the tradeskills but as I only have Gathering and Inkmilling, that will
take a little time. I am hoping that I can find people to help me improve and build it so that it includes all the tradeskills

