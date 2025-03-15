# HeliBoard
HeliBoard is a privacy-conscious and customizable open-source keyboard, based on AOSP / OpenBoard.
Does not use internet permission, and thus is 100% offline.

 # This fork of HeliBoard is closed 'cause of merging pull request into baze Heliboard, soon this changes will become publick with release of 3.0, and this repository no longer needed.
  Remember to uninstall this version before installing general Heliboard 'cause they signed with different signatures!

[<img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png" alt="Get it on F-Droid" height="80">](https://f-droid.org/packages/helium314.keyboard/)
[<img src="https://user-images.githubusercontent.com/663460/26973090-f8fdc986-4d14-11e7-995a-e7c5e79ed925.png" alt="Get APK from GitHub" height="80">](https://github.com/Helium314/HeliBoard/releases/latest)
[<img src="https://gitlab.com/IzzyOnDroid/repo/-/raw/master/assets/IzzyOnDroid.png" alt="Get it on IzzyOnDroid" height="80">](https://apt.izzysoft.de/fdroid/index/apk/helium314.keyboard)

## Table of Contents

- [Features](#features)
- [Contributing](#contributing-)
   * [Reporting Issues](#reporting-issues)
   * [Translations](#translations)
   * [To Community Creation](#to-community)
   * [Code Contribution](CONTRIBUTING.md)
- [To-do](#to-do)
- [License](#license)
- [Credits](#credits)

# Features
<ul>
  <li>Add dictionaries for suggestions and spell check</li>
  <ul>
    <li>build your own, or get them  <a href="https://codeberg.org/Helium314/aosp-dictionaries#dictionaries">here</a>, or in the <a href="https://codeberg.org/Helium314/aosp-dictionaries#experimental-dictionaries">experimental</a> section (quality may vary)</li>
    <li>additional dictionaries for emojis or scientific symbols can be used to provide suggestions (similar to "emoji search")</li>
    <li>note that for Korean layouts, suggestions only work using <a href="https://github.com/openboard-team/openboard/commit/83fca9533c03b9fecc009fc632577226bbd6301f">this dictionary</a>, the tools in the dictionary repository are not able to create working dictionaries</li>
  </ul>
  <li>Customize keyboard themes (style, colors and background image)</li>
  <ul>
    <li>can follow the system's day/night setting on Android 10+ (and on some versions of Android 9)</li>
    <li>can follow dynamic colors for Android 12+</li>
  </ul>
  <li>Customize keyboard <a href="https://github.com/Helium314/HeliBoard/blob/main/layouts.md">layouts</a> (only available when disabling <i>use system languages</i>)</li>
  <li>Customize special layouts, like symbols, number,  or functional key layout</li>
  <li>Multilingual typing</li>
  <li>Glide typing (<i>only with closed source library</i> ☹️)</li>
  <ul>
    <li>library not included in the app, as there is no compatible open source library available</li>
    <li>can be extracted from GApps packages ("<i>swypelibs</i>"), or downloaded <a href="https://github.com/erkserkserks/openboard/tree/46fdf2b550035ca69299ce312fa158e7ade36967/app/src/main/jniLibs">here</a> (click on the file and then "raw" or the tiny download button)</li>
  </ul>
  <li>Clipboard history</li>
  <li>One-handed mode</li>
  <li>Split keyboard (only available if the screen is large enough)</li>
  <li>Number pad</li>
  <li>Backup and restore your settings and learned word / history data</li>
</ul>

For [FAQ](https://github.com/Helium314/HeliBoard/wiki/FAQ) and more information about the app and features, please visit the [wiki](https://github.com/Helium314/HeliBoard/wiki)

# Contributing ❤

## Reporting Issues


# To-do
__Planned features and improvements:__
* Improve support for modifier keys (_alt_, _ctrl_, _meta_ and _fn_), some ideas:
  * keep modifier keys on with long press
  * keep modifier keys on until the next key press
  * use sliding input
* Less complicated addition of new keyboard languages (e.g. #519)
* Additional and customizable key swipe functionality
  * Some functionality will not be possible when using glide typing
* Add and enable emoji dictionaries by default (if available for language)
* Clearer / more intuitive arrangement of settings
  * Maybe hide some less used settings by default (similar to color customization)
* Make use of the `.com` key in URL fields (currently only available for tablets)
  * With language-dependent TLDs
* [Bug fixes](https://github.com/Helium314/HeliBoard/issues?q=is%3Aissue+is%3Aopen+label%3Abug)

__What will _not_ be added:__
* Dictionaries for more languages (you can still download them)
* Anything that requires additional permissions, unless there is a _very_ good reason

# License

HeliBoard (as a fork of OpenBoard) is licensed under GNU General Public License v3.0.

 > Permissions of this strong copyleft license are conditioned on making available complete source code of licensed works and modifications, which include larger works using a licensed work, under the same license. Copyright and license notices must be preserved. Contributors provide an express grant of patent rights.

See repo's [LICENSE](/LICENSE) file.

Since the app is based on Apache 2.0 licensed AOSP Keyboard, an [Apache 2.0](LICENSE-Apache-2.0) license file is provided.
The icon is licensed under [Creative Commons BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). A [license file](LICENSE-CC-BY-SA-4.0) is also included.

# Credits
- Icon by [Fabian OvrWrt](https://github.com/FabianOvrWrt) with contributions from [The Eclectic Dyslexic](https://github.com/the-eclectic-dyslexic)
- [OpenBoard](https://github.com/openboard-team/openboard)
- [AOSP Keyboard](https://android.googlesource.com/platform/packages/inputmethods/LatinIME/)
- [LineageOS](https://review.lineageos.org/admin/repos/LineageOS/android_packages_inputmethods_LatinIME)
- [Simple Keyboard](https://github.com/rkkr/simple-keyboard)
- [Indic Keyboard](https://gitlab.com/indicproject/indic-keyboard)
- [FlorisBoard](https://github.com/florisboard/florisboard/)
- Our [contributors](https://github.com/Helium314/HeliBoard/graphs/contributors)
