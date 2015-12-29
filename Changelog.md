_23/01-2011: 2.8.5_
  * Live wallpaper, slight reaction to scrolling.
  * In app, up/down movement moves pictures slightly.
  * When feed appears empty, feed is refreshed in two minutes (Good for when sdcard is not ready).
  * Feeds are refreshed every other hour.
  * Live wallpaper settings separated from app settings.
  * Live wallpaper reacts to settings changes.
  * Bugfixes.
  * Bugs (probably, please report!)

_16/01-2011: 2.8.4_
  * More bugfixes.
  * Infinite rewind, not just back to start.
  * Pure black background colour added.

_11/01-2011: 2.8.3_
  * Picasa feed was broken, now it is not.

_11/01-2011: 2.8.2_
  * Nasty snarling bug fixed.

_11/01-2011: 2.8.1_
  * Nasty bug fixed.

_11/01-2011: 2.8.0_
  * Long press on stream to pause.
  * Live wallpaper rotation decoupled from app
  * Single press to catch stream (no need to move your finger around any longer)
  * "Photos from here removed", as "coarse location" makes people uneasy... (I never know who, where og why you are!)
  * General bugfixes
  * Grand try/catch removed. Please report crashes!!

_09/01-2011: Rock steady_
  * Avoid popping when returning to live wall paper.

_09/01-2011: Live and free_
  * Live wallpaper
  * Rewinding now goes back to the beginning of the stream - slightly out of order, but it's there!
  * Memory optimizations?

_December-ish: Heartbeat. Badump!_
  * Some work has been done to remove flickering.
  * Rotation now stays the same, when lying on a table,

_21/11-2010: Look ma, no hands!_
  * Removed performance profiling that crashed some phones, and lowered performance on other.

_20/11-2010: Hi mom!_
  * Black, grey (default), white, green, yellow, red, blue and multicoloured background now available.
  * ... That's it. I've been busy. :)

_05/10-2010: 2.6.8_
  * Re-enabled slide to pick next.
  * Remember manual image rotation.
  * Fixed automatic (Exif) image rotation bug. (2.0 and newer)
  * When panning over the edge while zooming, the image no longer pops.
  * Fixed bug that occurred when having forced a rotation.
  * Reverted to forcing portrait mode
  * Fixed minor bug in the text showing how many feeds were loaded.
  * Fixed some crashes (I hope)

_20/09-2010: 2.6.7_
  * Fixed some crashes.

_19/09-2010: 2.6.6_
  * Fixed crash.
  * Fixed some texture bugs.
  * Slight optimizations.
  * Disabled strange features: Random image cache lookup when lacking images, glow on new images.
  * Image cache also works on local images.
  * Using the image cache no longer deteriorates the cached image.

_15/09-2010: 2.6.5_
  * Multitouch tweaks. Should be less prone to accidental image switching now.
  * Orientation fix once more.
  * Wonky zoomed image fix.

_13/09-2010: 2.6.4_
  * Removed memory leak

_13/09-2010: 2.6.3_
  * Improved zoom navigation (Spring action when exceeding bounds)
  * Removed some unused code and textures = slight optimization
  * Fixed zoom texture bug
  * Added error handling - might fix HTC Wildfire texture bug?

_12/09-2010: 2.6.2_
  * Fixed immediate crash on 1.5 devices.

_12/09-2010: 2.6.1_
  * Fixed immediate crash on non-multitouch devices.

_12/09-2010: 2.6.0_
  * Multitouch! Not perfect, but not bad. :)
  * Rotation fix for devices with non-standard default rotation (ie. landscape)
  * Rotation option for devices that show wrong side up.
  * 2.2 devices get soft button light turned off
  * Facebook signout fixed
  * Rotation image reload made slightly smoother.
  * Exif reading fixed.
  * Various bugfixes

_06/09-2010: 2.5.7_
  * Fix crash when rotating while finishing download of large image.

_06/09-2010: 2.5.6_
  * Showing old image when rotating after new image is selected but not yet loaded, fixed.

