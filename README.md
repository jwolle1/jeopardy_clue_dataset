## jeopardy_clue_dataset

<p align="center"><img src="images/jeo_logo.jpg" alt="Jeopardy! Logo" /></p>

This dataset contains _Jeopardy!_ clues from Season 1 through Season 38 (July 2022). It does not contain every clue that has appeared on the show. The data source prefers not to be credited.

There are 453,953 clues in total. They can be found in `combined_season1-38.tsv`. Note that the file is zipped. When uncompressed it is approx. 66 MB.

There are also individual files for each season (located in the `seasons` folder). These files are small enough that you should be able to open them with Microsoft Excel or Google Sheets.

* Seasons 1-11 average 8,739 clues each.
* Seasons 12-38 average 13,253 clues each.

There is a `kids_teen.tsv` file which contains only clues that appeared in Kids and Teen Tournament matches.

There is a separate `goat_tournament_jan2020.tsv` file which covers the Jennings-Holzhauer-Rutter event.

I've done my best to clean the data and filter out clues that depend on images, video, or audio.

---

**Column Information:**

Label | Description
:--- | :---
_round_ | _1_ for Single Jeopardy, _2_ for Double Jeopardy, or _3_ for Final Jeopardy.
_clue_value_ | The clue's value on the board before any Daily Double wagering.
_daily_double_value_ | If the clue is a Daily Double, this column is the amount wagered. Otherwise it's zero.
_category_ | i.e. the top row of the board.
_comments_ | The host's comments about a category.
_answer_ | The prompt given to contestants.
_question_ | The correct response.
_air_date_ | The calendar date on which the episode first aired.
_notes_ | Misc. information about the clue, e.g. whether it was a special tournament match.

---

All data is property of Jeopardy Productions, Inc. and protected under law. I am not affiliated with the show. Please don't use the data to make a public-facing web site, app, or any other product.
