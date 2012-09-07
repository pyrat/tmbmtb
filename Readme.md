
# TMB MTB

 This is a travel guide covering tour de mt blanc on a mountain bike.

## Authors

 - Alastair Brunton ([simplyexcited](http://simplyexcited.co.uk))

## Formats

 In TMBMTB the markdown files provided in `./chapters`, which can then be converted to several output formats, currently including _pdf_, _mobi_, _epub_ and of course _html_.

## All Formats

    $ make

## PDF

Required by `make book.pdf`:

    $ brew install htmldoc
    $ make book.pdf

## HTML

Required by `make book.html`:

    $ gem install ronn
    $ make book.html

## EPUB

Required by `make book.epub`:
Requires [Calibre](http://calibre-ebook.com/)

    $ make book.epub

## MOBI

Required by `make book.mobi`:
Requires [Calibre](http://calibre-ebook.com/)

    $ make book.mobi