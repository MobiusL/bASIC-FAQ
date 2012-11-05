bASIC-FAQ
=========

FAQ for the bASIC sold by BTCFPGA / BitcoinASIC

The primary source is [this thread on
bitcointalk.org](https://bitcointalk.org/index.php?topic=79637). Later pages are more
relevant.

General Comments and Disclaimer
-------------------------------

Tom (aka cablepair) has shown to be conservative in estimations on both the hashing speed
and power requirements of his products. _However_, the estimates may be higher (or lower)
if custom firmware, or overclocking is employed.

This information is provided with no guarantee. Reader discretion is advised. 

Recommended Reading
-------------------

Some basic understanding of electrical principles is recommended. This includes knowing
the relationship between volts, amperes and watts. Wikipedia can help you if you need a
basic intro.

See:

* [Ampere or Amp](http://en.wikipedia.org/wiki/Ampere)
* [Volt](http://en.wikipedia.org/wiki/Volts)
* [Watt](http://en.wikipedia.org/wiki/Watt)

Note that _W = V dot A_; dot here is referring to the [Dot
Product](http://en.wikipedia.org/wiki/Dot_product). Since there is no imaginary / vector
component it can be treated as regular multiplication.

Contacting Tom
--------------

Please read through this FAQ and as much of the
[thread](https://bitcointalk.org/index.php?topic=79637) as possible before contacting him.
Many questions have been answered here and Tom is a busy man. (Start from the end to get
the most recent posts)

If you require to contact Tom the two best methods are:

* Email: [thomas@thomasvanriper.com](mailto:thomas@thomasvanriper.com)
* Telephone: (315) 514-0269

Tom will reply to
[all](https://bitcointalk.org/index.php?topic=79637.msg1315070#msg1315070) emails he
receives; however, he may be delayed by a few days. If an urgent response is required
please consider calling him.

If you are outside the US and wish to call, please consider Google Talk or Skype as cheap
alternatives to calling from a landline.

Tom has previously stated that PM-ing him is not the fastes way to get a response. (source
pls)

Tom is also often available on IRC in both #bitcoin and #btcfpga on Freenode.

Shipping Dates
--------------

Currently Tom is on schedule to ship around the first week of December. (source me)

My personal understanding is that the first batch will all be manufactured / assembled
simultaneously and then all shipped simultaneously.
This is pure speculation and assumption on my part. - XertroV (should be confirmed denied,
more info needed)

Shipping Methods
----------------

Standard is USPS, though an upgrade to DHL is available.

Persons inside the United States won't notice the upgrade much; however, those outside the
US should notice a large improvement in shipping time. (source me)

Power Requirements
------------------

Current power estimates are [*at
most*](https://bitcointalk.org/index.php?topic=79637.msg1315070#msg1315070) 125 watts for
a 54 Ghash/s bASIC and approximately half for a 27 Ghash/s model.

A far more likely figure is under 100 watts. This equates to approximately 1.85 w/GH.

Power Connectors
----------------

Both bASIC models will have a 4 pin molex connector and a barrel connector (aka female DC
coaxial connector).
[(Source)](https://bitcointalk.org/index.php?topic=79637.msg1315070#msg1315070)

The barrel connector is
[thought](https://bitcointalk.org/index.php?topic=79637.msg1314859#msg1314859) to be a
centre +'ve 2.1 mmID 5.5 mmOD type. (ID = inside diameter, OD = outside diameter).

[Images](https://bitcointalk.org/index.php?topic=79637.msg1314785#msg1314785).

Power Supplies
--------------

A bASIC [*will not*](https://bitcointalk.org/index.php?topic=79637.msg1315070#msg1315070)
ship with any power supply.

However, you can buy a PSU that is compatible from Tom's store
[here](https://www.bitcoinasic.net/index.php?route=product/product&product_id=54).
This PSU will be able to power up to 10 bASIC mining units. If you are planning on running
less than 10 a smaller PSU (in terms of wattage) might be more appropriate.

Please exercise due diligence with regards to PSUs. Having $10,000 worth of equipment on
one PSU provides no hedging. If this concerns you, please consider using multiple PSUs
(possibly with a lower maximum wattage each) in order to spread risk. This is _especially_
true with lower quality PSUs.

Please be sure to use _quality_ PSUs and be sure not to stress them too hard to give
yourself the lowest risk factor you can. It is reccomended you keep the wattage below 80%
or so of the maximum rating on a PSU. This is more important than a PSU for gaming or a
normal system as this PSU will be running *constantly*.

What Should I Know When Purchasing a PSU
--------------------------------------

(This section is possibly inaccurate - I'm not that experienced with the matter. If
someone could read over this and confirm it's not inaccurate I would be appreciative)

I believe you should be looking at the number of 12v rails available and the amperage
supplied to each, since that is what will be powering your bASIC.

At 12 V one 54 Gh/s model will require 8.4 amps. 

The SeaSonic 1000 W PSU sold by Tom has a single rail at 12 V able to provide 83 A and so
is able to provided 12 V * 83 A = ~1000 W.

I have personally bought
[this](https://www.pccasegear.com/index.php?main_page=product_info&products_id=14393). It
has one 12 V rail at 40 A; so 480 W total. This would allow me to safely power up to four
54 Gh/s bASICs and perhaps one 27 Gh/s bASIC in addition to the previous four.

If you were to buy a PSU with three 12V rails that each provided 13 A you would be able to
power just *three* bASICs (54 Gh/s model). While the total (3 \* 12 \* 13 = 468 W) would
normally be able to power at least four 54 Gh/s bASICs, since you are restricted by each
rail, in reality you can only power (3 \* floor(12 \* 13 / 100) = 3) three bASICs. 

[_Note:_ floor(12 \* 13 / 100) gives the number of bASICs you can run from each rail]

### Formula:

I believe the general formula would be:

Num-rails \* floor(rail-volts \* rail-amps / 100 Watts) = Num-bASICs 

What is Required when Purchasing a Wall Wart with Barrel Connector
------------------------------------------------------------------




Is Tom's Shop Safe?
-------------------

Tom has stated they have a complete security system and they are located in close
proximity to a police station. In addition, when ASICs are being assembled there will be a
staff member present around the clock.
[(Source)](https://bitcointalk.org/index.php?topic=79637.msg1313840#msg1313840)









