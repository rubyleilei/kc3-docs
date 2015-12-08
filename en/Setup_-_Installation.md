[en](https://github.com/KC3Kai/kc3-docs/tree/master/en) / Setup / [Installation](https://github.com/KC3Kai/kc3-docs/blob/master/en/Setup_-_Installation.md)

**Recommended option**
Just visit KC3改 on Chrome Webstore and click on the "Free" button at the top:

### [Visit on Chrome Webstore](https://chrome.google.com/webstore/detail/kancolle-command-center-%E6%94%B9/hkgmldnainaglpjngpajnnjfhpdjkohh)

**Requirements**

-   **Uninstall/Disable the old KC3!**
-   **Browser**: Just your [Google Chrome](http://www.google.com/chrome)
-   **OS**: Will work on any OS that supports Chrome/Chromium
-   **Device**: Will work on computers, *not confirmed for mobile*

**Other installation methods**
Please visit [Setup development build](https://github.com/KC3Kai/kc3-docs/tree/master/en/Setup_development_build.md "wikilink")for other methods of installation as well as basic usage of other methods.

FAQ
---

#### I got prompted to either allow or deny cookie installation when installing KC3 Kai

You **will** need to allow cookie installation when installing KC3 Kai extension. Failing to allow cookie installation can lead to all sort of errors with the extension.

See [here (kancolle.wikia.com link)](http://kancolle.wikia.com/wiki/User_blog_comment:Dragonjet/KC3%E6%94%B9/@comment-1.226.128.137-20150728133756?permalink=290776#comm-290776) for further information.

#### I can't see KanColle tab or the under KanColle tab it keeps showing "Waiting for game actions" when I am already in the game!

This might have to do with not allowing the cookie installation beforehand, see previous question (above). Alternatively you may want to follow this guide as one user writes it but it uses Chromium as opposed
to Chrome:

1.  Installed Chromium
2.  Made sure Chromium accepts third party cookies
3.  Imported dev build of KC3 Kai
4.  Edited DMM.com's region flag as outlined here [Tutorial: Proxy Connection (kancolle.wikia.com link)](http://kancolle.wikia.com/wiki/Tutorial:_Proxy_Connection)
5.  Restarted Chromium
6.  Opened DMM.com, used "Activate Cookies" option in KC3 Kai toolbar menu
7.  Used "Play on DMM site" option to run the game
8.  Opened Command Center, game ran, and Command Center worked.

I did basically the same thing with Chrome. The only other extension I'm using on Chrome is Adblock, which I installed before KC3 Kai It doesn't work on Chrome even after disabling Adblock though So my Chrome installation was basically fresh, too. It just didn't work on it for some reason I don't know It's working with API Links too. So everything seems to be in working condition.

#### Some of the features listed does not work when it used to work!
The first and often the best place to start is by temporarily disabling/removing the Chrome Webstore version of KC3 Kai and then installing the [developmental build](https://github.com/KC3Kai/kc3-docs/tree/master/en/Setup_development_build.md "wikilink").

Failing to find a resolve to your issue it is best to check on the [KC3 Kai issues tracker (on GitHub)](https://github.com/KC3Kai/KC3Kai/issues) first.

#### I get a NETWORK_FAILED error on Chrome Webstore

-   Make sure you are using the latest Chrome.
-   Temporarily disable any firewall you may have or add Chrome to the trusted list within your firewall configuration. *You may re-enable firewall immediately after installation.*
-   Make sure that your computer as well as your network is free of malwares.

#### Can I use other Chromium-based browser?

While other chromium-based browsers are not officially supported by the extension, you may still attempt to install it.

Not being officially supported doesn't mean it will have less features, it just means the development team is not responsible and is in no obligation to assist and answer questions in installing, using or even troubleshooting it.

Also, it is not guaranteed that bugs isolated to those unsupported browsers will be fixed nor will be given priorities.

Don't worry though, within reasonable means the development team may offer support. This is why the following FAQ question will already explain some of the basic thing you need to do.

#### How can I install this on other Chromium-based browsers?

It is recommended that other Chromium-based browsers use the development builds of KC3改. See this guide on how to set it up: [Setup development build](Setup_development_build "wikilink")
