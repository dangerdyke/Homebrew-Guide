.. Homebrew Guide documentation master file, created by
   sphinx-quickstart on Sun Jan 13 23:22:33 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

After Setup (fusee-gelee)
=========================

Congratulations! By this point you have:

* Learned how to enter RCM
* Learned how to launch fusee-gelee payloads through RCM
* Learned how to perform NAND backups
* Learned how to block as much Nintendo telemetry as possible

Fixing the Archive Bit
----------------------

If you extracted the sdsetup ZIP using mac, linux, or BSD, the archive bit of the files on the SD card will not be correctly set. If you extracted the files using Windows, you do not need to do anything.

To fix the archive bit:

1. Enter RCM on your Switch
2. Push the Hekate payload to your Switch
3. Tap **'Tools > Arch Bit . RCM . Touch . Pkg1/2 > Fix Archive Bit'**

Hekate will automatically check all the files on the SD card and ensure their archive bits are set correctly.
   
Launching Atmosphere CFW
------------------------

To launch Atmosphere:

1. Enter RCM on your Switch
2. Push the Hekate payload to your Switch
3. Tap **'Launch > CFW (sysMMC)'**

Hekate will now boot Atmosphere. Note that Atmosphere CFW does not look fundamentaly different to the normal Switch operating system. You can verify you are in Atmosphere by trying to load the Homebrew Menu (see below) or checking if the system version string in System Settings contains **(AMS x.x.x)**.


Accessing the Homebrew Menu
---------------------------

Homebrew installed by placing an **NRO** file into the **/switch** folder on your SD card can be launched through the Homebrew Menu.

Access the Homebrew Menu by holding the **R** button while opening **any game or app** or by simply opening the **album**. Note that for games, you need to hold **R** *after* choosing a user (if applicable). Also note that not all Homebrew work by launching them through the Album and require you to run them through a game.

To use the Album again in CFW, hold down the **R** button while clicking on the Album icon.

........

What's Next?
------------------------

It is very highly recommended that you setup emuMMC to protect your Switch from bricking, and so you can use the latest firmware version for online play and games without losing access to CFW.

.. raw:: html

	<div class="admonition warning">
		<p class="last">To create an emuMMC, continue to <a href="/emummc/emummc">Create an emuMMC</a></p>
	</div>


.. toctree::
   :maxdepth: 2
   :caption: Contents:
