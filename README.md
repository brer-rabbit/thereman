# Annoying Thereman - light sensitive buzzing companion

This repo contains the design and build info for Thereman, a light sensitive buzzing companion.  Very useful for a variety of buzzing sounds.

The Thereman contains two LDRs (Light Dependent Resistors) and a dual 555 timer pretty much like an Atari Punk Console.  The LDRs control pitch and pulse width.

# Build

The kit contains a PCB with the dual 555 timer (a 556), the LDRs, eye LEDs, and some passive components on the front.  The back requires soldering a couple components.  I'm assuming you're using regular solder wire.

![Components shown with front and back of Thereman](build/components.jpg)

## Prep

Tin the pads first.  Shown below, tin all the pads marked in green; the pads in red do no need soldering.

![Tin pads shown in green](build/tinning.jpg)

Optionally, tin the yellow pads: there are not electrically connected and you can solder a wire between them to create a loop to hang the Thereman.

Just a touch of solder for tinning and you don't want solder poking up.  Keep it flat and level so components can attach.

![This is not even, keep it flat](build/tinning_keep_it_level.jpg)

## Switch

The switch has a few small pads; it's easiest to do this first before the other components clutter the space.  There on/off switch sticks out the side of the Thereman.

Once done congrats!  You've soldered the smallest component of the project.

## Piezo Buzzer

The piezo buzzer is the black square that is responsible for the great sound of the Thereman.  It goes in the very middle; it's not polarized and can be installed in either direction.

## Battery Retainers

Install the top battery retainer.  Two of the three pads keep the battery retainer in place and make an electrical connection.  The middle pad is not soldered.  Of the two pads to solder, the pad that is at the top may be easiest to do first.  Then the pad right next to the piezo.

![Correct orientation of battery retainers](build/retainers_correct.jpg)


The bottom two battery retainers need to be oriented so one can insert batteries.

![Nope, flip those battery retainers around](build/retainers_wrong.jpg)

Also, keep the battery retainers slightly apart so they do not touch.

![Keep the retainers a bit apart, this is too close](build/retainers_too_close.jpg)
