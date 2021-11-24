# Cheat Sheet - Roland MC-101 Groovebox

![Roland MC-101 Diagram](mc-101.PNG)

Hi there, and welcome to the unofficial Cheat Sheet for the [Roland MC-101 Groovebox](https://www.roland.com/global/products/mc-101/)! 

This Cheat Sheet aims to provide a one or two pager of the most useful shortcuts and workflow operations of this nifty little Groovebox. Please note that you'll be able to find *most* of these by reading the manuals, but who has time to go through all of that, right? ;)

## How to read this cheat sheet

Everything in **bold** refers to a control (a button, knob or slider) on the front panel of the MC-101 (see picture above). 

A **+** (**plus-sign**) between two or more controls indicates that those controls should be used simultaneously, in the specified order. 

A **,** (**comma**) between two or more controls indicates that those controls should be used sequentially, in the specified order.

## Completeness and correctness
First of all, this is a work-in-progress (WIP) until specified differently. You're currently looking at the Markdown version of the cheat sheet, the PDF version can be found [here](mc101-cheatsheet.pdf).

Though I always strive to be complete and correct, there's always the chance that there's something missing or just plain wrong in here. Should that be the case then make good use of the [New Issue](https://github.com/NLxAROSA/mc101cheatsheet/issues/new/choose) button from the [Issues](https://github.com/NLxAROSA/mc101cheatsheet/issues) tab above. Or even better: [New Pull Request](https://github.com/NLxAROSA/mc101cheatsheet/compare) from the [Pull Requests](https://github.com/NLxAROSA/mc101cheatsheet/pulls) tab! 

Anyway, enough chitchat, see below for the Cheat Sheet!


# Cheat Sheet - Shortcuts

## Global shortcuts

|Action|Shortcut|
|-----------------------------------|-----------------------------------|
|Track settings|**Shift**+**Track Sel**|
|Clip settings|**Shift**+**Clip**|
|Sound settings|**Shift**+**Sound**|
|System menu|**Shift**+**Filter**|
|Motion editor|**Shift**+**Mod**|
|Copy clip/track|**Shift**+**FX**|
|Clear clip|**Shift**+**Project**+**Track Sel**|
|Quick write project|**Shift**+**Tempo**|
|Scatter settings|**Shift**+**Scatter**|
|Quantize settings|**Shift**+**Record**|
|Multi FX settings|**Shift**+**Multi FX**|
|Display knob value|**Shift**+**Knob**|
|Knob fine adjustment|****Sound/Filter/Mod/FX**+**Value Knob**|
|Select C1 parameter|**Sound**+**C1**|
|Select C2 parameter|**Filter**+**C2**|
|Select C3 parameter|**Mod**+**C3**|
|Select C4 parameter|**FX**+**C4**|
|Storage mode|**Project**+power on device|
|Enter scene mode|**Clip**+**Seq**|

## Sequence editing shortcuts

|Action|Shortcut|
|-----------------------------------|-----------------------------------|
|Copy/Paste Step|Select **Pad** to copy, **Shift**+**FX**, Select **Pad** to paste, **Shift**+**FX**|
|Delete Step|**Shift**+**Project**+**Pad**|
|Pad edit|**Shift**+**Note**|
|Duplicate measure|**Seq**+**>**|
|Halve measure|**Seq**+**<**|
|Add drum substep|**Seq**+**Pad**|
|Add low velocity drum hit|**Track Sel**+**Pad**|
|Clear clip|**Shift**+**Project**+**Clip**|
|Edit measure length|**Shift**+**>** or **Shift**+**<**|
|Auto-advance mode (tone track only)|**Pad**, **Record** + **Pad** of 1st step|
|Note edit|**Seq**, **Pad**, **C1**-**C4** to change values|
|Note edit alternative|**Seq**, **Pad**, hold **Sound** or **Filter** or **Mod** or **FX**, **Value** to change value.|
|First/last step mode|**Shift**+**Seq**|
|Cancel first/last step|**Shit**+**Project** while in first/last step mode|
|Toggle notes/chords|Press twice **Note**|
|Chord designer|In chord mode, press **Shift**+**Filter**|

## Playback shortcuts

|Action|Shortcut|
|-----------------------------------|-----------------------------------|
|Force start|**Shift**+**Play**|
|Mute/Unmute drum part|**Note**+**Pad** (for clip) or **Track Sel**+**Pad** (for track)|
|Transpose tone track|**Note**+**Pad**|
|Select pitch of looper track|**Note**+**Pad**|
|Random sequence|**Track Sel**+**>**|
|Reverse sequence|**Track Sel**+**<**|
|Tap tempo|**Shift**+**Exit**|
|Toggle metronome|**Tempo**+**Exit**|
|Toggle arpeggiator|Long press **Note**|
|Stutter/top of pattern|**Shift**+**Play** while playing|
|Start/Stop current clip|**Clip**+**Sel** while playing|
|Multi FX parameter select|**Multi FX**+**FX Prim**|
|Multi FX parameter depth|**Multi FX**+**FX Depth**|
|View knob value|**Shift**+**C1**-**C4**|


## Scene shortcuts

|Action|Shortcut|
|-----------------------------------|-----------------------------------|
|Store Scene|**Clip**+**Pad1**-**Pad8**|
|Recall Scene|**Clip**+ long press **Pad1**-**Pad8**|
|Scene selection|Long press **Clip**|
|Scene chain|**Shift**+**Pad**|


# Cheat Sheet - Workflows


## Step recording tone track

Start editing: Press **Seq**, then **Pad** to select the first step, then **Note**. Enable/disable notes via **Pad** (hold for tie). Select step via **Value**.


## Step recording drum track:

Start editing: Press **Note**,**Pad** to select the drum part to edit, then **Seq**. Enable/disable steps for given drum part. Select drum part via **Value**.


First/Last Step mode:


Select last step: **Pad**

Select first step: **Shift**+**Pad**


## Realtime recording a tone track

Press **Record**,**Note**, then Play; play on the pads, press **Record** again to stop.


## Realtime recording a looper track

Press **Pad**, then **Shift**+**Record**, select source from menu. Press **Pad** to select clip and press **Record**. This puts it on standby-recording mode and will record the 1st 8 measures (max) after pressing Play.


## Realtime recording motion to a track

Make sure motion is on (via Motion Editor), Press **Play**, **Record**, press **Sound** or **Filter** or **Mod** or **FX**, **C1**-**C4** to record motion for each track. Press **Record** again to stop.


## Editing motion for a step

Press **Seq**, **Shift**+< or **Shift**+> to select step. Press **Value**, **C1**-**C4** to change motion value.
