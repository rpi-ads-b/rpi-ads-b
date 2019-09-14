I've heard you like planes! How about trying some plane spotting with this little spotting kit.

## Getting jiggy with dump1090

 1. Plug MicroSD card into your laptop
 1. Follow this tutorial to set it up with your wifi - https://desertbot.io/blog/headless-raspberry-pi-3-bplus-ssh-wifi-setup
   Starting from Step 3
 1. Connect antenna and put it as high as possible and preferrably outdoor.
 1. Install `apt install dump1090-mutability` package on RaspberryPi and answer `Yes` in dialog about init-d scripts.
 1. Open `http://<raspberry-pi-IP>/dump1090` and enjoy

## Explore other interesting projects

 1. Is your programming skills a bit rusty? Try to decode ADS-B packets yourselve
 2. Integrate with [FlightAware](https://uk.flightaware.com/adsb/piaware/). They will give you Enterprise account for that so you can see even more intersting stuff.
 3. Make a photo of passing aircraft! https://medium.com/@arunvenkats/automating-the-capture-of-airplane-pictures-with-raspberry-pis-ads-b-and-iot-software-39e25ddcf3ea
