KC3改 offers **on-screen quest translations** for players using [Play via API link](https://github.com/KC3Kai/kc3-docs/tree/master/en/Gameplay_-_API_Link.md "wikilink").

How it works
------------

![KC3改 Translations](https://github.com/KC3Kai/kc3-docs/blob/master/_img/KC3KaiTranslations.jpg)

#### Process

-   Chrome notifies KC3 Kai of HISTORY entry containing Quest data
-   [Panel](https://github.com/KC3Kai/kc3-docs/tree/master/en/Panel.md "wikilink") notifies main KC3改 script, `background.js`
-   `background.js` notifies the HTML page of Quest IDs
-   The HTML page's JavaScript will get info about those quests from our local `quests.json` file
-   The HTML page's JavaScript will show POP-UPs (yes like popup ads) containing English or otherwise your preferred language texts in the correct location on the screen to match the placement of the in-game texts

FAQ
---

#### Is this bannable?

**No**. Just make sure you don't go doing screenshots and flailing around your translated picture with your HQ name.

Some people even fear doing screenshots with the viewer interface itself, and this not just applies to KC3改. Yes, they even fear taking screenshots having KCV container. It's better safe than sorry.

If you really want to share screenshots, edit the picture and blur out your HQ name. But technically speaking, if you play naturally, it's **100% safe**.

#### I have KC3改 installed but I don't see quest translations

-   By default, it's disabled. [turn it on](http://github.com/KC3Kai/kc3-docs/tree/master/en/Settings.md "wikilink").
-   It **only** works on [Play via API link](https://github.com/KC3Kai/kc3-docs/tree/master/en/Gameplay_-_API_Link.md "wikilink").
-   It **also only** works if [F12 Panel / Admiral Dashboard](https://github.com/KC3Kai/kc3-docs/tree/master/en/Panel.md "wikilink") is on.

#### Some quests are not translated

It must be a new quest, wait for next version.

#### Why only translate quests, not anything else?

Quests can be translated because there is an API call each page you open. This is how the extension gets aware with what you are viewing.

The said API call contains the list of Quest on that current quest page, thus we can show overlays with corresponding translations.

However, browsing through pages of ships and equipment doesn't have API calls. This means that the extension does not know what you are currently viewing, therefore cannot put ship and item translation overlays on the screen like how it does with quests.
