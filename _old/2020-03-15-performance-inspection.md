---
title: 151552Z MAR 20
categories:
  - Blog
  - Equipment
tags:
  - Testing
  - Equipment
gallery:
  - url: /assets/images/gallery-005/whspr-001x800.jpg
    image_path: /assets/images/gallery-005/whspr-001x800.jpg
    alt: "WSPR Results 01"
    title: "WSPR Results 01"
  - url: /assets/images/gallery-005/whspr-002x800.jpg
    image_path: /assets/images/gallery-005/whspr-002x800.jpg
    alt: "WSPR Results 02"
    title: "WSPR Results 02"
  - url: /assets/images/gallery-005/whspr-003x800.jpg
    image_path: /assets/images/gallery-005/whspr-003x800.jpg
    alt: "WSPR Results 03"
    title: "WSPR Results 03"
  - url: /assets/images/gallery-005/whspr-004x800.jpg
    image_path: /assets/images/gallery-005/whspr-004x800.jpg
    alt: "WSPR Results 04"
    title: "WSPR Results 04"
  - url: /assets/images/gallery-005/whspr-005x800.jpg
    image_path: /assets/images/gallery-005/whspr-005x800.jpg
    alt: "WSPR Results 05"
    title: "WSPR Results 05"
gallery2:
  - url: /assets/images/gallery-005/march_inpection-002x800.jpg
    image_path: /assets/images/gallery-005/march_inpection-002x800.jpg
    alt: "Inspection 01"
    title: "Inspection 01"
  - url: /assets/images/gallery-005/march_inpection-002x800-annoted.jpg
    image_path: /assets/images/gallery-005/march_inpection-002x800-annoted.jpg
    alt: "Inspection 02"
    title: "Inspection 02"
  - url: /assets/images/gallery-005/march_inpection-002x800xannotated.jpg
    image_path: /assets/images/gallery-005/march_inpection-002x800xannotated.jpg
    alt: "Inspection 03"
    title: "Inspection 03"
  - url: /assets/images/gallery-005/march_inpection-003-annotated.jpg
    image_path: /assets/images/gallery-005/march_inpection-003-annotated.jpg
    alt: "Inspection 04"
    title: "Inspection 04"
  - url: /assets/images/gallery-005/march_inpection-003x800.jpg
    image_path: /assets/images/gallery-005/march_inpection-003x800.jpg
    alt: "Inspection 05"
    title: "Inspection 05"
gallery3:
  - url: /assets/images/gallery-005/rig_and_pi-001x800.jpg
    image_path: /assets/images/gallery-005/rig_and_pi-001x800.jpg
    alt: "Raspberry Pi 01"
    title: "Raspberry Pi 01"
  - url: /assets/images/gallery-005/rig_and_pi-002xCrop.jpg
    image_path: /assets/images/gallery-005/rig_and_pi-002xCrop.jpg
    alt: "Raspberry Pi 02"
    title: "Raspberry Pi 02"
  - url: /assets/images/gallery-005/rig_and_pi-005-annotatedx800.jpg
    image_path: /assets/images/gallery-005/rig_and_pi-005-annotatedx800.jpg
    alt: "Raspberry Pi 03"
    title: "Raspberry Pi 03"
  - url: /assets/images/gallery-005/RTC-DS3231.jpg
    image_path: /assets/images/gallery-005/RTC-DS3231.jpg
    alt: "Realtime Clock Module DS3231"
    title: "Realtime Clock Module DS3231"
---
`6 Month Performance Appraisal & Inspection`
---

Time to take stock of the PRC's gear and performance so far.   After six months of licensed operations and manic gear acquisitions it was a good idea to lay out the big chunks and see what's what.

**WEAKNESS** Poor performance was shown in the 10 meter band with the Yaseau FT-891.  Voice comms on SSB weren't audible to fellow operators on the Saturday [NEMARC][3] net.  Some stations in the net are less than 5 miles away.
{: .notice--warning}

The clubs first participation in a contest was also poor.  Logging only 3 QSO's and only one of these being give a DXCC (whaterver that is).
{: .notice--warning}

![SSB Contest](/assets/images/gallery-005/contest-001.JPG){:height="75%" width="75%"}

No progress has been made in DIY production.  [Noted previously][4], this deficiency needs work to overcome.  Three QRP guys kits have arrived but assembly has not been attempted.
{: .notice--warning}

**SUCCESS** With the addition of digital modes transmit capability, transmissions with QSO's were made in WSPR, FT8 and JS8-Call.
{: .notice--success}

![Digital Modes](/assets/images/gallery-005/digital_modes-001.JPG){:height="75%" width="75%"}

WSPR power was set to 5 watts - lowest possible on the FT-891 - the results were surprising.

<figure>
{% include gallery id="gallery" caption="WSPR Results" %}
</figure>

Equipment:

Gear layed out for inventory:

<figure>
{% include gallery id="gallery2" caption="Gear Inspection" %}
</figure>

The new piece of gear enabling digital modes was the Raspberry Pi.  It is used to control the Yaseau FT-891 and encode/decode the digital signals.  [OH8STN][1] and [KM4ACK's][2] websites and YouTube channels are to thank for the guidance and setting up the Raspbery Pi.  As work in progress, the Pi is in a near constant state of rebuilding.  The latest addtion was the Real Time Clock (RTC) and a buck converter is being shipped to the PRC-TL-PF / QTH.

<figure>
{% include gallery id="gallery3" caption="Raspberry Pi for Digital Modes" %}
</figure>

[1]: https://www.youtube.com/channel/UC3xxr5EeFDtxnuHTWsDu2rA
[2]: https://www.youtube.com/user/jasonoleham
[3]: http://www.nemarc.org/index.html
[4]: https://pineland.radio/blog/WSPR-project-failure/