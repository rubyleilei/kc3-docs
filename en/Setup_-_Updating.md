[en](https://github.com/KC3Kai/kc3-docs/tree/master/en) / Setup / [Updating](https://github.com/KC3Kai/kc3-docs/blob/master/en/Setup_-_Updating.md)

Chrome extensions update automatically. So in general, you do not need to worry about updating. However, you should be aware of when they happen so you can adjust your timings.

The common problem with auto-update is that it restarts automatically. You do not want this to happen and your game close when you're nearing a boss kill! Avoid going on sortie during expected update times.

Starting **Version 006**, KC3改 checks for the latest version when you open the menu (the gold heart icon). At the bottom of the menu, it will either tell you "*You are using the latest version!*", or if the next version is nearing its scheduled publish, it will become a countdown timer. This will tell you how much time left before next release.

Procedure
---------

1.  Check if there is a new version on the KC3改 menu
2.  If there is, wait until countdown
3.  If its done and says a new version is ready, check for announcements:
    -   [Facebook](https://www.facebook.com/dragonjetmkii)
    -   [Twitter](https://twitter.com/dragonjetmkii)
4.  Once it's announced, end your kancolle session if you are still playing with it via KC3 Kai.
5.  Go to the Chrome's extensions page
6.  Check the "Developer Mode" tickbox
7.  Click on "Update extensions now" button
8.  Wait until KC3改 restarts (Make sure you are not mid-sortie)
9.  Sometimes, if we ask for additional permissions from your Chrome or otherwise it will become disabled. You just need to re-enable them and allow new permissions, but **do not re-install** it.

FAQ
---

#### I'm using another Chromium-based browser, how do I update?

Generally, we recommend non-Google Chrome browser to use [development builds](Setup_development_build "wikilink"). The guide is below.

#### I'm using development build, how do I update?

You shouldn't worry about WebStore releases if you're on development build though. To update your source, simply do a `git pull`, or if not using git, re-download the master zip from the [project home page](https://github.com/dragonjet/KC3Kai).

#### There's a new version, the KC3改 menu still showing I'm on latest

It must be cache. Do not clear your cache though. Just follow the steps in the **Procedures** above. Once you're updated, the KC3改 menu will fix itself regardless of cache.
