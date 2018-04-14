Here are several [JabRef](https://www.jabref.org/) [custom export filters](https://help.jabref.org/en/CustomExports) that

- converts (all or part of) [BibTeX](http://www.bibtex.org/) (.bib) files opened in JabRef
- to a HTML page with a list of references and builtin quick search.

The code is based on <https://bitbucket.org/MarkSchenk/jabref-export>.
The main differences are in the `listrefs` filter:

- Reference items are more conformant to the [IEEEtran](https://www.ctan.org/pkg/ieeetran) style.
- Use HTML `<ol>` list instead of `<table>` to format the list of reference.

License: [Creative Commons Attribution 3.0 License](https://creativecommons.org/licenses/by/3.0/)
