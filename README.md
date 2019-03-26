# grp-documentation
Documentation for Go Review Partner

+ [English](doc/documentation_en.md)
+ [polski (Polish)](doc/documentation_pl.md)

To build an HTML page with `pandoc`, run:

    L=pl && [ -d html ] || mkdir html && pandoc -s --toc doc/documentation_"$L".md -o html/grp_doc_"$L".htm
    
Change the language code in `L=pl` into one you desire, eg. `en`.
