# jeopardy_clue_dataset

This dataset contains jeopardy clues from Season 1 through the end of
Season 35. It does not contain every clue that has appeared on the
show. The data source prefers not to be credited.

There are 349,641 clues in total. They can all be found in 
*master_season1-35.tsv*. There are also files for each season. 
Seasons 13 and later contain 12,000 to 14,000 clues each. Seasons 12 
and earlier contain fewer. There is also a *kids_teen.tsv* file 
which contains only clues that appeared in special Kids and Teen 
Tournament matches.

Note that *master_season1-35.tsv* is zipped. When uncompressed it
is approximately 51.0 MB.

<br />

---

**Column Labels:**

- *round* – *1* for Single Jeopardy, *2* for Double Jeopardy, 
*3* for Final Jeopardy.

- *value* – The clue's value on the board. If the clue was a Daily
Double, this column will be the wagered amount.

- *daily_double* – *yes* or *no*.

- *category*

- *comments* – Usually this contains Trebek's comments about the
category. Sometimes other misc. information is found here.

- *answer*

- *question*

- *air_date* – The calendar date on which the episode first aired.

- *notes* – Indicates whether a clue appeared in a special tournament
match.

---

<br />

All data is the property of Jeopardy Productions, Inc. and 
protected under law. I am not affiliated with Jeopardy Productions, 
Inc. Please don't use the data in making a public-facing web site, app, 
or any other public product.
