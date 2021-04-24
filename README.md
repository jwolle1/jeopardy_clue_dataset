## jeopardy_clue_dataset

This dataset contains _Jeopardy_ clues from Season 1 through 
Season 36 (June 2020). It does not contain
every clue that has appeared on the show. The data source prefers 
not to be credited.

There are 376,266 clues in total. They can be found in `combined_season1-36.tsv`.

There are also individual files for each season.

* Seasons 1-12 average 5,088 clues each.
* Seasons 13-36 average 13,134 clues each.

There is a `kids_teen.tsv` file which contains only clues that appeared in Kids and Teen 
Tournament matches.

There is a separate `goat_tournament_jan2020.tsv` file which covers the Jennings-Holzhauer-Rutter event.

Note that `combined_season1-36.tsv` is zipped. When uncompressed it is approx. 56 MB.

---

**Column Labels:**

* _round_
  * 1 for Single Jeopardy
  * 2 for Double Jeopardy, 
  * 3 for Final Jeopardy.

* _value_ – The clue's value on the board. If the clue was a Daily
Double, this column will be the wagered amount.

* _daily_double_ – _yes_ or _no_.

* _category_

* _comments_ – Usually this contains the host's comments about the
category. Sometimes other misc. information is found here.

* _answer_

* _question_

* _air_date_ – The calendar date on which the episode first aired.

* _notes_ – Indicates whether a clue appeared in a special tournament
match.

---

All data is property of Jeopardy Productions, Inc. and 
protected under law. I am not affiliated with Jeopardy Productions, 
Inc. Please don't use the data to make a public-facing web site, app, 
or any other commercial product.