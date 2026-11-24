# Shared report format

## Document and sources

Write for desktop reading and printing. Embed styles, scripts, definitions, and images in the HTML so that opening the file offline is sufficient. Keep source PDFs, drafts, crop previews, build scripts, and validation records outside the deliverable folder. Publish reports externally only when requested.

Use the paper's complete English title, checked against the original, as the H1, browser title, and link text in an optional index. If the paper has no official English title, preserve its published title. Identify editions through files or folders. Start the report directly with the title and Overview. Keep the four main sections in order and use descriptive subsection headings. Write plainly in the report language, explaining the paper's argument without course schedules, exercises, reader praise, or tutorial dialogue.

Place source and version information with the relevant figure, citation, or short end reference. Keep section anchors for internal references. Omit title banners, author metadata cards, insertion placeholders, fixed toolbars, sidebars, cross-paper navigation, contents panels, export and print buttons, and back-to-top controls.

## Definitions and cited papers

Make each occurrence of a recognized term clickable in editable report text, including headings, lists, tables, and captions. Cover abbreviations, datasets, benchmarks, models, metrics, methods, mechanisms, systems, and important cited papers. Map full names, abbreviations, case variants, and aliases to the same record. Distinguish different meanings by context. Keep formulas, code, external links, and source images intact. Use the editable caption for key terms in an image. Use one control per passage and avoid nested buttons.

Open a collapsed card at the point of reading. Include the name, official expansion if one exists, category, short meaning, role in this paper, and a verifiable source. For names without a formal expansion, give their documented origin where relevant. Write definitions in the report language. Keep the argument in the main text and background in the cards.

| Card | Details needed at the point of use |
| --- | --- |
| Dataset or benchmark | Data source, sample content and unit, task, and how the authors use it. Keep result-sensitive settings in Evaluation. For example, in a StreamingLLM report, the PG19 card should identify Project Gutenberg books published before 1919, the long-text language-modeling task, and the authors' use of the test set to construct a continuous stream. |
| Metric | What it measures, unit, preferred direction, and aggregation. |
| Method, mechanism, or system | What it operates on, what it does, and its relation to this paper. |
| Important cited paper | Full English title, verified publication venue and year or documented preprint status, brief summary, relevance to the method, baseline, or evaluation, and source link. Disambiguate similarly named papers and software. |

Check facts against the original paper, official dataset card, project documentation, or originating publication. Check publication status against proceedings or the publisher. Distinguish main conferences, workshops, journals, technical reports, and preprints. Embed the card content locally. Use keyboard-focusable triggers, toggle on a second click, provide a close control, and support Escape. Keep the page free of a permanent glossary or global toolbar.

## Equations and identifiers

Use native MathML for inline and display math and for expressions in tables and definition cards. Use the corresponding MathML structures for fractions, matrices, sums, scripts, norms, and piecewise functions. Show original equation numbers separately beside the expression. Match subscripts and superscripts across prose, tables, and equations. Use monospace for program identifiers. Give long equations a local horizontal scroll area and keep equation blocks together in print where practical.

## Original figures, tables, and algorithms

Obtain the source PDF and locate each figure, table, theorem, or algorithm needed for the discussion. Crop to the item's boundaries and retain its number, full caption, axes, legends, error bars, panel labels, and other evidence. An algorithm crop includes the complete box. Inspect every crop for clipped content or adjacent body text. Preserve the original values, drawing, and aspect ratio.

Embed the crop as an image data URL near the explanation. Identify the paper, item number, PDF version and one-based PDF file page in the editable caption, with a page-targeted link to the source. Distinguish the PDF file page from printed page numbers. Identify any author-created explanatory diagram as such. Use an internal anchor for later references to the same figure.

Use at least twice the image's normal desktop display width in pixels. Render at a higher resolution for fine labels. Let the reader open the full-resolution image locally and close it with a control or Escape. Typeset mathematical reasoning separately from source screenshots.

## Typography and print layout

Use Times New Roman for English text, Songti or SimSun with Noto Serif CJK SC as a fallback for Chinese report prose, and monospace for code. Indent the first line of Chinese body paragraphs by two character widths. Align captions, lists, tables, and code according to their own structure. Fit short tables to their content and center headers and cells. Wrap long entries or scroll the table locally. Keep the desktop page free of horizontal overflow. Use desktop layouts without mobile-specific breakpoints.

Provide a print stylesheet that keeps text, captions, sources, figures, and formulas readable and hides interactive controls and open overlays. Leave printing to the browser.

## Offline and visual checks

- Open the finished file in a desktop browser engine with networking disabled. Check text, every image's decoding and intrinsic size, and locally available definitions and paper summaries.
- Check term coverage across the entire editable report, including repeated occurrences and aliases. Verify card contents, keyboard focus, opening and closing, Escape, and the image viewer.
- Inspect every MathML element for parsing errors, empty expressions, leftover LaTeX or dollar delimiters, and abnormal dimensions. View representative screenshots of fractions, matrices, long subscripts, wide equations, and table math.
- Inspect all source crop previews, then view complex figures, complete algorithm boxes, and long tables in the rendered page. Check desktop overflow and print preview. Confirm that the report has no leftover navigation panels, metadata banners, or image placeholders.
- Record structural checks and visual checks separately outside the delivery folder. Correct failures before delivery.
