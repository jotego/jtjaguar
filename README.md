# FPGA Clone of Early Arcade Games

Designed by Jose Tejada (jotego - @topapate). PCB donated by **xxx**.

You can show your appreciation through
* [Patreon](https://patreon.com/jotego)
* [Paypal] (https://paypal.me/topapate)

Yes, you always wanted to have a Karate Champ arcade board at home. First you couldn't get it because your parents somehow did not understand you. Then you grow up and your wife doesn't understand you either. On top of that, an original PCB from Japan costs $500. Don't worry, MiST(er) is here to the rescue.

I hope you will have as much fun with it as I had it while making it!

## Supported Games

In chronological order:

 1. 

## Known Issues

## Keyboard

On MiSTer keyboard control is configured through the OSD.

For MiST and MiSTer: games can be controlled with both game pads and keyboard. The keyboard follows the same layout as MAME's default.

    F2      Test
    F3      Game reset
    P       Pause (press 1p or 2P during pause to hide the credits)
    1,2     1P, 2P start buttons
    5,6     Left and right coin inputs
    9       Service

    cursors 1P direction
    CTRL    1P button 1
    ALT     1P button 2
    space   1P button 3

    R,F,G,D 2P direction
    Q,S,A   2P buttons 3,2 and 1


## ROM Generation

There are MRA files available in the [rom/mra](rom/mra) folder. MRA files are the recommended way to boot the core in MiSTerFPGA. Use the [MRA-to-ROM converter](https://github.com/sebdel/mra-tools-c/) from Sebdel if your device does not accept MRA files natively.

## Binary Files

MiSTerFPGA, MiST, SiDi, NeptUNO and MC+/2 platforms are supported. Look for your platform binary files in [JTBIN](https://github.com/jotego). For MiSTerFPGA, the recommended way to get the core binary files is the [update_all](https://github.com/theypsilon/Update_All_MiSTer) script.

The **Analogue Pocket** version is supported for [Patreon](https://patreon.com/jotego) subscribers only.

## Compilation

This project uses the [JTFRAME](https://github.com/jotego/JTFRAME) framework. Please refer to it.

## Special thanks to Patreon subscribers

```
members
```