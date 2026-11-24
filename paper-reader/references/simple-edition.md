# Simple-edition report

## Overview and Evaluation

Keep the full edition's research problem, setting, contribution, main results, and limits in Overview. Retain its complete Evaluation, including the experimental configuration, baselines, measurement scope, main results, ablations, and limitations. In a same-language conversion, preserve the text, equations, figures, and order in both sections. In a translation, preserve the evidence, values, figures, and order while translating the prose.

For a standalone simple report, build both sections directly from the paper. Record models, datasets and splits, hardware, software, precision, batch size, sequence length, cache or sparsity settings, baseline, metrics, aggregation, and timing boundaries. Mark unreported parameters. Explain the axes and scope beside each main result. Keep end-to-end, kernel, index-construction, and profiling results distinct.

## Motivation

Follow the paper from application need to prior limitations, supporting evidence, and research goal. Usually two or three short subsections suffice. Place each key motivation figure beside an explanation of the comparison and the observation. Keep the conditions under which the problem arises. Remove repeated explanations, background lessons, long cost calculations, and implementation digressions. Put term definitions in the clickable cards.

## Method

Follow the main components or stages, usually in three to five subsections. Give the input, core operation, output, dependencies, and connection to the next stage. Keep formulas and conditions that determine a decision, retain the original numbering, and explain what the variables mean and when the formula applies.

Condense auxiliary derivations, expanded matrices, element-by-element calculations, repeated examples, and line-by-line code discussion. Where a choice or data movement is hard to see, include a short example with checkable inputs and output, identified as illustrative. Keep preconditions, state dependencies, and correctness limits such as when an index becomes available or which history a cache loses.

For a numbered algorithm, include the whole original box and summarize its stages and selection criteria. If the paper has no algorithm box, use its method figure and procedural description. Cite the section for unnumbered expressions. Keep source formulas, explanatory expressions, examples, and verified implementation behavior distinguishable. Add implementation claims only when the relevant artifact supports them.

## Edition checks

Retain the glossary coverage of every term still in the report, and include the original figures needed to support the shorter argument. Check that Motivation and Method actually contain shorter prose in the HTML. For a conversion, compare Overview and Evaluation against the full edition. If the user requests moving original reports into a separate edition folder, verify their file hashes before and after the move. Keep editing materials outside the delivery folder.
