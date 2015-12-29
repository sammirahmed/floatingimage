# <a href='https://market.android.com/details?id=dk.nindroid.rss'>Floating Image</a> #
Floating Image streams images from the web as well as from the device and displays them in a continuous stream of floating images across the display. A close Floating Image derivative is featured on the [Archos](http://archos.com/) 70 and 101 tablets as Photo Frame.

Developers: If you find this an enticing project feel free to contact me about continuing it, as I don't seem to get much work done on it these days.

**If you experience problems, PLEASE PLEASE PLEASE contact me, otherwise they will most probably remain!**


---


If you feel compelled to donate some of your money, this is now also possible. It won't make me work more though, as I'm already very dedicated to this project - in fact, I might work less, as I'll be out spending your hard earned cash. However, I will appreciate it!

<p>
<a href='https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=ZV6XZZ9WEX426&lc=DK&item_name=Floating%20Image&currency_code=DKK&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted'><img src='https://www.paypal.com/en_US/i/btn/btn_donateCC_LG.gif' /></a>

Please note that if you donate $1 Paypal will deduct 60%, if you donate $2 they will deduct 30%. I greatly appreciate the 40 cent I <i>will</i> receive, but in that case it might be better for you to find some friends who also want to support me - or to hope we'll meet at some point, and then buy me that beer (Please don't send it with the postal service, it's a horrible mess when I open it).<br>
</p>

---

### Recent activity: ###
_11/02-2011: 3.4.13:_
  * Fixed random crash.

_11/02-2011: 3.4.12:_
  * Show images from emails should work.
  * Fixed 500px bug when attempting to show a user's images.

_01/02-2011 (ish): 3.4.11:_
  * Read SMS permission added. I'm not spying on you! Floating Image needs this to read images from smssmsms'es!
  * Basic Photobucket added
  * RSS added
  * Option to choose where to save
  * Bug where images were saved in the same file fixed
  * A couple of other bugs fixed.

_17/01-2011: 3.4.10:_
  * Floating Gallery can open images from more places
  * Smooth jump on zoom out
  * Bugs fixed

_25/12-2011: 3.4.8, 3.4.9:_
  * Bugfixes

_24/12-2011: 3.4.7:_
  * 500px support!
  * Option to use all subfolders for a feed, autoinclude new ones.
  * A few minor bugs fixed.

_19/12-2011: 3.4.5:_
  * Fix bug where pictures weren't always shown, when returning to Floating Image.
  * Fixed a crash
  * Only subscribe to image files, not all images (like content://url)

_18/12-2011 - even later: 3.4.3, 3.4.4_
  * Crash on new installs fixed. <-- The cause of the update!
  * Bounce back when zooming added.
  * Initial feeds activated properly

_18/12-2011 + 30 minutes: 3.4.2_
  * Yet another Crashfix

_18/12-2011 + 45 minutes: 3.4.1_
  * Crashfix
  * When swiping, you cannot select an empty image.

_18/12-2011: 3.4.0_
  * Improvements to the gallery
    * Feeds are managed from the start screen
    * The gallery images no longer wrap around.
    * The gallery can be launched by clicking on images.
  * File browsing is changed to hopefully be less confusing.
  * Which subfolders to include when adding a local feed can be selected.
  * A warning is issued if no images are being showed (except for in wallpaper mode)
  * Pinch to zoom fixed on tablets.

_05/12-2011: 3.3.1_
  * Bugfix

_04/12-2011: 3.3.0_
  * Gallery mode moved to a separate launcher.
  * Selected image fades to high resolution.
  * When selecting next image in gallery, stream follows.
  * Sorting can be selected for each feed (name, date, random)
  * Auto select mode added (Not yet in live wallpaper)
  * Feeds can be renamed.
  * Backgrounds updated to 32bpp
  * Bugfixes.
  * Bugs (I'm sure, do tell)

_A few bugfixes between these releases_

_29/10-2011: 3.2.0_
  * New gallery mode added.
  * Image loading is different which should resolve a LOT of memory issues!
  * Images no longer repeat themselves. (Woo!)
  * Slow loading images fade in. (More woo!)
  * Selecting/deselecting is now a single click. Double click yields the menu.
  * No longer supporting Android version 1.5. Actually this was in the last release, but I overlooked that. Oops!

_A bunch of updates didn't make it to this site_

_08/05-2011: 3.0.1_
  * New movement: Mixup. A mix of the other modes, changing every other minute.
  * New languages: Russian, Korean, German, Spanish, Danish.
  * New Flickr feed: My favourites.
  * Mandatory bug fixes.

_23/04-2011: 3.0.0_
  * New movements modes:
    * Either direction
    * Hyperspeed
    * Stack
    * Tabletop
  * Delete image - after many requests, and even a donation.

_07/04-2011: 2.8.12_
  * Fixed live wallpaper / app issue when using all black background.

_05/04-2011: 2.8.11_
  * If no "local" images are found, retry every 30 seconds (lowered from 120)
  * Graphical bugfixes
  * Available for all to play! (If you didn't have live wallpaper, no fun for you)

_21/02-2011: 2.8.10_
  * More bugfixing.

_20/02-2011: 2.8.9_
  * Fix bug in caching showing the wrong images.
  * Slight memory optimization.
  * Small internals reworking, doing things the right way.

_09/02-2011: 2.8.8_
  * Fix Flickr sign-in bug (it was accidentally disabled).

_01/02-2011: 2.8.7_
  * Wallpaper and App no longer share selected image sources.

_01/02-2011: 2.8.6_
  * Live wallpaper rotations dependant on chosen screen, rather than touch movement.
  * When local feed appears empty, feed is refreshed in two minutes (Good for when sdcard is not ready). (Same as previous version, but now I tested it...)
  * A couple of bugfixes


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

### Language support ###
  * Danish
  * English
  * German (Philipp Forsbach)
  * Korean (Anonymous)
  * Russian (Руслан Айнетдинов)
  * Spanish (Rodolfo Hurtado)
  * Czech (Jan Matys)


---

### About ###
Floating Image is a spare time project to get some experience coding for mobile devices in general and the Android platform in specific. This has two large impacts on the project:

1. Development happens when I find the time, which can vary from every day to not at all.

2. The plans for the project are not set in stone, so if you have a really cool idea, I just might go for it.

Screenshots and Market info at <a href='https://market.android.com/details?id=dk.nindroid.rss'>Google Market</a>.

### Future plans: ###

  * More image sources:
> - Stumpleupon

> - Google search

> - Webshots

> - rss

  * ~~Share images.~~ Tag several images, and share batch.

### On hold: ###
  * Screen lock replacement. (This has been requested time and again, but it seems Google is not too fond of letting people replace the screen lock. Because of this, I have decided to put this on hold, until I run out of ideas for other stuff I can shove into the program.)