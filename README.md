# Pre-work - Tip Calculator App

Tip Calculator is a tip calculator application for iOS.

Submitted by: Kathryn Thomas Hastings

Time spent: 03 hours spent in total

## User Stories

The following **required** functionality is complete:
* [Y] User can enter a bill amount, choose a tip percentage, and see the tip and total values.

The following **optional** features are implemented:
* [Y] Custom font
* [N] UI animations
* [Y] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [Y] List anything else that you can get done to improve the app functionality!
* [Y] Added a background image

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<a href="/course_images/ios_for_designers/littleTipster.gif" target="_blank"><img src='/course_images/ios_for_designers/littleTipster.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' /></a>

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes
Describe any challenges encountered while building the app.

* Everything’s brand new.
* Kept defaulting to trying PHP syntax when in doubt (not helpful).
* Kept defaulting to Javascript syntax, i.e. semicolons after everything from muscle memory (not helpful)
* Linked the wrong object for the calculateTip function and started over when I couldn’t figure out the issue
* Guerrilla user testing showed that having the grand total due first was confusing; user expected large number to be the input number; solution — change order of elements.
* Setting “focus” for the bill total on load (first responder)
* Getting the keyboard to appear on load (turn off hardware keyboard)

### Outstanding items/idea backlog — 
* Remove the background colour and line for the navigation controller
* Remove dollar sign from placeholder and consistently append to bill value total
* Experiment “absolutely” positioned decimal points
* Embed desired custom font (not in the custom list)
* Experiment with custom tip values
* Experiment with shared cost (i.e. splitting the tab)

## License

    Copyright [2016] [Kathryn Thomas Hastings]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
