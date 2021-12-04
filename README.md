# ESKD – KiCad runtime environment

This repository contains the special [KiCad] runtime environment for [ESKD].

> **[ESKD] – "Einheitliches System der Konstruktionsdokumentation des [RGW]"**

[ESKD] was a standardization system in the former [Eastern Bloc] at the time
of the East-West conflict and was strictly applied in all member states of the
[CMEA] (Council for Mutual Economic Assistance, [RGW]). With the
[Dissolution of the Soviet Union] and the [Fall of the Berlin Wall] in 1989,
it rapidly lost its validity and just as quickly lost its meaning. With the
[reunification] of East and West Germany in 1990, it became invalid overnight,
was no longer used and was replaced by the now valid [IEC] and [DIN] standards.

[KiCad]: https://www.kicad.org/ "A Cross Platform and Open Source Electronics Design Automation Suite"
[ESKD]: https://d-nb.info/551201940 "Deutsche Netionalbibliothek"
[DIN]: https://en.wikipedia.org/wiki/DIN "German: Deutsches Institut für Normung e.V."
[IEC]: https://en.wikipedia.org/wiki/International_Electrotechnical_Commission "International Electrotechnical Commission"
[RGW]: https://de.wikipedia.org/wiki/Rat_f%C3%BCr_gegenseitige_Wirtschaftshilfe "Rat für gegenseitige Wirtschaftshilfe"
[CMEA]: https://en.wikipedia.org/wiki/Comecon "Council for Mutual Economic Assistance"
[Eastern Bloc]: https://en.wikipedia.org/wiki/Eastern_Bloc "generally referred to the USSR and its satellite states"
[Dissolution of the Soviet Union]: https://en.wikipedia.org/wiki/Dissolution_of_the_Soviet_Union "1988–1991"
[Fall of the Berlin Wall]: https://en.wikipedia.org/wiki/Fall_of_the_Berlin_Wall "German: Mauerfall"
[reunification]: https://en.wikipedia.org/wiki/German_reunification "German: Deutsche Wiedervereinigung"

**The content in this repository are intended for KiCad version 6.x**,
clone with all sub-modules:

```
git clone --recurse-submodules ...
```

The follwoing KiCad [online documentaion](https://docs.kicad.org/master/)
can be useful:

* [KiCad – Getting started](https://docs.kicad.org/master/en/getting_started_in_kicad/)
  – [PDF](https://docs.kicad.org/master/en/getting_started_in_kicad/getting_started_in_kicad.pdf)
* [KiCad – Reference manual](https://docs.kicad.org/master/en/kicad/)
  – [PDF](https://docs.kicad.org/master/en/kicad/kicad.pdf)
  * [PCM](https://docs.kicad.org/master/en/kicad/#plugin_and_content_manager):
    *Plugin and Content Manager*
  * [Eeschema](https://docs.kicad.org/master/en/eeschema/)
    – [PDF](https://docs.kicad.org/master/en/eeschema/eeschema.pdf):
    *Schematic Editor with integrated Symbol Editor*
  * [Pcbnew](https://docs.kicad.org/master/en/pcbnew/)
    – [PDF](https://docs.kicad.org/master/en/pcbnew/pcbnew.pdf):
    *PCB Editor with integrated Footprint Editor*
  * [Pl Editor](https://docs.kicad.org/master/en/pl_editor/)
    – [PDF](https://docs.kicad.org/master/en/pl_editor/pl_editor.pdf):
    *Page Layout or Worksheet Editor (with `bitmap2component`)*
  * *Accessory Tools*:
    * [CvPcb](https://docs.kicad.org/master/en/cvpcb/)
      – [PDF](https://docs.kicad.org/master/en/cvpcb/cvpcb.pdf):
      *Associate components from schematic to component footprints*
    * [GerbView](https://docs.kicad.org/master/en/gerbview/)
      – [PDF](https://docs.kicad.org/master/en/gerbview/gerbview.pdf):
      *Gerber file (RS-274X format) and Excellon drill file viewer*
    * [IDFv3 Exporter](https://docs.kicad.org/master/en/idf_exporter/)
      – [PDF](https://docs.kicad.org/master/en/idf_exporter/idf_exporter.pdf):
      *Mechanical CAD data export (`dxf2idf`, `idf2vrml`, `idfcyl`, `idfrect`,
       `kicad2step`)*
    * [PCB Calculator](https://docs.kicad.org/master/en/pcb_calculator/)
      – [PDF](https://docs.kicad.org/master/en/pcb_calculator/pcb_calculator.pdf):
      *Set of calculation utilities*
* [KiCad – Plugin System](https://docs.kicad.org/master/en/plugins/)
  – [PDF](https://docs.kicad.org/master/en/plugins/plugins.pdf)

Other ESKD KiCad repositories are located on:

* Libraries: https://github.com/lipro-ecad/ESKD-kicad-libraries
* Templates: https://github.com/lipro-ecad/ESKD-kicad-templates
* Sources: https://github.com/lipro-ecad/ESKD-kicad-sources
