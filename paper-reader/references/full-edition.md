# Full-edition report

## Overview

Identify the research problem, the setting where it arises, the authors' contribution, and the main result with its measurement conditions. Use the paper's overview figure when it helps connect the problem to the method.

## Motivation

Follow the authors' reasoning from the application requirement through the limits of existing approaches to the observation that motivates the design. Place each relevant figure near the claim it supports. Explain what was compared, under which conditions, and what the comparison shows. When a trade-off depends on a workload or hardware assumption, state it with the claim.

## Method

Describe each stage in execution order. Identify its inputs and outputs, give symbols and shapes, show where data is stored, and trace what each operation reads, writes, or waits for. Where two methods behave differently, the same small input can expose the decision that changes the output.

Give all inputs and intermediate values needed to reproduce a worked example. Distinguish formulas and algorithms in the paper, your own derivations, hand calculations, author-code behavior, and measured results. Keep original equation and algorithm numbers. For unnumbered expressions, cite the section.

Include each numbered algorithm needed for the explanation as a complete crop with its title, inputs, outputs, and line numbers where present. If the paper has no algorithm box, say so and use its method figures and prose. Label explanatory pseudocode as reconstructed from the paper. Annotate every nonblank operation in the report language with the state it reads, updates, or awaits.

For implementation claims, cite the repository, revision, and file. Verify the experiment entry point before connecting a class or kernel to a particular result. Distinguish the paper's artifact and branch from related projects. Explain discrepancies in symbols or parameters where they affect the reader's interpretation.

## Evaluation

Record the models, datasets, hardware, software, precision, batch size, sequence length, sparsity or cache settings, baselines, metrics, and timing scope. Include the split, subset, scale, concatenation, or truncation settings that affect the result. Mark missing settings as unreported. Explain how measurements were aggregated and whether a time covers a kernel, preprocessing, profiling, or the full run.

Place the main comparisons and ablations beside the relevant figures or tables. Explain the axes, units, configurations, observed differences, and limitations. Keep each numerical claim tied to its baseline and the part of execution that was measured.
