# Hackaday RSS reader for motd
## Public Domain
## Al Williams al.williams@awce.com

You need a few common pieces of software you probably already have and if you don't, get them from your package manager:

banner
curl
tput
grep
sed
bash

You almost certainly have the last 4, by the way.

Make sure 51-hackaday is executable and try running it to make sure
it all works:

   ./51-hackaday

Then move or copy it to /etc/update-motd.d (you'll need to be root)

     sudo mv 51-hackaday /etc/update-motd.d

That's it.

Here is more or less what it looks like:


-----
     #     #
     #     #    ##     ####   #    #    ##    #####     ##     #   #
     #     #   #  #   #    #  #   #    #  #   #    #   #  #     # #
     #######  #    #  #       ####    #    #  #    #  #    #     #
     #     #  ######  #       #  #    ######  #    #  ######     #
     #     #  #    #  #    #  #   #   #    #  #    #  #    #     #
     #     #  #    #   ####   #    #  #    #  #####   #    #     #
     
    		 Jaw-Dropping, IC-Free Pong on an Oscilloscope
    		 Transcranial Electrical Stimulation With Arduino, Hot Glue
    		 Hackaday Prize Entry: [Nardax] Shoots Fireballs
		 An Introduction to Differential I²C
		 Gaming Beyond Retropie
		 Linux-Fu: Applications on the Web
		 The Right Circuit Turns Doppler Module into a Sensor
-----

