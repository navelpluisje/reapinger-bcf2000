# Install

---

[Home](../)

---

## Copy the files

If you are here and want to install these files, I presume you already did teh steps for installimng CSI. If not, [install CSI first](https://github.com/malcolmgroves/reaper_csi/wiki/Installation). For now stop at step 5. We will pick up later from here

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

First of all, the Behringer BCF2000 should be set to MCU mode. This [video on ReaberBlog](https://reaperblog.net/2015/04/behringer-bcf2000-basic-setup-in-reaper/) tells you exactly how to do so.

Now we can conrtinue with th einstallation steps as state mon the CSI wiki pages. There are 2 differences:

* **Step 13**: For both the Surface and Zones we need to select `Reapinger-BCF2000`. Also check the `Auto Map Focussed Effects` checkbox.

And you're done.

---
