# ReturnTi.me
Source for the ReturnTi.me web 'app'. In action at https://returnti.me

## Overview
A simple page to be displayed when a shared screen is used by a
group of people. Great for emnsemble/mob programming breaks, virtual
conferences, etc.

## Purpose
ReturnTime displays a web page to be shown on video conferencing
screens during rest breaks and other interruptions. It was created
to support teams in coding ensembles (pairing/mobbing/teaming
programming) where the whole group is taking a break and will
return at a later time. This is useful for team members to have on
their screens while working at home, or in shared meeting rooms at
an office.

## Live, Editable Text
The text at the top of the screen and the timeszone display at
the bottom can be changed simply by clicking on or tabbing to the
text and using standard cursor movements. The text at the top will
default to the query string parameter 'msg' value. Try
https://returnti.me?msg=Will%20Return%20Soon for a more generic
message.

## The Clock
The large LED-style clock supports 12- and 24-hour time, with
English am/pm indicators as needed. The seven-segment LED figures
support a 'ghost voltage' state, showing just a small amount of
residual light. When the 'tens place' hour figure is fully dark,
its opacity is boosted just a bit to make the overall display
retain some visual balance. To set the clock to 24-hour display,
add "&hours=24" to the query string. Set the clock color is done
via the "&clockcolor=<color>" option which accepts common color
names as well as standard web color settings like "%23ff35ee". 
(%23 is the URL encoding for '#'.)

## Example URLs:
	
*	https://returnti.me?msg=Will%20start%20again%20at%201pm
*	https://returnti.me?msg=Meal%20break%20until%2019:30&hours=24
*	https://returnti.me?msg=Party%20at%20Noon!&clockcolor=yellow
*	https://returnti.me?msg=Break%20until%20top%20of%20hour&clockcolor=%23ff35ee&hours=24

A backup copy of the site is available at:

*	https://rossolson.github.io/returntime/?msg=Via%20GitHub😄  ⬅︎ includes an emoji!
	
## Changelog

	2022-09-20 - Now with backup hosting at GitHub page.
	2022-09-08 - Added support for clockcolor to SVG, and page passthru.
	2022-08-29 - First version
	
