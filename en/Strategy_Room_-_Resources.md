Resources page shows a snapshot of your resources at specified intervals and plots them out on a graph over specified intervals. The following notes for the three graphs are as follows:

-   **Over the past day (per hour)**
    -   **NN:** Noon (12:00pm or 1200hrs)
    -   **MN:** Midnight (12:00am or 000hrs)
    -   The formats are indicated in 12hours
-   **Over the past week (per 6 hours)**
    -   The formats are indicated in 24hours
-   **Over the past month (per day)**
    -   The formats are indicated as Month/Day

You can hover your mouse over each of the nodes (as indicated as dots on the graph) to see your resources at a certain point when KC3 Kai captured the details of your resources.

####FAQ:
**Question:** Why are my resource history showing 0?
**Answer:** Make sure that:
- you're not just starting out to play with KC3 Kai.
- [you're using a proxy such as ShimakazeGo.](https://github.com/KC3Kai/KC3Kai/issues/868)
- your IndexDB is not showing 0 for any of the fields listed under the developer notes below.

Once made sure that none of those fits your case then you may wish to file an issue with the developers.

**Developer notes:**

-   Database is accessible via: Ctrl+Shift+I &gt; Resources &gt; IndexedDB &gt; KC3 - chrome extension &gt; resource

