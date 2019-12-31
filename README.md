Long, Wide Data and How to Efficiently Plot Them
================
Jun
Dec 22, 2019

Introduction
------------

Often times when we deal with data, it comes with different formats. If you scrapped the data from a website, likely it is in wide format. In fact, most data we physically see is in this format, since wide data is very intuitive and easier to understand. One good example would be this [NBA stat page from ESPN](https://www.espn.com/nba/stats/player/_/table/offensive/sort/avgPoints/dir/desc).
On the other hand, long format data is less often to see. However, it has it’s own advantages like:
- fast processing (using vectorized operation)
- required by certain advanced statistical analysis and graphing

In this repo, I’ll show how to transform the data between the two formats, how is long format faster to process, and how to efficiently plot each format. We will use the monthly precipitation data for San Francisco and Sacramento as our examples.

You can also see the tutorial [here](https://towardsdatascience.com/long-wide-data-and-how-to-efficiently-plot-them-7a96887e309d?).
