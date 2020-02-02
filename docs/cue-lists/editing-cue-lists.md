---
id: editing-cue-lists 
title: Editing cue lists
sidebar_label: Editing cue lists
---

Playback View window
--------------------

The easiest way to edit a cue list is using the Playback View window
(press \<View/Open\> then the select button for the cue list to open
it). This shows a grid with each cue and allows you to change most
features of the cue. Click on the item you want to change in the grid,
and the softkeys will offer you the different options.

To change multiple cues at once, draw a box across the items you want to
change.

The Intensity View window is useful for seeing the state of all
fixtures, see section 5.2.2 on page 133.

Editing values in Cue View window
---------------------------------

You can edit the value of every fixture in each cue using the Cue View
window. Press the View Cue button at the right hand end of the Playback
View window.

![cueview](/docs/images/image257.png)

You can then click on the values you want to change and edit them using
the softkeys.

-   The context menu buttons allow you to view levels, shapes, effects
    and times for each attribute of each fixture in each cue.

-   If levels are set from a palette, the View Palettes button either
    shows you the palette used, or the underlying value.

-   If the View Tracking Values button is selected, tracking values
    (values which have tracked through from another cue rather than
    being stored directly in this cue) are shown in light grey.

Moving and copying cues
-----------------------

You can copy or move cues within a cue list or to other cue lists.
Either click and drag the cue in the Playback View window (press
Open/View then the select button for the cue list), or use Unfold (next
section), or you can use a command-line style series of keypresses.

Copy/Move within the same playback:

-   COPY/MOVE \<playback\> \<cue\> \[THRO \<cue\>\] \[NOT \<cue\>\]
    \[AND \<cue\>\] @ \<cue\> ENTER

-   COPY/MOVE \<playback\> \<cue\> \[THRO \<cue\>\] \[NOT \<cue\>\]
    \[AND \<cue\>\] ENTER \<cue\> ENTER

Copy/Move to the end of the same playback:

-   COPY/MOVE \<playback\> \<cue\> \[THRO \<cue\>\] \[NOT \<cue\>\]
    \[AND \<cue\>\] @ @

-   COPY/MOVE \<playback\> \<cue\> \[THRO \<cue\>\] \[NOT \<cue\>\]
    \[AND \<cue\>\] ENTER ENTER

Copy/Move to a different playback:

-   COPY/MOVE \<playback\> \<cue\> \[THRO \<cue\>\] \[NOT \<cue\>\]
    \[AND \<cue\>\] \[@\]\[ENTER\] \<playback\> \<cue\> ENTER

Copy/Move to the end of a different playback:

-   COPY/MOVE \<playback\> \<cue\> \[THRO \<cue\>\] \[NOT \<cue\>\]
    \[AND \<cue\>\] \[@\]\[ENTER\] \<playback\> ENTER

-   COPY/MOVE \<playback\> \<cue\> \[THRO \<cue\>\] \[NOT \<cue\>\]
    \[AND \<cue\>\] \[@\]\[ENTER\] \<playback\> \<playback\>

(\<playback\> is a playback swop key, \<cue\> is the cue number and
sections in square brackets are optional)

Editing a cue list using Unfold
-------------------------------

The \<Unfold\> button places each cue of the cue list on one of the
playback faders. This allows you to fire and edit each step individually
as if it was a stand-alone cue.

1\> Press \<Unfold\>, then the Select button of the cue list to be
edited.

2\> Cues are loaded into the playback faders. The display shows the cue
numbers and legends (see more cues using softkeys F and G).

3\> Raise a playback fader to output the contents of that cue (fade
times will operate as programmed).

4\> Various Unfold options are available, the details are below.

5\> Press \<Unfold\> again to get out of unfold mode.

-   To edit the contents of a cue: Press \<Clear\> to empty the
    programmer, raise the fader to output the cue, make the changes,
    press \[Record Step\], then the Select button for the cue number.

-   To merge the programmer into the live step, double tap \[Record
    Step\].

-   To change the times or cue linking for the cue, press \[Edit
    Times\], then the Select button for the cue, then set the times (see
    Timing on the following page)

-   To insert a new cue, set up the look for the new cue, press B
    \[Insert Step\], then press the playback button where you want the
    new cue to go. All following cues will be shifted on by one and the
    new cue will be given a number in between the two existing cues (for
    example, if you press playback 3, your new cue will be 2.5).

-   To move or copy a cue, press the \<Move\> or \<Copy\> button, press
    the select button for the cue you want to move or copy, then press
    the select button where you want it to go.

-   To delete a cue, press the \<Delete\> button then the select button
    for the cue you want to delete. Press the select button again to
    confirm.

-   To change the cue legend, press \[Set Step Legend\] then the
    playback select for the step you want to change.

-   If the cue list has more cues than there are playback faders, you
    can swop to the next page using softkeys F and G.

Using Update to change tracked cues
-----------------------------------

Because fixture settings in a cue list are tracked through from previous
cues, if you want to edit a setting you need to find the cue where it
was originally set.

The Update function will go back through the cue list from the currently
fired cue and automatically update the correct cue.

1\> With the cue list fired, select the fixtures and change them to the
settings you want to store.

2\> Press \<Update\> (\<Record Cue\>, \[Update\] if the console doesn't
have an Update button).

