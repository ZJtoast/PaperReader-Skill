# PaperReader Skill

PaperReader turns a research paper into a single HTML report that opens offline in a desktop browser. It accepts requests in English or Chinese and writes the report in either language. Each report follows the paper through Overview, Motivation, Method, and Evaluation, with figures from the original PDF, typeset equations, and clickable definitions.

| Edition | Reading depth |
| --- | --- |
| Full (default) | Follows the method from inputs to outputs, including dependencies, derivations, and worked examples where they clarify a decision. |
| Simple | Shortens Motivation and Method. Keeps the full Overview and Evaluation, including experimental settings, baselines, and limitations. |

## Installation

Download or clone this repository. Copy the entire [paper-reader](paper-reader/) folder into your Codex skills directory, normally `~/.codex/skills/`. If you use a custom `CODEX_HOME`, use its `skills` directory. The installed entry point should be `skills/paper-reader/SKILL.md`. Start a new Codex chat to use it.

The repository also includes the author's [global AGENTS.md](AGENTS.md). Installing the skill requires only the `paper-reader` folder.

## Example requests

Attach the PDF or supply its path or a link. Write the request in either language. By default, the report follows the language of the request. You can also specify a different output language.

> Use $paper-reader to write a full report in Chinese on the attached paper. Trace the inputs and outputs of its main algorithm.

> Use $paper-reader to make a simple English edition of this report. Keep the Overview and Evaluation intact.

> Use $paper-reader to prepare the simple edition in both Chinese and English, with a separate HTML file for each language.
