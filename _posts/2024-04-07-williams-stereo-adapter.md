---
layout: post
title: "Williams Stereo Adapter for Stargate, Joust, and Sinistar"
date: 2024-04-07
---

![Completed Williams stereo adapter install]({{ site.baseurl }}/assets/images/williams/complete.jpg)

### Add stereo sound to your Stargate, Joust, or Sinistar

## What Is It?

One of the only early-80s Williams games that featured stereo sound was Sinistar — but only in the cockpit version. This project shows how you can add that same original stereo sound to an upright Sinistar, as well as add stereo to Joust and Stargate.

## Videos

I added stereo to my Stargate and it sounds great! Unfortunately, it's difficult to hear the stereo in a cell phone video recording — it sounds much better in person.

<iframe width="560" height="315" src="https://www.youtube.com/embed/sVfttbVLo6k" title="Williams stereo adapter demo, Stargate" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/h_hqxc9s1T0" title="Williams stereo adapter demo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

![Stereo-modified Williams cabinet]({{ site.baseurl }}/assets/images/williams/machine2.jpg)

## What You'll Need

1. **A second working Williams sound board** (1C-2001-146-6) — look for one on eBay.

2. **A 2532 EPROM** programmed with either the Sinistar, Joust, or Stargate special stereo ROM (keep reading for more info).

3. **A soldering iron** and experience with soldering.

4. **An interconnect PCB.** This PCB avoids custom wiring or hacking of the stock harness — the stereo board taps all its connections right from the main harness and provides quick screw terminals for easy speaker hookup, plus a built-in volume pot. Available from [BSG Electronics](https://bsgelectronics.com/williams-stereo-interconnect-board).

   ![Williams stereo interconnect board]({{ site.baseurl }}/assets/images/williams/board.jpg)

5. **An 8-ohm speaker or similar.** You can place the speaker on a shelf, on top of the cabinet, or do a more permanent install inside the cabinet if you prefer — I used a small Bose bookshelf speaker with my Stargate.

6. **Speaker wire.**

7. **An inline click-wheel switch (optional)** — lets you easily toggle stereo on/off.

   ![Inline click-wheel volume switch]({{ site.baseurl }}/assets/images/williams/th.jpg)

8. **Molex and speaker parts** from [Digikey](https://www.digikey.com/en/mylists/list/NV6H9PY4BS). (Note: these [cheaper 4mm speaker posts on eBay](https://www.ebay.com/itm/384940453644) will also work.)

9. **[An A50K potentiometer](https://www.ebay.com/itm/304482856805)**

10. **[8x 1/4" hex x 1-1/2" aluminum standoffs, 8-32 thread, male/female](https://www.ebay.com/itm/192562877297)**

## Stereo ROMs

[Download the stereo ROMs (ZIP)]({{ site.baseurl }}/assets/images/williams/StereoRoms.zip)

## Assembly Tips

1. **Test the stereo board before installing the ROM or changing any jumpers.** The Stargate stereo ROM does not play any sounds when you press the diagnostics button — I haven't confirmed yet whether Joust or Sinistar stereo makes diagnostic sounds.

2. **Jumper the stereo board for a 2532 EPROM.** Connect the W1, W3, W4, W5, W7, W10, and W15 jumpers; remove all other jumpers. See [jestersattic.com's Williams sound board reference](https://www.jestersattic.com/wms_snd.php) for more detail.

   ![Stereo board jumper configuration]({{ site.baseurl }}/assets/images/williams/jumpers.jpg)

3. **Note:** even though Stargate uses a 2716 for its main board, a 2532 is still needed for the stereo board.

4. **Remove the screws from your existing sound board** and replace them with the hex standoffs. Reuse the existing screws to mount the stereo board to the standoffs.

5. **Need a 2532 EPROM programmed?** Message me — I may be able to help.

## Thank You

Thanks to Synamax for reverse-engineering the Sinistar source code and creating the Joust and Stargate versions of the stereo ROM. Check out his story here:

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZRDdKZ7V54I" title="Synamax's Williams stereo ROM story" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
