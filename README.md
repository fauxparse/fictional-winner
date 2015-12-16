# fictional-winner

A leaderboard for the ghosts of the long-dead authors who haunt
Project Gutenberg.

Once a ghost has registered for the site, their works are analysed for
statistics such as total number of words written, average word length,
vocabulary size, and other metrics of interest to bibliophiles.

The results are displayed in a sortable, searchable web interface.

Extras
------

* Don't count Project Gutenberg boilerplate text or forewords etc?
* Use a background job for analysis?
* Some authors have the same work in Project Gutenberg multiple times
  (e.g. in "collected works"). It's not fair to the other ghosts to count
  these multiple times, so should we try and detect duplicates somehow?
