# Reapinger BCF2000

<img src="./assets/reapinger-logo.png" style="width: 200px; float:left; margin-right: 1rem;" >

---

---

A repo containing the [MIDI surface][csi-surface] and zone files to let the [Behringer BCF2000](bcf2000) communicate like a madman with [Reaper][reaper].
It contains the default mappings as send and several effects.

---

---

> [Screenreaderfriendly version](./screenreader)

## Install and usage

* [Installation](./install.md)


## ¿What is supported?

The next effects and instruments are currently supported. Some of them need some more testing and some more finetuning for the values.
If you find faults or so ever, let me know so I can improve the files.

### Zones

* [Channel](./zones/Channel.md)
* [GroupButton(s)](./zones/Group.md)
* [Buttons](./zones/Buttons.md)
* [PresetButtons](./zones/Presets.md)
* [Transport](./zones/Transport.md)

### Sends

The **Sends** zone will avctivate the send tracks over the channels.

* [Sends](./zones/Sends.md)

### Effects

The **Effects** zone will avctivate the effect tracks over the channels.

* [Effects](./effects/index.md)

## Others

Everyone is welcome to contribute, so this can grow to support more and more effects, instruments, etc.
If you have any request and do not know how to make it? Let me know and I will try to help you out.

* [Credits](./credits.md)
* Licence: MIT
* [Code Of Conduct](./code-of-conduct.md)
* [Contribute](./contribute.md)

[reaper]: https://reaper.fm
[csi-surface]: https://github.com/malcolmgroves/reaper_csi/wiki/Defining-Control-Surface-Capabilities
[bcf2000]: https://www.behringer.com/Categories/Behringer/Computer-Audio/Desktop-Controllers/BCF2000/p/P0246#googtrans(en|en)
