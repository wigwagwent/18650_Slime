# slimevr_pcb
A PCB design the size of a 18650 battery that supports the BMI160 designed for SlimeVR full-body trackers

- [18650_Slime-Main](/hardware/18650_Slime_main/) - A fully custom PCB that handles the IMU.

  Unlike most of the SlimeVR community, it uses the ESP32-C3, a newer and more
  powerful chip. Designed to be a more powerful development platform, as it natively
  supports JTAG debugging over USB, more compilers and languages, including Rust,
  and supports Bluetooth LE v5.0.
  ![3d render](/hardware/18650_Slime_main/renders/18650_Slime_Main_Front.png)

- [18650_Slime-Battery](/hardware/18650_Slime_battery/) - Combines fast charging with protection
  ![3d render](/hardware/18650_Slime_battery/renders/18650_Slime_Battery_Front.png)
  
  It can be used with other boards that want an 18650 cell with a built in charge controller.

## License
**This hardware is licensed under the CERN-OHL-P v2 license**, which is a permissive,
non-viral and non-reciprocal open hardware license. Unlike software licenses like
MIT and Apache 2.0, it better handles the nuances of hardware and protects both
the licensor and licensee from patent lawsuits.

**Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in this work by you, shall be licensed as above, without any
additional terms or conditions.**

### Conveying notice of License
Note that as part of the CERN-OHL-P v2 license, recipients of manufactured
hardware must also receive notice of the above license. One such
method of conveying the notice is to include a link to the original source repo,
or printing "Licensed under CERN-OHL-P v2" on the PCB silkscreen. For more info,
see [here](https://ohwr.org/project/cernohl/wikis/uploads/8a6b5d01f71c207c49493e4d114d61e6/cern_ohl_p_v2_howto.pdf).

This is conceptually similar to the MIT/Apache 2.0 Licenses, where the original
license must still be included as a notice even when the source is modified and
subsequently relicensed under different terms.
