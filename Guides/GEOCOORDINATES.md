# Getting the Geo-Coordinates
Geo-coordinates need to be manually provided by superusers or bar administrators for LineHop to know where the tavern is in relation to local LineHop users. You may do so by following these simple steps:

**A:** Know the mailing address of the bar.

For this example, we will use a Vancouver bar called "Sammy J's Grill & Bar". Sammy J's is located at _19925 Willowbrook Drive #101 V2Y 1A7_ in Langley, BC.

**B.** Open your preferred browser and go to https://maps.google.com.

**C.** Search for the bar you are looking for.

In our case, we are searching for "Sammy J's Grill & Bar Langley".

<img width="400" alt="screen shot 2015-08-26 at 2 16 24 pm" src="https://cloud.githubusercontent.com/assets/6799989/9494286/1275cc58-4bfd-11e5-84bc-1c58924c1782.png">

**D.** Click on the red location pin.

**E.** Copy the link from your browser.

Depending on the browser, the layout/process could be different. We are using Safari on OS X. You will need to click into the address bar, select the entire link (⌘+A) and copy it to your clipboard (⌘+C).

![figure 2](https://cloud.githubusercontent.com/assets/6799989/9494663/1b5fd1ea-4bff-11e5-84c9-557d889fd236.png)

**F.** Open a text document, paste the link and extract the longitude and latitude.

The link for Sammy J's looks like:

```text
https://www.google.com/maps/place/Sammy+J's+Grill+%26+Bar+Langley/@49.1184016,-122.673901,
14z/data=!4m6!1m3!3m2!1s0x5485d02cfa635309:0xa1108e3b4f7b55b1!2sSammy+J's+Grill+%26+Bar+Langley
!3m1!1s0x0000000000000000:0xa1108e3b4f7b55b1?hl=en
```

Look for the geo-coordinates (which will look like `@49.1184016,-122.673901`) but you will need to remove the "@" from the start.

**G.** Add the geo-coordinates to your tavern by following the "[How do I create a new Tavern?](https://github.com/linehop/guides/blob/master/CREATING-NEW-TAVERNS.md#how-do-i-create-a-new-tavern)" guide.

If you have any questions or concerns, please feel free to reach out to **[@istx25](https://www.github.com/istx25)** ([douglas@cosmiclabs.io](mailto:douglas@cosmiclabs.io)) or **[@damonjones](https://www.github.com/damonjones)** ([damon@cosmiclabs.io](mailto:damon@cosmiclabs.io)).
