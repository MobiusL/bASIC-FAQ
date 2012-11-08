Unofficial bASIC-FAQ
====================

An unofficial FAQ for the bASIC sold by BTCFPGA / BitcoinASIC

The primary source is [this thread on
bitcointalk.org](https://bitcointalk.org/index.php?topic=79637) and the [BTCFPGA 
forums](https://www.btcfpga.com/forum/). Later pages are more relevant.

Other sources include the [BTCFPGA / BitcoinASIC
Forum](https://www.btcfpga.com/forum/index.php), the
[BitcoinASIC](https://www.bitcoinasic.net) site, and other non-bitcoin related sources.

Contents
========

* [General Comments and Disclaimer](#general-comments-and-disclaimer)
* [Recommended Reading](#recommended-reading)
* [Contacting Tom](#contacting-tom)
* [Shipping and Assembly](#shipping-and-assembly)
    * [Shipping Dates](#shipping-dates)
    * [Shipping Methods](#shipping-methods)
    * [Fabrication](#fabrication)
    * [Assembly](#assembly)
* [Power Requirements](#power-requirements)
* [Power Supplies and Connectors](#power-supplies-and-connectors)
    * [Power Supplies](#power-supplies)
    * [Power Connectors](#power-connectors)
    * [What Should I Know When Purchasing a PSU](#what-should-i-know-when-purchasing-a-psu)
        * [Formula](#formula)
    * [What is Required when Purchasing a Wall Wart](#what-is-required-when-purchasing-a-wall-wart)
* [bASIC details](#basic-details)
    * [Production details](#production-details)
    * [bASIC Physical Dimensions](#basic-physical-dimensions)
    * [SHA256 Core](#sha256-core)
    * [Compatible Miners](#compatible-miners)
* [Will I need to pay Import Duties if I'm in the 
EU](#will-i-need-to-pay-import-duties-if-im-in-the-eu)
* [Do bASICs need to be okay'd by the FCC](#do-basics-need-to-be-okayd-by-the-fcc)
* [Tom's Shop](#toms-shop)
    * [Images](#images)
    * [Is It Safe?](#is-it-safe)
* [Contributors](#contributors)


General Comments and Disclaimer
-------------------------------

Tom (aka cablepair) has shown to be conservative in estimations on both the hashing speed
and power requirements of his products. _However_, the estimates may be higher (or lower)
if custom firmware, or overclocking is employed.

Units used are Volts (V), Amperes (A), Watts (W), Joules (J) and Gigahashes per second (Ghash/s or
Gh/s). This document also uses combinations of the above. It should be noted that W / Gh/s are
equivalent to J / Gh. They may be used interchangeably.

**This is an unofficial FAQ**. I (XertroV) and other contributors claim no credibility. 
Please use your own due diligence, or that of those whom you trust, when reading the
content of this FAQ. Furthermore, this information is provided with no guarantee. Reader
discretion is advised.

If you're aware of an error on this page please email me at
[xertrov@gmail.com](mailto:xertrov@gmail.com)

Recommended Reading
-------------------

Some basic understanding of electrical principles is recommended. This includes knowing
the relationship between volts, amperes and watts. Wikipedia can help you if you need a
basic intro.

See:

* [Ampere or Amp](http://en.wikipedia.org/wiki/Ampere)
* [Volt](http://en.wikipedia.org/wiki/Volts)
* [Watt](http://en.wikipedia.org/wiki/Watt)

Note that **W = V dot A**; dot here is referring to the [Dot
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

Tom has previously stated that PM-ing him is not the fastes way to get a response; it is
last on his list of priorities. 
[(Source)](https://bitcointalk.org/index.php?topic=79637.msg1308426#msg1308426)

Tom is also often available on IRC in both #bitcoin and #btcfpga on Freenode.

Shipping and assembly
---------------------

### Shipping Dates

Currently Tom is [on
schedule](https://bitcointalk.org/index.php?topic=79637.msg1312091#msg1312091) to ship
around the [first week of
December](https://bitcointalk.org/index.php?topic=79637.msg1257857#msg1257857) *for the
first
batch*. 

_Note_: there has been some ambiguity regarding what ["first week after
thanksgiving"](https://bitcointalk.org/index.php?topic=79637.msg1257857#msg1257857) means.
Tom has stated this is the [next business
week](https://bitcointalk.org/index.php?topic=79637.msg1291185#msg1291185) following the
week containing Thanksgiving. A realistic timeframe is approximately __after the 26th of 
Nov. but before the 7th of Dec.__

https://bitcointalk.org/index.php?topic=79637.msg1257857#msg1257857

The second batch is set to ship January of 2013 (as per
[bitcoinasic.net](http://www.bitcoinasic.net)). Tom has stated it should ship a month
after the first batch. (IRC #btcfpga; 20121106)

[section last here removed due to being complete speculation]

### Shipping Methods

Standard is USPS, though an upgrade to DHL is available.

Persons inside the United States won't notice the upgrade much; however, those outside the
US (and possibly Canada) should notice a [large
improvement](https://bitcointalk.org/index.php?topic=79637.msg1294089#msg1294089) in
shipping time.

### Fabrication

"ASICs have been in fabrication for some weeks now" [(on 27th October,
2012)](https://bitcointalk.org/index.php?topic=79637.msg1300687#msg1300687)

### Assembly

The assembly house used is able to assemble [1000 boards in 5
days](https://bitcointalk.org/index.php?topic=79637.msg1300687#msg1300687). The assembly
house is [thought](https://www.btcfpga.com/forum/index.php?topic=21.msg148#msg148) to be
[Screaming Circuits](http://www.screamingcircuits.com/) (official source needed)

Power Requirements
------------------

Tom has [stated](https://www.btcfpga.com/forum/index.php?topic=4.msg132#msg132) that
power requirements are estimated to be:

* 27 Gh/s: 50 - 60 Watts
* 54 Gh/s: 100 - 120 Watts

Both are thus **1.85 - 2.22 W / Gh/s**

The estimate of 100 W per 54 Gh/s bASIC is used throughout this document, and
approximately half for 27 Gh/s models.

Power Supplies and Connectors
-----------------------------

### Power Connectors

Both bASIC models will have a 4 pin molex connector and a barrel connector (aka female DC
coaxial connector).
[(Source)](https://bitcointalk.org/index.php?topic=79637.msg1315070#msg1315070)

The barrel connector is _thought_ to be a centre +'ve
[2.1](https://bitcointalk.org/index.php?topic=79637.msg1314859#msg1314859) or
[2.5](https://bitcointalk.org/index.php?topic=79637.msg1315524#msg1315524) mmID 5.5 mmOD
type. (ID = inside diameter, OD = outside diameter). It should be able to provide 12 V and
10 A (DC of course). It seems 2.1/5.5 centre +'ve connectors are uncommon above 5 A, so a
2.5/5.5 connector might be more likely (often rated for up to 10 A).

**If you are buying a wall wart** please buy a _high quality_ power adapter. There is no
sense in ruining a thousand dollar piece of machinery due to a below average power
adaptor.

Cablez [sells PSU to 2.1/5.5 & 2.5/5.5 DC
plugs](https://bitcointalk.org/index.php?topic=74397.0) 
compatible with BitFoce singles (Tom 
[has stated](https://bitcointalk.org/index.php?topic=79637.msg1315070#msg1315070) that at 
least the dimensions are the same. The linked post is ambiguous as to power needs;
however, it is likely these are identical to PSU requirements: DC, 12 V, 10 A)

[Images](https://bitcointalk.org/index.php?topic=79637.msg1314785#msg1314785).


### Power Supplies

A bASIC [*will not*](https://bitcointalk.org/index.php?topic=79637.msg1315070#msg1315070)
ship with any power supply.

However, you can buy a PSU that is compatible from Tom's store
[here](https://www.bitcoinasic.net/index.php?route=product/product&product_id=54).
This PSU will be able to power up to 10 bASIC mining units. If you are planning on running
less than 10 a smaller PSU (in terms of wattage) might be more appropriate.

Please exercise due diligence with regards to PSUs. Having $10,000 worth of equipment on
one PSU provides no hedging. If this concerns you, please consider using multiple PSUs
(possibly with a lower maximum wattage each) in order to spread risk. This is *especially*
true with lower quality PSUs.

**Please be sure to use quality** PSUs and be sure not to stress them too hard to give
yourself the lowest risk factor you can. It is reccomended you keep the wattage below 80%
or so of the maximum rating on a PSU. This is more important than a PSU for gaming or a
normal system as this PSU will be running *constantly*.

### What Should I Know When Purchasing a PSU

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

**Note:** floor(12 \* 13 / 100) gives the number of bASICs you can run from each rail

#### Formula:

I believe the general formula would be:

__Num-rails \* floor(rail-volts \* rail-amps / 100 Watts) = Num-bASICs__

### What is Required when Purchasing a Wall Wart

(Todo - need confirmation of barrel connector details)



bASIC details
-------------

* 27 Gh/s: one 6 chip cluster with heatsink and fan; 90 nm architecture
* 54 Gh/s: two 6 chip clusters with a heatsink and fan over each cluster; 90 nm
architecture

[Neither](https://bitcointalk.org/index.php?topic=121884.msg1312300#msg1312300) will be
enclosed.

Sources: [54
Gh/s](https://www.bitcoinasic.net/index.php?route=product/product&product_id=51) and [27
Gh/s](https://www.bitcoinasic.net/index.php?route=product/product&product_id=50)

### Production details

Tasks handled by the assembly firm and their engineers:
[(Source)](https://bitcointalk.org/index.php?topic=79637.msg1238806#msg1238806)

* Designing the production board
* Fabrication of PCB's
* Assembly of boards to completion

After this the final boards will be shipped to Tom. Then - with a team of full time
employees the following will occur:
[(Source)](https://bitcointalk.org/index.php?topic=79637.msg1238806#msg1238806)

* Open boxes
* Load Firmware
* Test bASICs for 24 hours each
* Box up and ship

Production and assembly will be a long process, and may take up to a week.

### bASIC Physical Dimensions

* 27 Gh/s: 5 x 4 inches; 12.7 x 10.2 cm (rounded up to nearest mm)
* 54 Gh/s: 9 x 4 inches; 22.9 x 10.2 cm (rounded up to nearest mm)

[Source](https://bitcointalk.org/index.php?topic=121884.msg1312300#msg1312300)

### SHA256 Core

The SHA256 Core (the heart of the ASIC) has [been provided by a 'well known' company from
outside the US](https://bitcointalk.org/index.php?topic=79637.msg1157886#msg1157886). They
are a top design firm in regards to these types of cores.

### Compatible Miners

I (XertroV) don't know much about this. If you can lend a hand it'd be appreciated. I won't
add software unless it can be sourced to protect against my own ignorance.

* [BFGMiner](https://bitcointalk.org/index.php?topic=78192.0)




Will I need to pay Import Duties if I'm in the EU
-------------------------------------------------

[This page
(ec.europa.eu)](http://ec.europa.eu/taxation_customs/dds2/taric/measures.jsp?Lang=en&
SimDate=20121105&Area=US&Taric=8542319000&LangDescr=en)
seems to indicate that import duties will be 0%.

You may be required to pay VAT if you don't have a VAT number. This will be changed on the
total customs value (e.g. $1069 per bASIC + $90 for DHL). The authors encourage you to
research this for your particular case.
[http://www.dutycalculator.com/](http://www.dutycalculator.com/) may be of assistance.

Do bASICs need to be okay'd by the FCC
--------------------------------------

This is unlikely because they are shipped as components and not a stand-alone machine.
Despite this, Tom [will be ensuring that bASICs are within FCC
regulations](https://bitcointalk.org/index.php?topic=79637.msg1313940#msg1313940). You
need not worry about this.


Tom's Shop
----------

### Images

Tom's Flickr album is here: http://flic.kr/ps/2m9aox

### Is it Safe?

Tom has stated they have a complete security system and they are located in close
proximity to a police station. In addition, when ASICs are being assembled there will be a
staff member present around the clock.
[(Source)](https://bitcointalk.org/index.php?topic=79637.msg1313840#msg1313840)






Contributors
------------

My appreciation is given to all contributors. They are as follows (probably in
chronological order of contribution):

* XertroV (Original Author)
* cheebydi (VAT / Import Duties and Misc)
* Odi (New material suggestions plus fact-checking and sourcing)


