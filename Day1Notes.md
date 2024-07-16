# Notes from the Moderated Problem Session

1. Worksheets:
    - From a book with worksheets or activities, extract a "workbook".  It might have alternate frontmatter, but it should also have links to the original source.
    - Currently the activities element does not allow `@workspace`, maybe it should?
    - There should also be "stand alone" worksheets.

2. "Standalone" as a way to compile a fragment, and ignore the preamble when in a large document.  (Can this be managed by "versions"?).  Related, an *Overlay* journal: material wrapped around a paper that appears elsewhere.

3. Worksheets as print with workspace or online interactive exercises.  (Also good to print these, but online, they do not need blank space.)

4. Syllabus: What is a syllabus?  Need many more tags!

5. Worksheet: what is a worksheet?  e.g., Name, grade/marking

6. We need to get straight what all these things are:
    - article
    - worksheet
    - handout
    - exam
    - quiz
    - memo
    - letter
    - standalone
    - laboratory
    - slideshow

7. User experience: single source file document that is easy to share.

8. Landing page (this sort of exists, but it could be better).

9. Using a journal style on your latex (this could go in the publisher file).  What is the `\documentclass{?}`, a journal `.sty` file.  How does `\begin{theorem}` look (does it have a label?)

10. Reference/Bibliography

11. PreTeXt to JATS (Journal Article Tag Suite).  It's an XML format.

12. Other conversions to/from PreTeXt.  We should make a poster/diagram.

13. Cross references when extracting.  Warnings are given.  
    - Want to make a link to the full version.  
    - Numbering when extracting.  Preserve or renumber?  Levels of numbering (figure for example).  Both need to be publisher options.
    - What should the reference look like?  Name or number?

14. Documentation:
    - Reference for intermediate users: what can go here?
    - Quick start (less than 5 minutes)
    - There are multiple sections of the guide that are still "todo"
    - Quick start for specific document types.
    - Easy to find samples (e.g. annotated book)
    - More copy/paste snippets (in vscode)
    - Autocomplete
    - Schematic of the pretext universe
    - The `pretextbook.org` landing page
    - Catalog
    - Interactive features (Doenet etc)
    - Sample small documents to copy/modify.  Maybe as templates in the CLI or in a contributed repository
    - How to convert from LaTeX/Markdown

15. Community control with review.  Is that separate from the current repo?  What about things under development?  
    - Converting from latex/markdown easier than pandoc.
    - Converters from "lite" languages: highlight part of a document and hit convert.  Perhaps AI to go from lite documents to pretext?

16. Lite documents could be yaml and markdown, which could give you lots of pretext.  
    - Support people writing that.
    - What subset of LaTeX converts to PreTeXt?

17. Why write in PreTeXt?  Interactivity, Accessibility.

18. (an expansion of 7) One file is better (in some cases) than a directory with many files.
    - Common publisher file.
    - Think about the Instructor role
    - "Course" content.
    - Create by CLI: syllabus, worksheets.
    - How to share outside a "Course" context (like sharing a `.sty` file).
    - Start a document with `<publication>`.
    - You can share an overleaf project.

19. Linters.  Highlight sloppy markup.

20. Branding (related to "Course").  Publisher file should be Course Config file.  
    - Need to pay more attention to the Instructor ("Private Publishing")
    - Do competitor analysis

21. Assembling legacy material (book of worksheets).

22. Dynamic Calendar: What is it?

23. Programming Languages: Which are available, what are their capabilities?

24. Other embeddables: Penrose diagrams, Lurch, Sonification for data (multimodal), large data sets (see Runestone data file object).

25. One page output (HTML including CSS & JS).  Option 1: Bundle.  Option 2: external CSS & JS (but this would need a better way to maintain).  Zip files can be done, but don't meet the needs of this use case (sending an accessible file to a syllabus repository, eg)
    - What about google fonts?
    - Is ePub good enough?  No, because of knowls.
    - Other use cases: slides on a thumb drive

26. Put a slide in a book?  Really gather all slides in one place so you can share all slides for a course in a single link, that is updated regularly.  This is really like creating a "course".

27. LTI or LMS integration
