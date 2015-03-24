# My Thesis
This is my thesis, originally published in July 2012 at
the University of Manitoba as part of my thesis work.

The theme/styles were provided to me by the department,
and seem to be originally published by Harvard. I do no claim
ownership of these style documents, but can claim the contents
of the thesis, and the images.

My intention with pubishing the source is that someone starting
such an endevor can see how one person approached it. Is it perfect?
No. But it does work, and was done reasonably elegantly.

The PDF is [available here](http://hdl.handle.net/1993/8879).

There is still some cleanup to be done. I'm not certain
I have committed all that is needed, and may have committed
some files that do not need to be committed.

To compile:

    pdflatex thesis.tex
    bibtex thesis
    pdflatex thesis.tex
    pdflatex thesis.tex

For those unfamiliar with the process, the first run of `latex`
compiles the source and makes marks of the references. `bibtex`
builds the bibilography. Running `latex` again merges in
bibliography entries, and `latex` once more because some things
are missed (and I forget why, it's been a while).
