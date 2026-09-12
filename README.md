# Derivatives Course Homework

Coursework and supporting data for a derivatives course. Each assignment is kept
in its own folder so that notebooks, prompts, and input data remain together.

## Repository Layout

| Folder | Topics and contents |
| --- | --- |
| [`HW1`](HW1/) | WTI crude oil data, forwards, and hedging |
| [`HW2`](HW2/) | SPX/NDX futures fair value and index arbitrage |
| [`HW3`](HW3/) | Cheapest-to-deliver analysis for TYZ5 Treasury futures |
| [`HW4`](HW4/) | Assignment prompt and Problem 2.3 workbook |
| [`HW5`](HW5/) | European options assignment and Problem 3 workbook |
| [`HW6`](HW6/) | Trinomial-tree American option pricing |
| [`HW7`](HW7/) | Implied volatility and American option Greeks |
| [`HW8`](HW8/) | VIX calculation from SPX option chains |

The course syllabus is available at [`DerivativesSyllabus.pdf`](DerivativesSyllabus.pdf).

## Working With the Notebooks

1. Open the notebook for the assignment in Jupyter Notebook or JupyterLab.
2. Run the notebook from its assignment directory. Several notebooks load data
   using paths relative to that directory.
3. Keep the supplied input files beside the notebook unless a notebook is
   updated to use a different path.

The repository currently contains both notebooks and original assignment
materials. Files in `Archive/` and the VIX data folder are retained as
supporting source material for their respective assignments.

## Notes

- `HW1/Huang_James_HW0.ipynb` is the submitted notebook for the course's
  Homework 0 material, even though it is stored under the first homework folder.
- Checkpoint notebooks and operating-system metadata are ignored by Git through
  [`.gitignore`](.gitignore).
- Do not commit private API keys, terminal exports, or unrelated local files.
