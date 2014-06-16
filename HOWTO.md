HOWTO
=====

Grab yourself a copy of death-on-taurus.html. This is the master file.
Then download Calibre:

    http://calibre-ebook.com/download
  
Run:

    ebook-convert death-on-taurus.html death-on-taurus.epub \
    --cover death-on-taurus-cover.jpg \
    --author-sort "Porup, J.M." \
    --authors "J.M. Porup" \
    --language English \
    --title "Death on Taurus" \
    --title-sort "Death on Taurus" \
    --preserve-cover-aspect-ratio
  
or if you're a Kindle user:

    ebook-convert death-on-taurus.html death-on-taurus.mobi \
    --cover death-on-taurus-cover.jpg \
    --author-sort "Porup, J.M." \
    --authors "J.M. Porup" \
    --language English \
    --title "Death on Taurus" \
    --title-sort "Death on Taurus" \
    --prefer-author-sort
    
    ebook-convert death-on-taurus.html death-on-taurus.pdf \
    --cover death-on-taurus-cover.jpg \
    --author-sort "Porup, J.M." \
    --authors "J.M. Porup" \
    --language English \
    --title "Death on Taurus" \
    --title-sort "Death on Taurus" \
    --paper-size a4 \
    --pdf-add-toc \
    --pdf-page-numbers \
    --preserve-cover-aspect-ratio \
    --margin-bottom 72 \
    --margin-top 72 \
    --margin-left 72 \
    --margin-right 72

Calibre's full command-line interface is documented here:

  http://manual.calibre-ebook.com/cli/ebook-convert.html

