# Install

---

[Home](../)

---

## Emulation Mode

The Behringer BCF2000 needs to be in MCU mode to function with these files. MCU mode can be entered by following the next steps

* Power of the BCF2000
* Hold down the second button of the top row (Row under the encoders)
* While holding down the button, power up the BCF2000

You should be in MCU mode now.

>There's also a video on this on [ReaperBlog](https://reaperblog.net/2015/04/behringer-bcf2000-basic-setup-in-reaper/). Jon tells you exactly how to do so.

## Copy the files

If you are here and want to install these files, I presume you already did the steps for installimng CSI. If not, [install CSI first](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Installation). For now stop after step 5. We will pick up later from here

Here the steps for instaling Reapinger BCF2000:

* Open the CSI folder in Finder, Explorer, or whatever application you are using for browsing files.
* Copy the `Reapinger-BCF2000.mst` file in the Surfaces/Midi folder to the Surfaces/Midi folder in CSI.
* Copy the `Reapinger-BCF2000` folder in the Zones folder to the Zones folder in CSI.
* The folder structure should look like below

```
CSI/
├── Surfaces/
│   ├── Midi/
│       ├── Reapinger-BCF2000.mst
│       └── Other files.mst
├── Zones/
│   ├── Reapinger-BCF2000/
│   │   └── Reapinger-zon-files
│   └── bootstrap.min.js
└── Other CSI Folders/
```

## Install the Surface and Zones

Now we can continue with the installation steps as statet on the CSI wiki pages. There are 2 differences:

* **Step 11**: Choose `Add Midi`
* **Step 12**: The number of channels is: 8
* **Step 13**: The number of sends is 8
* **Step 14**: The number of effects is 8
* **Step 16**: For both the Surface and Zones we need to select `Reapinger-BCF2000`. Also check the `Auto Map Focussed Effects` checkbox.

And you're done.

---
