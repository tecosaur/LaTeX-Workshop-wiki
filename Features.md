# Features

This feature list does not claim to be comprehensive. However it should give a good idea of how LaTeX-Workshop stacks up to other common LaTeX editors.

## Comparison to Some Other Editors

### Overall

| Feature              | LaTeX Workshop | TexLab | TeXstudio | TexMaker | Overleaf |
| -------------------- | -------------- | ------ | --------- | -------- | -------- |
| Multi-Cursor         | ✔️             | ✔️     | ✔️        | ❔        | ❌        |
| Symbol Picker        | ❌              | ❌      | ✔️        | ✔️       | ❌        |
| Assistant/Wizard     | ❌              | ❌      | ✔️        | ✔️       | ❌        |
| Drag and Drop Images | ❌              | ❌      | ✔️        | ❔        | ❌        |
| PDF Viewer           | ✔️             | ❌      | ✔️        | ✔️       | ✔️       |
| 'Quickbuild' Recipes | ✔️             | ❌      | ❔         | ✔️       | ❌        |
| Documentation Viewer | ✔️             | ❌      | ❔         | ✔️       | ❌        |
| Error Reporting      | ✔️             | ✔️     | ✔️        | ✔️       | ✔️       |
| Snippets             | ✔️             | ✔️     | ❔         | ✔️       | WIP      |
| Code completion      | ✔️             | ✔️     | ✔️        | ✔️       | ✔️       |
| Info on Hover        | ✔️             | ✔️     | ✔️        | ❔        | ❌        |
| Signature help       | ✔️             | ❌      | ✔️        | ✔️       | ✔️❔      |
| Goto declaration     | ❌              | ❌      | ❌❔        | ❌❔       | ❌        |
| Goto definition      | ❌              | ✔️     | ❌❔        | ❌❔       | ❌        |
| Find references      | ❌              | ✔️     | ✔️❔       | ✔️❔      | ❌❔       |
| Document symbols     | ✔️             | ✔️     | ✔️        | ✔️       | ❌        |
| Document link        | ❌              | ✔️     | ❌❔        | ❌❔       | ❌        |
| Document formatting  | ✔️             | ❌      | ✔️        | ✔️       | ❔        |
| Rename               | ❌              | ✔️     | ❌         | ❌        | ❌        |
| Folding              | ✔️             | ✔️     | ✔️        | ✔️       | ✔️       |

### TexLab (as a vscode extension)

feature list from: https://texlab.netlify.com/

| Feature              | TexLab | LaTeX Workshop |
| -------------------- | ------ | -------------- |
| Code completion      | ✔️     | ✔️             |
| Hover                | ✔️     | ✔️             |
| Signature help       | ❌      | ✔️             |
| Goto declaration     | ❌      | ❌              |
| Goto definition      | ✔️     | ❌              |
| Goto type definition | ❌      | ❌              |
| Find references      | ✔️     | ❌              |
| Document highlights  | ✔️     | ❔              |
| Document symbols     | ✔️     | ✔️             |
| Code action          | ❌      | ❌              |
| Code lens            | ❌      | ❌              |
| Document link        | ✔️     | ❌              |
| Document color       | ❌      | ❌              |
| Document formatting  | ❌      | ✔️             |
| Rename               | ✔️     | ✔️             |
| Folding              | ✔️     | ✔️             |

### TeXstudio

feature list from: https://www.texstudio.org/

| Feature                              | TexStudio | LaTeX Workshop         |
| ------------------------------------ | --------- | ---------------------- |
| Multi-Cursor                         | ✔️        | ✔️<sup>[2](#fn2)</sup> |
| Auto-Completion                      | ✔️        | ✔️                     |
| Symbol Picker                        | ✔️        | ❌                      |
| Hover Info                           | ✔️        | ✔️                     |
| Assistant (images, tables, formulas) | ✔️        | ❌                      |
| Drag and Drop images                 | ✔️        | ❌                      |
| Table Formatting                     | ✔️        | ✔️                     |

### TexMaker

feature list from: http://www.xm1math.net/texmaker/

| Feature                   | TexMaker | LaTeX Workshop         |
| ------------------------- | -------- | ---------------------- |
| Spell Checker             | ✔️       | ❌<sup>[1](#fn1)</sup>  |
| Code Folding              | ✔️       | ✔️                     |
| Code Completion           | ✔️       | ✔️                     |
| Structure View            | ✔️       | ✔️                     |
| File structure view       | ✔️       | ✔️                     |
| PDF Viewer                | ✔️       | ✔️                     |
| 'Quickbuild' Recipes      | ✔️       | ✔️                     |
| Symbol Picker             | ✔️       | ❌                      |
| Wizards*                  | ✔️       | ❌                      |
| Documentation Viewer      | ✔️       | ✔️                     |
| Error Reporting           | ✔️       | ✔️                     |
| Block Selection Selection | ✔️       | ❌                      |
| Find in folders           | ✔️       | ✔️<sup>[2](#fn2)</sup> |
| Regex search              | ✔️       | ✔️<sup>[2](#fn2)</sup> |
| Asymptote Support         | ✔️       | ❔                      |
| Snippets                  | ✔️       | ✔️<sup>[2](#fn2)</sup> |

\* analagous to TeXstudio's Assistants which provide a GUI for certain tasks (table creation, etc.)

### Overleaf

| Feature                                      | Overleaf | LaTeX Workshop        |
| -------------------------------------------- | -------- | --------------------- |
| Folding                                      | ✔️       | ✔️                    |
| Code Completion                              | ✔️       | ✔️                    |
| Smart Suggestion Ranking<sup>[3](#fn3)</sup> | ✔️       | ❌                     |
| Reference Search                             | ✔️       | ✔️                    |
| Rich Text Mode                               | ✔️       | ❌                     |
| Zotero Integration                           | WIP      | ❌                     |
| Mendely Integration                          | ✔️       | ❌                     |
| Spell Check                                  | ✔️       | ❌<sup>[1](#fn1)</sup> |
| Templates                                    | ✔️       | ❌                     |


<a name="fn1">1</a>: Functionality available via other VS Code extensions
<a name="fn2">2</a>: Functionality provided by VS Code
<a name="fn2">3</a>: see https://www.overleaf.com/blog/523-a-data-driven-approach-to-latex-autocomplete
