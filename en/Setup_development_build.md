Can't wait for the next version? Want to use the latest build as the developers/beta testers? You have the option to do this by following simple instructions below. There are also multiple options depending on how familiar you are with tools. Don't worry though, there's a way for even the basic layman.

The system **requirements** would be the same as the WebStore version of KC3改, [you may review it here](Installation "wikilink").

**Note:** Due to the fact that both the development build as well as the stable build shares virtually similar icons and what not. It is **advisable** should you use/alternate between development and stable build that you disable one before enabling the other. Otherwise you may confuse yourself as to which one you are currently using or wonder why certain things are incorrect/not functioning as intended.

Step 1: Download
----------------

#### Option: Zip Releases

Zip releases are available [here](https://github.com/dragonjet/KC3Kai/releases). From time to time when certain [milestones](https://github.com/dragonjet/KC3Kai/milestones) are
reached, newer zip releases will be made available for download.

Note that zip releases are not necessarily identical to development builds as they are a "snapshot" of development build once it has reached a certain milestone but may share same ID as development build as opposed to stable (webstore) build.

#### Option: Zip Download (Deprecated, no longer recommended)

1.   [Download](https://github.com/dragonjet/KC3Kai/archive/master.zip) the ZIP file from the [front page of KC3 Kai github](https://github.com/dragonjet/KC3Kai).
2.   Extract the contents of the ZIP file into your preferred directory/folder.
3.  Go into your Chrome browser &gt; menu bar located on the right-hand part of the toolbar with an icon representing 3 horizontal layers &gt; More tools &gt; Extensions.
4.   Check the box labelled "Developer mode" located on the right hand upper part of the window.
5.   Click on "Load unpacked extension".
6.   When prompted to "Select the extension directory/folder", navigate to where you extracted the contents of the zip file but under the directory/folder labelled src.
For instance, if you extracted into \\Downloads\\KC3Kai\\ then you should point the extension directory/folder as \\Downloads\\KC3Kai\\src

#### Option: Git Cloning

If you have knowledge with git, you can clone the repository onto your
computer:

-   Get Clone URLs from [KC3改 GitHub](https://github.com/dragonjet/KC3Kai)
-   Also do submodule update as mentioned [here](https://github.com/KC3Kai/KC3Kai/issues/784#issuecomment-139556574).

#### Option: TortoiseGit

If you do not have knowledge with git, but still want the bleeding edge of KC3改, you may use software like **TortoiseGit** to assist you.

1.   [Download and Install git](https://git-scm.com/downloads)
2.   [Download and Install tortoisegit](https://code.google.com/p/tortoisegit/wiki/Download)
3.   Create the directory where you want your latest KC3改 to go.
4.   Get Clone URLs from [KC3改 GitHub](https://github.com/dragonjet/KC3Kai)
5.   Go inside your KC3改 folder, right-click, Select **Git Clone**
6.   Paste the Clone URL into the **Git Clone** prompt
7.   Wait for cloning process to complete
8.   You will need to also do submodules update, see [here](https://github.com/KC3Kai/KC3Kai/issues/784#issuecomment-139554087) for instructions.

Step 2: Install
---------------

1.   On your Chrome: **Chrome Menu** &gt; **More tools** &gt;
    **Extensions**
2.   Check "Developer mode" located on the top-right
3.   Click on "*Load unpacked extension*"
4.  Browse inside you local KC3改 folder and select the sub-folder: **/src**
5.   The gold heart icon will appear on your Chrome, and you can start testing

FAQ
---
#### When I used the git/development build of KC3 Kai I see no words besides the icon within the KC3 Kai menu, clicking on them does not do anything!

When using development build of KC3 Kai (since circa version 19), translations for various KC3 Kai related items have been moved to another project and therefore breaks the ZIP builds downloaded from GitHub. This does **not** include [tagged releases](https://github.com/dragonjet/KC3Kai/releases) which are technically ["grunted"](https://www.npmjs.com/package/grunt) builds and would thereby include translations.

**For users who do not wish to use a proper git software**
Please use [tagged releases](https://github.com/dragonjet/KC3Kai/releases) but do note that any tagged releases are generally older than the bleeding edge releases found when using the actual git software.

**For developers**
You will need to:
````
git submodule update --init -- "src/data/lang"
````
For developers not familiar with CLI git commands please refer to your git software documentation.

As mentioned [here](https://github.com/KC3Kai/KC3Kai/issues/866#issuecomment-140267548) as well as [here](https://github.com/KC3Kai/KC3Kai/issues/784#issuecomment-139556574).


#### What are the differences between WebStore, Zip, and GitHub versions?

**Chrome WebStore** releases are usually stable builds, and is the one **recommended** for normal players. This is also a signed copy of KC3 Kai that the lead developer has wished to release to the public.

The following below are **unsigned** copies of KC3 Kai which means they require a different method of installation as well as maintaining/updating.

As a result, any use of variants listed below are your responsibility to maintain that your version of KC3 Kai is up to date as developers may elect to either support it or not.

[**Tagged** releases](https://github.com/KC3Kai/KC3Kai/releases) are basically the same as Chrome Webstore builds except without the lead developer's signature.

Users having trouble getting KC3 Kai from Chrome WebStore and/or does not want their KanColle game session closing tab whenever there are new updates for KC3 Kai are being made available may wish to install and use this variant.

[**Master.zip** versions](https://github.com/KC3Kai/KC3Kai/archive/master.zip) are development builds for those keen on trying out the latest version but does not want to deal with git.

They usually include features/changes that are not yet included on Chrome WebStore versions, either because these updates are unstable or otherwise testing. That means, it might include some bugs, but that's the reason for zip releases - public testing and getting feedback.

Be prepared for some hair pulling moments when and if you go use the experimental builds.

**GitHub** versions are the latest (bleeding edge) in KC3改 development. *Not recommended* for the faint of heart.

Each code update the developers do, either minimal or major, is usually pushed to git. Users of git versions can optionally "pull" any time and these updates becomes available on their computers. These users are the first to see anything new on the extension.

The problem with this is that codes are usually not fully tested and there's a significant chance they come with bugs.

#### Why are there two ways of installing "GitHub" version of KC3 Kai?

Installation via [ZIP file](https://github.com/KC3Kai/KC3Kai/archive/master.zip) is intended to prevent much confusion for those unfamiliar with how git works and prefers to just install the viewer as it is. 

**However**, at the expense of this should the user prefers to keep updating the copy of the "GitHub" version of KC3 Kai **via** ZIP file it is preferred to use tortoisegit for instance.

Installation via tortoisegit is a little complex at first but potentially makes life easier for the user to keep up-to-date with the latest git revisions of KC3 Kai.

#### My user profile from "Webstore" build is missing in "GitHub" build (or vice versa). Help!

This is as expected due to the fact that both of these builds have completely different ID and hence are stored in different directories/folders respectively.

#### If I install "GitHub" build of KC3 Kai, am I obliged to provide feedback to the developers in any way?

No, it is not a necessity to help out the developers **however** it does help should you offer feedback as the developer version of KC3 Kai offers experimental features not found in the stable build offered in the Google Webstore.

Besides, you may help "shape" the future of what KC3 Kai is to look like.

#### Are there any particular risks with using the "GitHub" build of KC3 Kai as opposed to using the "Webstore" build?

No, however bugs maybe apparent within the "GitHub" build and so long as you are aware of that, that is all it matters.

#### How do I debug KC3 Kai?

1.   Once you have KC3 Kai opened up, pop the KC3 Kai into a [separate window](http://stackoverflow.com/questions/20220090/undock-chrome-developer-tools).
2.   Once you have KC3 Kai popped out into a separate window, press Ctrl+Shift+I (which is the same as opening the developer tools itself).
3.   The title of KC3 Kai debug window should be something like:
`Developer Tools - chrome devtools://devtools/bundled/devtools.html &remoteBase=https://chrome-devtools frontend.appspot.com/serve\_file/@196519/&can\_doc=true&dockSide=undocked&toolbarColo`
4.   Go into the Console tab.
5.   Optionally you may also want to look at installing [Chrome Apps & Extensions Developer Tool](https://chrome.google.com/webstore/detail/chrome-apps-extensions-de/ohmmkhmmmpcnpikjeljgnaoabkaalbgc?utm_source=chrome-app-launcher-info-dialog)

#### How do I distinguish whether or not I am using the development build of KC3 Kai or not?

Normally the stable or otherwise known as "webstore builds" can only be obtained from Google webstore and are not available in for instance a zip file. Webstore builds are signed versions of KC3 Kai authored by Dragonjet and usually contains the file extension prefix .crx.

There are other tell tales:

1.   The icon for developmental version of KC3 Kai looks like a solid yellow golden color as opposed to the one featured in the Chrome WebStore.
2.   When playing via API link and when navigating to the KC3 Kai panel it is clearly lablled as "DevKC3Kai".
3.   Under extensions with development builds you will see there is an extra line indicating where it is loaded from, e.g.
    `Loaded from: ~/KC3Kai/src`
3.   The development build will have a different ID compared to stable build. Hence this is the same reason as above for why details of your historical involvements such as resources, crafting and what not would be gone as they are stored in a different location and are not shared.