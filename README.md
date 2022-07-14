# tcspc_plot

Visualize TCSPC data with PGFPlots & TikZ.

## Compilation

Compile the document ``main.tex`` with XeLaTeX using MikTeX. When displaying scatter data it may be necessary to expand 
the main memory size with the additional compiler argument ``--extra-mem-top=100000000``.

## Example Data

This work contains example TCSPC data acquired during a practical in the directory ``data``.
- ``tcspc_daten-1.txt``: Rhodamine B in different solvents (chloroform, ethanol, water, iso-propanol).
- ``tcspc_daten-2.txt``: 9-Cyanoanthracene in acetonitrile (aerated, enriched with oxygen, degassed with nitrogen).
- ``tcspc_daten-3.txt``: 9-Cyanoanthracene in iso-propanol with 2-nitrotoluene of various concentrations (0mM, 2.83mM, 5.65mM, 8.48mM, 11.3mM).

## License

This work may be distributed and/or modified under the conditions of the LaTeX Project Public License. This work has 
the LPPL maintenance status `maintained'.
