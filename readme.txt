%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
	                           READ ME!
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

TEAM: COA
Submitted on December 3, 2012

@Authors: Nick Mojsej (100820777)
	  Darryl Hill (100238971)
	  Daniel H Lee (100796983)

Setting the IP Address...
  - On the server side, open the Command Prompt on Windows and type "ipconfig".
  - Note the "IPv4 Address" under "Ethernet adapter Local Area Connection #".
    It should be "134.117.28.##".
  - Add this address to "ipconfig.txt" in the Client folder!
  - Make sure you save it!

How To Compile...
  1 Open a terminal and execute "make clean".
  2 Execute "make".
  Do 1 and 2 for both Client and Server directories.

How To Run...
  - Execute "./cuCareServer"
  - Execute "./cuClientGui"

Use one of the following users to log in:
	dball 	   (ID: 1)  - as a Physician
	nickmojsej (ID: 13) - as a Physician
	noly 	            - as an Assistant Administrator
	dlee 	            - as a System Administrator
  Use one of the physician IDs whenever appropriate. i.e. making a consultation, filtering, etc.

When you filter the patient list,
   the screen will change the colour denoting that you are in the filtering mode.
   The default colour is chosen by Christine. You may change the colour as you pleased.
   To do so, on the main screen, look at the menu bar.

To configure the audit process time,
   Use the following format: "hh:mm:ss" in the 24-hour time format.
   Ex. For 7pm, use "19:00:00"

Refer to "DesignEvolution.txt" for up-to-date designed changes.
