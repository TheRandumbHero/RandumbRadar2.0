<p align="center">
<img src="/images/RandumbRadar2_Logo.png" alt="RR_Logo" style="width:200px;"/>


Theres a few of these online now and I wanted to add my own flair to my own so I set about designing my own code (with the help of ChatGPT) and my own 3D printed case. Whilst this is not a fork or remix it is heavily inspired by @github/arvis91/
The idea was to see whether I could create my own Desktop Radar software with a 3D printed case that only uses friction fit for all the componants and if possible to make it plug and play with no requirement for soldering if you weren't confident. 

Design wise the screen mount is designed around the one I ordered which I have listed below but I have some more coming from AliExpress (to reduce cost) to see if these also fit.

So without further ado please see below!

## Parts List

- 3D Printed Case - [RandumbPrints - Makerworld.com](https://makerworld.com/en/@RandumbPrints)
- Cheap Yellow Display (CYD) - [Amazon UK](https://www.amazon.co.uk/dp/B0CQX9Q68P?ref=ppx_yo2ov_dt_b_fed_asin_title) - These can be got cheaper on AliExpress I just needed one quickly for the build.

# Connecting & Building:

1. Print the case whilst waiting for the parts to arrive.
2. Place the CYD into the mount to the part called "Cradle"
3. Slide 'Cradle' in the 'Main Body'
4. Place 'Bezel' into 'Outer Shell' This is a tight fit and should properly click.
5. The flat uprights of the 'Main Body' should be used to guide the 'Outer Shell' its been design this way to keep as little a gap as possible from the screenwithout causing accidental damage


# Webflasher

> [!CAUTION]
> By Flashing your ESP32 it will wipe any other app you currently have running - I would advice unplugging any other ESP's you may have plugged in just incase you select the wrong COM Port.

Connect the ESP32 to your PC with a USB-C cable and head to [LINK](https://therandumbhero.github.io/RandumbRadar2.0/) this will open up a webflasher - Flash your ESP32 and wait for it to complete.

# Initial Setup

Once the ESP32 boots up for the first time, it will create a Wifi Access Point called RandumbRadar, connect to this on your phone/laptop. Head to 192.168.77.1 on your browser and enter your home WIFI details. You'll get a confirmation page and the device will reboot.

<p align="center">
  <a href="/images/Initial_Setup.png">
    <img src="/images/Initial_Setup.png" width="180" alt="Initial">
  </a>

# First Setup

The Screen should now be displaying a local IP address, so back on your home WIFI you should be able to go to that address and start the first set up. The First thing you need to do is go to [opensky](https://opensky-network.org/) and create an account, once done, on your account page you'll see an option to create an API key. Click this and it will download a file to your PC, there you'll find the ID and Secret. Now head to that IP address you seen on your Radar Screen and click settings. Paste your Client ID and Client Secret into the corresponding boxes (without the speech marks or any other formatting) and click Save. The system will take a few minutes and then start the next scan. The long/lat defaults are Heathrow Airport at a 200km range so expect to see alot of dots first time round!

<p align="center">
  <a href="https://github.com/TheRandumbHero/RandumbRadarOS/blob/main/images/OpenSky_Options.png">
    <img src="/images/OpenSky_Options.png" width="180" alt="OpenSky">
  </a>

  <a href="/images/OpenSky_Options.png">
    <img src="/images/OpenSky_Creds.png" width="180" alt="Creds">
  </a>

  <a href="/images/OpenSky_Options.png">
    <img src="/images/Setting_OpenSky.png" width="180" alt="Settings">
  </a>
</p>

# Customisation

Now is the fun stuff. Head back to the Dashboard, Click Customisations and go crazy! Update your Lon/Lat and range to suit and I've included a couple of customisations options within the app. I hope to add more in the future.

<p align="center">
  <a href="/images/Customisation.png">
    <img src="/images/Customisation.png" width="180" alt="Initial">
  </a>
   
  </a>
</p>
