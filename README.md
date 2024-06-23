## Operation Haystack by Frank Herbert (24721) ##

This is an [errata report][1] for a [Project Gutenberg][2] EBook.

[1]: https://www.gutenberg.org/help/errata.html
[2]: https://www.gutenberg.org

"Operation Haystack" by Frank Herbert

- [Project Gutenberg listing][3]
- [DP project page][4]

[3]: https://www.gutenberg.org/ebooks/24721
[4]: https://www.pgdp.net/c/project.php?id=projectID4691749c38689

Assigned ID `[errata #17666]`

### Corrections

```
Operation Haystack, by Frank Herbert
    March, 2008  [EBook #24721]

    EPUB version:
        Page numbers are not hidden in the EPUB file like they should be.
        Some page numbers are even inline in the middle of sentences.
        The file uses ".pagenumber" CSS, not known to ebookmaker.

        Can be fixed by adding the below CSS to HTML. I tested this both
        in browsers (page numbers display properly) and building EPUB with
        online ebookmaker at PGLAF (page numbers are properly hidden).

        .x-ebookmaker .pagenumber { display: none; }

        Screenshots showing the problem in EPUB available here:
        https://github.com/tangledhelix/DP_haystack_errata

    Txt version (line 186), HTML version (line 416):
        she gasped as she opened his sole remaining eye, said
            2nd "she" should be "he"
```