3\> Press \<Enter\> to immediately store the new values to the cue list.

Alternatively, the softkeys show a list of palettes and playbacks which
can be updated. Select or deselect these as required.

4\> If you have used the softkey options, press \<Enter\> to complete
the update.

-   If the attributes you have changed were tracked through from a
    previous cue, Update will update that cue rather than the current
    one.

Editing a cue list which is running
-----------------------------------

You can also edit cues in a cue list while you are running it without
using Unfold.

1\> Fire the cue list by raising its fader.

2\> Use Wheel A to select the cue number you want to change then the
\<Go\> button to jump to it. (On Pearl Expert/TT Mk1 press the white ↔
button above the Snap Back button instead of \<Go\>)

3\> Press \<Clear\> to make sure the programmer is empty.

4\> Make the changes that you want to the current step.

5\> Press \<Record\> then \<Connect\>, then select \[Replace\],
\[Merge\] or \[Insert After\] to save the changes. (On Pearl Expert and
TT Mk1 use the Rec Step button)

6\> Press the \<Go\> button (on Pearl Expert and TT Mk1 the white ↔
button) to jump on to the next step.

-   You can edit the times for a cue using the \<Live Time\> and \<Next
    Time\> buttons (not on all consoles) as follows:

    1\> Fire the cue list by raising its fader.

    2\> Use Wheel A to select the cue number you want to change then the
    \<Go\> button to jump to it (on Pearl Expert and TT Mk1 the white ↔
    button)

    3\> Press \<Live Time\> to set the times for the current step, or
    \<Next Time\> for the next step. The Live and Next step numbers are
    shown on the display above the controller wheel.

    4\> Use the softkeys to set the times, linking and overlap settings
    you want (see section 8.5.1 on page 211 for description of the
    times). If you set the \[Link to next step\] option to On, then the
    next cue will not wait for the \<Go\> button.

    5\> Press the \<Go\> button (on Pearl Expert and TT Mk1 the white ↔
    button) to jump on to the next step.

-   The Review button lets you test the live step with the new timings.

-   You can also use \<Unfold\> to set the times as described in the
    Unfold section above.

Editing a cue list while recording
----------------------------------

You can edit cues while you are in the Record Cue List menu.

1\> Press \[Cue Number=x\] and type the cue number to be edited.

2\> The console will jump to the cue and show the output.

3\> Make the changes that you want to the programming of the current
step, or to the timings using \[Edit Cue x Times\].

4\> Press \[Update Cue x\] or the Rec Step button to save the changes.

-   The \[Update Mode\] softkey allows you to set how changes in the cue
    will be tracked. \[Update Mode Forwards\] updates the channels in
    the current cue and tracks following cues until the channels are
    next changed. The values in cues before this one will not be
    changed. \[Update Mode Backwards\] updates the current cue and
    tracks backwards through cues until the channels were last changed.
    \[Update Mode Both\] will update the current cue, tracking backwards
    through previous cues from the previous change and forwards through
    following cues to the next change. \[Update Cue Only\] will just set
    the current cue.\
    \
    ![](/docs/images/image258.png){width="1.0138888888888888in"
    height="0.7222222222222222in"}
    ![](/docs/images/image259.png){width="0.9861111111111112in"
    height="0.7222222222222222in"}
    ![](/docs/images/image260.png){width="0.9861111111111112in"
    height="0.7361111111111112in"}
    ![](/docs/images/image261.png){width="0.9722222222222222in"
    height="0.7222222222222222in"}

-   You can't change the cue number using this menu -- if you press
    \[Cue Number\] this will change the cue you are editing. Use
    \[Advanced Options\] to change cue numbers.

Updating values in a range of cues
----------------------------------

You can merge or replace values in a range of cues in a cuelist (or a
chase). This can be done either from the keypad or from the Playback
View.

From Playback View, press \<Record\> then select a cue or range of cues
by touching and dragging over the required cues. Select \[Merge\] or
\[Replace\] (or press \<Enter\> to merge). The current programmer will
be merged into all of the selected cues.

From the keypad, connect the cue list (or chase) and press \<Rec Step\>.
Then use the syntax \<n\> THRU \<m\> to select a range or \<n\> AND
\<m\> to select cues which aren't together. The selected cues will
highlight in red in the Playback View if you have it open. When you have
selected all desired cues press \<Enter\>, then select \[Merge\] or
\[Replace\] (or just press \<Enter\> again to merge).

Disabling a cue
---------------

You can temporarily disable a cue using the Disable option at the right
hand end of the Playback View window. Select the Disabled box and the
softkeys let you set \[Cue Disabled\]. When a cue is set to Disabled it
will be skipped. This can be a useful way to remove a cue, but still be
able to put it back in later.

Extracting a cue from a cue list with Include
---------------------------------------------

You can reload a single cue out of a cue list into the programmer using
Include. Press \<Include\>, select the cue list, enter the cue number to
be included, then press \[Include Cue\].

If you want to do this from the currently connected cue list, Press
\<Include\>, \<Connect\>, type cue number, \[Include Cue\].

This is useful if you want to reuse a state from a cue list in another
playback. It is also useful if you want to edit shapes/effects in a cue,
although you can also do this from the Playback View window.

