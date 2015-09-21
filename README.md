# A browser for your PDFs documents using bibtex

Tired of chosing the right filenames for your PDF documents? Or do they get too
long because they have to contain the title and the full author list?
`rofi-bibbrowser` solves all those problems!

## Behaviour

Initially, you are presented a menu containing an item for each entry of your
bibtex file and containing all PDFs of your document directory that could not
be associated to a bibtex entry. Bibtex entries with an associated PDF file are
indicated by the `[PDF]` marker.

![Screenshot]
(screenshots/main-window.png)

If you select a bibtex entry that has at least one PDF associated to it, it
will open that PDF. Otherwise, it will ask you for the PDF document for that
bibtex entry.

![Screenshot]
(screenshots/linking-window.png)

Selecting the corresponding PDF document will rename it to a canonical filename
and open it afterwards.


## Configuration file
The configuration file is just a python script and located at
`~/.config/rofi-bibbrowserrc`. You can overwrite any function that has been
defined before and adjust it to your needs.