_05/09-2010: 2.5.5_
  * Added much needed warning that high resolution thumbnails might crash phone. :(

_05/09-2010: 2.5.4_
  * Removed some initial multitouch code that crashed pre-2.1update-1 phones. Sorry about that.

_05/09-2010: 2.5.3_
  * More image speeds available.
  * Tweaks to lower memory usage.
  * Focused images look better.
  * Read Exif data on capable devices.
  * HD display errors fixed.
  * Minior language fixes.
  * Feeds should be added faster.
  * Error when rotating selected image fixed.

_18/08-2010: 2.5.2_
  * Fixed appearance bugs on manage feeds view.
  * Made it possible to view hidden files when selecting feed directory, through the menu.

_15/08-2010: 2.5.1_
  * Preventing the user from rewinding too far (about a screen length), as the images will just repeat.
  * Fix Picasa Album view.
  * Show who owns the seleted album in the feed manager.
  * The speed of the floating stream is now adjustable.
  * Small UI fixes here and there.

_08/08-2010: 2.5.0_
  * Manual image rotation
  * Improved image source management.
  * Option for high quality thumbnails
  * Image sharing (Share URL on online images).
  * Certain bugs killed.
  * High res launcher icon

_05/07-2010: 2.4.8_
  * Full Picasa support, login and all
  * Froyo App on SD-card support

_27/06-2010: 2.4.7_
  * Much improved Flickr support.

_19/06-2010 (30 minutes later): 2.4.6_
  * Thinking about it, the fix from the previous version introduced different bugs. Should be fixed now.

_19/06-2010: 2.4.5_
  * Strange image swapping bug fixed. Should also remove some memory leaks. Fun stuff!
  * Option whether details are shown is once again remembered.

_13/06-2010: 2.4.4_
  * Friend facebook support
  * Flickr authentication
  * Ability to sign out of facebook

_24/05-2010: 2.4.3_
  * Anti-aliasing!! (Requires Nexus One style hardware - Won't work on Magic)
  * Facebook support
  * Strange image swapping fixed
  * Samsung moment/spica bugfix

_19/05-2010: 2.4.2_
  * More bugfixes

_18/05-2010: 2.4.1_
  * Bugfixes

_17/05-2010: 2.4.0_
  * New On Screen Display
  * Optimizations for large display devices (Nexus One, etc)
  * General bugfixes
  * Somehow I broke Samsung support again. :(

_18/04-2010: 2.3.16_
  * Basic Picasa support added.
  * Swipe to move to next image added.

_10/04-2010: 2.3.15_
  * Larger images are used, scaled to screen size.
  * Shuffle is now actually used.
  * Changed settings strings.
  * Not adding local images to image cache (though this might be a good idea?)
  * Not restarting renderer every time you return from sub-activity.
  * More images can be set as background.

_09/04-2010: 2.3.13, 2.3.14_
  * Fixed rather nasty bugs, among which:

> - Splash screen time dependant on how stream search.

> - Image feeding bugs fixed.

_07/04-2010: 2.3.12_
  * Bug where no images appear fixed. You really should mail me about this, I cannot contact you if you just write something in the comments! :(

_07/04-2010: 2.3.11_
  * Minor restructuring to allow for different display modes.
  * Basic slideshow transitions implemented (still none for floating image)
  * You can now choose if your images should be shuffled or not.

_29/03-2010: 2.3.10_
  * Major restructuring of code to allow for more dynamic content.
  * Specific Flickr feeds supported.
  * 2MB+ images now supported (artificial cap removed)
  * Infobar etc now also fade out, not only in.

_21/03-2010: 2.3.9_

  * Per request the fullscreen option is now saved across sessions, so you no longer have to set it every time.

_21/03-2010: 2.3.8_

  * Fixed bug where info bar was repeated, when it spanned more than 512 pixels.
  * Fixed "show local folder" bug.

_24/02-2010: 2.3.7_

  * Nasty bug filling up the feeds fixed. Sorry about that.
  * Clear all button added to local feeds (This should have a warning - nothing now).

_16/02-2010: 2.3.6_

In the spirit of release early, release very very often:
  * Back button will deselect selected image. If no image is selected, default behavior (quit program).

_15/02-2010: 2.3.5_
  * Hopefully I have fixed some of the problems writing to a perfectly fine sd-card.
  * Version is now saved in preferences, so even if there's no sd-card the program should stop resetting constantly.

_14/02-2010: 2.3.4_

My brother insisted I enabled four axis rotation, so there you go...
  * Four axis rotation added. :)

_14/02-2010: 2.3.3_

I finally sqeezed in a small update. Oh, and Floating Image just reached 10.000 downloads!
  * Ability to save image to disk added.
  * Ability to set flickr image as background added. The same will happen for local images eventually.
  * (Hopefully) Better scrolling
  * Some performance adjustments.
  * Delay before rotating screen removed.

_06/01-2010: 2.3.2_

Bugfixes:
  * Image picking is now correct
  * Picking bug when resuming from viewing an image in horizontal mode.

_05/01-2010: 2.3.1_
  * Fixed fullscreen bug.

_05/01-2010: 2.3.0_

Happy New Year!
  * Full screen option added
  * Show folder option added (Show only folder, it will take a while for the folder to fill the entire stream)
  * Randomizing random photo stream.

_30/12-2009: 2.2.0_
  * Live rotation.
  * New splash screen and icon, courtesy Mikkel Gjøl (Same goes for creative input, shadows and background).
  * Support for running with no SD-card (Previously it crashed hard, now it warns the user, and is flaky).

_28/12-2009: 2.1.1_

Yeck! Another bug! I suck!
  * Control locks under certain circumstances when selecting an image.

_28/12-2009: 2.1.0_

Yeck! A bug:
  * Bug where images are displayed badly at startup removed.
  * Progress bar for loading images added.
  * Minor UI changes

_28/12-2009: 2.0.0_

I found time to do a little coding over a weekend, so finally some updates:
  * Multiple display sizes support, also horizontal mode.
  * Background changed from black.
  * Stream fades out when an image is selected.
  * Image information fades in.
  * Images now have shadows (Except for new images, they still glow).
  * Images are by default slighly more messy, by being rotated.
  * Images brought to focus using smoothstep rather than linear motion.
  * Local feeds (images on the phone) are now user definable.
  * General optimizations.

_Some time in early December_

Google/code page is up! This, after a month or two with no development (Travel / Lots of work). Hopefully this will change soon.