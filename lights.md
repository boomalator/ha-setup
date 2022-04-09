# Lights
Most of my HA is about lighting. I like light; I used to design theatrical lighting and I believe that architecture and home decor isn't complete if lighting hasn't been considered. I also belive that a home's basic lighting has to work with or without the controllers. A switch needs to turn a light on or off. 

## Main Lights - Lutron

AFter having many differnt odds-and-ends in the old place, I standardized on Lutron's Caseta for every last wired switch in the house. https://www.casetawireless.com/us/en. New switches and dimmers were installed before the interace hub was ready to move, so for several weeks, the automation consited of the linked remotes. Adding the hub and app adds reasonable programability even withtout the HA server. 

I've used Lutron for a long time. In fact, I'm abandoning sevral bits of RadioRA (the original, no 2 nor 3) in the old house, including a [Chronos controller](https://www.lutron.com/TechnicalDocumentLibrary/044037b.pdf) that in it's day was about a grand.

If I were to do it yet again, I probably would use RadioRA3 instead of Caseta. There's a few more options in the system, and it's not significantly more, and it's still easy to retrofit. It helps that I have buying access at Electrical distributors, and although I'm not a licensed electrician, I do hold a Qualified Electrical Worker permit. (Caseta and RadioRa/RA2/RA3 all use Lutron's ClearConnect, but aren't able to play with each other.)

## Effect Lights - Wiz

I hummed and hawwed over Wiz vs Hue for colours and effects, including a track light that lets me look reasonably good on camera for web casting and Zoom/Teams. It came down to me just not seeing the value in paying 3 to 4 times as much per bulb for Hue. Hue uses Zigbee and Wiz uses direct Wifi. Most of my Wiz lights are GU10 bulbs, although there are a couple of LED strips.

Both Hue and Wiz are supported by my automation software, [Home Assistant](https://www.home-assistant.io/).
