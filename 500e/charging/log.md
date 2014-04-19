---
Tttle: Logs for 500e
layout: default
---

# 500e Charging Log ([edit](https://github.com/pelegri/pelegri.github.com/edit/master/500e/charging/log.md))

Also see [chargers](chargers.html)

## Mar 2013
* Car was built (very early in the production)

## Aug 2013
* Car purchased at FIAT Cole, SLO

## Feb 2014

### Mon, Feb 17 - fail
* Dropped at FIAT putman, with LCS-25p and instructions on how to try to reproduce the 120V message.
* Mechanic could not reproduce.  They left the car overnight.

### Tue, Feb 18 - fine
* Talked with mechanic and told him that other 500e showed 240V not 120V.
* I went to pick up the car late afternoon.  He showed me a 2014 that also showed 120V.  We tried it 3 times with me there, 2 it showed 120V, and once it showed 240V.  I took the car home.
* I plugged in the car.  It made the usual click-and-clack, and then it charged fine.
* Took the car to pick up flier at airport
* Plugged the car overnight.  The usual click-and-clack and then some grinding noise but it was charging fine.

### Wed, Feb 19 - fail
* Car didn't charge.  It looked as if it failed pretty soon after it started charging.
* Drove the car to SFO.  Flew to LAX.  Flew back.  Charged it for about 30min on a ChargePoint w/o problems
* Plugged it in at home, went to bed.  Car failed (see Thu)

### Thu, Feb 20 - fail, fine
* Car was fully charged in the morning
* Drove to work and back; let car rest and then tried to charge
* Tried twice to charge the char but car didn't register the plug at all.  Not even a light.  Charger cycled through cycling and not cycling.  I didn't let it go into a fault in both cases.
* Opened door, then tried again to plugin, this time more forcefully.
* Car reacted to the plug and charged fine this time.

### Fri, Feb 21 - fail, fail, fine
* Back home; tried to charge and failed once.  Usual failure click-and-clack noises.  Failure light, but car/ESEV tried to charge more than once.  Failure happened within the first 3 minutes.
* Unplugged, waited for systems to quiesce, then plugged in, now more forcefully.  It is charging right now.  Charged fine.

### Sat, Feb 22 - fail, fail, fine, fine, fail, fail, fine
* Battery down to 20% after trip up the peninsula.  Tried to charge and started charging.  2 minutes after it failed after the usual click-and-clack.  It then turned itself off and, without replugging in, it started trying to charge again.  2 more minutes and it did the same.  And once more.  I finally unplugged it.
* Drove to find another HCS-40.  Old model (Yazaki connector). Charged fine twice in a row.
* Tried again at home.  Failed twice in a row.
* Tried at home while pressing the connector by hand.  It charged fine.

### Sun, Feb 23 - fail, fail, fail
* Tried to charge while holding the connector firmly; failed with the usual clacking and the car reporting it was trying to charge
* Unplugged, unwound the cable and laid up on the floor. Tried again to charge while holding the connector firmly; this time the car reported it was plugged didn't even try to charge.
* Unplugged, tried again.  Also showed not trying to charge.  It reported "press now to charge", so I did that.  Twice.  No changes.  After a bit, the car now shows a charging fault.
* I unplugged and will take it to the dealer tomorrow morning.
* Looked more carefully and I see evidence of heat damage - see [Pictures](http://www.flickr.com/photos/42919418@N03/sets/72157641437193913/).

### Sun, Feb 25
* ClipperCreek strongly recommends me not to charge the car until the problems are fixed.

### Mon, Feb 24 - 
* Took the car to the dealer.  They read the codes.  I have EVCU P1A15-00 ("Motor Electronics Coolant Pump Control Module Feedback Circuit") and OBCM P0D27-00 ("Battery Charger 1 Input Voltage Too Low").  It may be a PIM problem - or something else.
* Car charges OK with 120V charger, probably because the 120V charger only uses the AC-1 contact, not the AC-2 that is damaged, but I am not doing any more charging until I can get the car into the shop.

### Tue, Feb 25
* Awaiting for the car to get into the shop. More research seems to clearly indicate thermal damage.  Clipper Creek will send a clean unit but we need to resolve the root cause before we can try again.

### Tue, Feb 25
* ClipperCreek shipped us another HCS-40 replacement.  Great guys.

### Wed, Feb 26
* Replacement HCS-40 arrived, IIRC

### Thu, Feb 27
* 500e dropped at Putman Fiat.  I explained in detail and in person all the info I had to the mechanic.

### Fri, Feb 28
* FIAT Putman calls and indicates the problem is not present.  I talked with the mechanic directly and we clarify the problem *is* there.
* FIAT Putman calls FIAT/Chrysler HQ.  They have a lot of trouble getting responses from HQ

## March 2014

### Mar 5
* I shipped back both the LCS-25p and the old HCS-40 to ClipperCreek via UPS

### Mar 6
* ClipperCreek received the two units

### Mar Something
* ClipperCreek sent the heat-damaged plug from the latest HCS-40 to Delphi, the manufacturer.  Delphi also manufactures the inlet, and I provided the VIN number of my car to CC to pass it on to Delphi so they can do analysis on both sides at the same time.

### Mar Something
* FIAT Putman indicated they needed a new brake unit, because it was damaged. Or something like that; it was unclear
* Later on, they indicated they had to bleed and they needed a special tool.
* Later on, it was not clear if they really needed the tool or not.
* (Pending) Clarify whether the brake control unit was replaced or not - see below under Marh 20th.

### Mar 20
* I got the car back from FIAT Putman
* Car Brakes felt strange.  Very hard to modulate.  I drove it around for a bit and could not figure out if it was real or if I had forgotten how the car should feel.  I took it home for now.
* Invoice indicated the following was done to the car:
** Removed Rear Suspension Unit
** Removed High Voltage Battery
** Replace Charge Port Harness
** Installed new inlet
** Bled brake fluid
** Installed new brake fluid
** Bled
** Rebled
* Invoice lists 4 parts that were replaced:
** Wiring (8015002)
** Brake Fluid (1081006)
** Control A... (5058007)
** Module An... (8035030)
* One of the last two should be the Delphi J1772 inlet.  I don't yet know what is the other part.  It may be the brake control, or not.

### Mar 27
* I took the car to the shop to have it checked.  Mechanic indicated he had only bled the brakes, that he had not replaced the unit.  He took the car for a test drive and noticed nothing.
* I can still feel some lack of modulation in the brakes.  Will continue to track

## April 2013

### Ongoing
* Car has been charging reliably since I got it back.
* No signs of any damage to any of the connectors in the HCS-40 plug and the 500e inlet.  That problem seems to be all gone

### Apr 10ish
* I am now pumping the brakes before starting. Initial pump the brake is very tight, no slack at all.  On 3rd or 4th pump the brake feels normal.  With this protocol the brakes feel normal.
* I will try not pumping later next week and see how the brakes feel.