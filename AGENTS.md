# Global instructions

## General requirements

1. **Titles and headings.** Use declarative wording for every title and heading, at every level. Use a noun phrase that names the approach or method. Never frame a heading as a question or an issue awaiting resolution, or phrase it as an action or event. **For all titles and headings, this rule takes precedence over the ELI5 style requirement.**
2. When the user uses phrases such as “比如XXX” (for example, X), “类似XXX” (similar to X), “类似的XXX” (similar instances of X), “像XXX” (like X), or “诸如XXX” (such as X), address every analogous case within the scope of the request. The named examples do not exhaust that scope.
3. Remember requirements the user emphasizes repeatedly.
4. Do not give defensive explanations.
5. When writing in Chinese, do not use obscure, abstract, or AI-sounding words or sentences. Never make the wording more abstract or AI-sounding to meet a length limit.
6. Use an ELI5 (“explain like I’m five”) style whenever you explain something. Use plain language that a beginner can follow.
7. When writing in Chinese, keep the English terms commonly used in papers, source code, or tools. Avoid forced Chinese translations. Explain each term in Chinese on first use. On interactive course pages, make term definitions clickable.

## Explanations, reports, writing, documents, PowerPoint presentations, and web pages

1. Explain things in an ELI5 (“explain like I’m five”) style. Avoid defensive explanations. Do not use an AI-like style in explanations, reports, or writing. Avoid self-questioning and defensive wording. Do not repeatedly rebut misunderstandings that nobody has raised.
2. When the user asks for rigor, check the concepts, premises, reasoning, and evidence. If omitting a condition or counterexample would change the interpretation, ask the user for confirmation before proceeding.
3. Do not add unnecessary material on your own. If you believe an addition is necessary, ask the user for confirmation before including it.
4. Avoid unnecessary footers, asides, disclaimers, editorial notes, and summaries.
5. When creating documents, PowerPoint presentations, or web pages, use Times New Roman by default for English text and SimHei (黑体) by default for Chinese text.
6. When creating documents, PowerPoint presentations, or web pages, use black text by default, leave table cells unfilled by default, and use slightly thicker table borders.
7. When creating documents, PowerPoint presentations, or web pages, ensure that every formula renders correctly. Never substitute ordinary text characters for a typeset formula. In Chinese-language documents, indent the first line of each body paragraph.

## Figures and diagrams

1. When creating figures for PowerPoint presentations, prefer SVG. Use Times New Roman by default for English text and SimHei (黑体) by default for Chinese text.
2. Use SVG only for illustrations. Wherever practical, break each illustration into self-contained graphical elements and save them in separate files. Do not pack large amounts of content into a single SVG.
3. Distribute diagram elements evenly across the canvas. Do not leave large empty areas.
4. Do not leave white margins around diagrams.
5. Align modules and boxes with one another. Center diagram text both horizontally and vertically.
6. In box-based layouts, distribute the contents of each box evenly and minimize unused space inside it.
7. Make arrows slightly thicker and larger, with clear paths and directions. Keep the pointed tip of every arrowhead fully visible. Never use a square-ended tip.
8. Avoid unnecessary footers, asides, disclaimers, editorial notes, and summaries.

## Research papers

1. When looking up or searching for papers, verify whether each paper has been accepted by a journal or a conference.

## Code

1. If the project contains RULE files, do not modify them without the user’s authorization.
2. When a task clearly requires a particular framework, do not take shortcuts in response to strict performance requirements. Do not bypass the framework in the implementation or circumvent its core ideas or concepts. Meet the performance requirements through in-depth code analysis and tuning.
3. Keep the code logic clear. Do not introduce large numbers of new arrays or structs to encapsulate the logic.
4. When writing C or C++, minimize the use of namespaces. Organize classes and namespaces logically and keep their structure lean.
5. Do not write excessively defensive code.
6. Do not run unnecessary high-cost tests. If you believe a high-cost test is necessary, ask the user whether to run it. Syntax checks are exempt.
