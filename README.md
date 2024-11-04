# listal2letterboxd

Many years ago, I used a site called [Listal](https://www.listal.com/) to
track the films I watched.

I gave up using it in 2019 as it looked like the site was getting no love
from its owners and it seemed likely to stop working before too long. I
switched to [Trakt](https://trakt.com/) and, more recently,
[LetterBoxd](https://letterboxd.com/).

I always knew that at some point, I'd want to go back and see if it was
possible to export my data from Listal and import it to LetterBoxd.

That day is today.

Exporting the data was easy enough. If you're logged into Listal and go to
[listal.com/user/export](https://www.listal.com/user/export), you can get an
XML file containing all the data you need.

And if you go to
[letterboxd.com/about/importing-data/](https://letterboxd.com/about/importing-data/)
you can see a few options for importing that data. The simplest option seems
to be to produce a CSV file.

So that's what this code does. It reads the Listal export file and produces
the CSV import file that LetterBoxd needs.

I'm [realdavorg](https://letterboxd.com/realdavorg) on LetterBoxd.
