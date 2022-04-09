# Lights
Most of my HA is about lighting. I like light; I used to design theatrical lighting and I believe that architecture and home decor isn't complete if lighting hasn't been considered. I also belive that a home's basic lighting has to work with or without the controllers. A switch needs to turn a light on or off. 

## Main Lights - Lutron

AFter having many differnt odds-and-ends in the old place, I standardized on Lutron's Caseta for every last wired switch in the house. https://www.casetawireless.com/us/en. New switches and dimmers were installed before the interace hub was ready to move, so for several weeks, the automation consited of the linked remotes. Adding the hub and app adds reasonable programability even withtout the HA server. 

I've used Lutron for a long time. In fact, I'm abandoning sevral bits of RadioRA (the original, no 2 nor 3) in the old house, including a [Chronos controller](https://www.lutron.com/TechnicalDocumentLibrary/044037b.pdf) that in it's day was about a grand.

If I were to do it yet again, I probably would use RadioRA3 instead of Caseta. There's a few more options in the system, and it's not significantly more, and it's still easy to retrofit. It helps that I have buying access at Electrical distributors, and although I'm not a licensed electrician, I do hold a Qualified Electrical Worker permit. (Caseta and RadioRa/RA2/RA3 all use Lutron's ClearConnect, but aren't able to play with each other.)

## Bulbs

The trick with in-wall dimmers is to use compatible bulbs. Nothing beats the warmth and smoothness of incandescent, but they run hotter, use more energy and are harder to find. I relied heavily on [Lutron's compatibility tool](https://www.lutron.com/en-US/pages/ledcompatibilitytool/compatibility.aspx) and only buy 5-star tested bulbs... or I buy one of something else, test it, and return it. I **loathe** flicker in my lights. So far, best results with:
+ GE, Classic or Relax
+ Phillips (some models)
+ Sylvania (some models)

Surprisingly, some Illume slimline retrofitabble pot lights that I had kicking around work awesome. These are nice little lights, especially at $15 CAD each! [Home Depot](https://www.homedepot.ca/product/illume-essential-4-inch-recessed-round-led-panel-12-pack-energy-star-/1001062803)

## Effect Lights - Wiz

I hummed and hawwed over Wiz vs Hue for colours and effects, including a track light that lets me look reasonably good on camera for web casting and Zoom/Teams. It came down to me just not seeing the value in paying 3 to 4 times as much per bulb for Hue. Hue uses Zigbee and Wiz uses direct Wifi. Most of my Wiz lights are GU10 bulbs, with a couple of LED strips.

Both Hue and Wiz are supported by my automation software, [Home Assistant](https://www.home-assistant.io/).

## Odds and Sods
Of course, I'm a hobbyist. So there's always a few oddballs kicking around. These are for testing or playing or "old stock".

+ [Globe RGB and Tunable White bulbs](https://globe-electric.com/en/product/globe-electric-wi-fi-smart-60w-equivalent-multicolor-changing-rgb-tunable-white-dimmable-frosted-led-light-bulb-no-hub-required-a19-e26-base-2-pack34207/)
  Flashed with Tasmota.
  
  I like the products, but I've had several of the RGB lights have one of the colours (usually blue) go bad. The company has been very responsive about replacements. They are inexpensive and carried at Costco, Lowe's, and even Radio Shack/The Source. Look for sales. Caution: Not all models are flashable. You may be stuck with Tuya-derived apps.
  
+ [Ikea Tradfri](https://www.ikea.com/ca/en/cat/smart-lighting-36812/)

  Reasonably cheap, available locally. Mostly have these to test Ikea's zigbee controllers and pairing.
