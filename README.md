# Live Coding Bioinformatics Exercises

This repo is a small collection of live-coding style exercises for practicing **foundational bioinformatics patterns** in plain Python.

Each notebook is meant to feel like the kinds of problems you might see in an interview, on a whiteboard, or in a workshop: short, focused, and built around **small, composable helper functions** with clear assumptions.

## Notebooks

All notebooks live in the `notebooks/` folder.

1. `01_reverse_complement.ipynb`
   - Reverse complement of a DNA sequence.
   - You will practice:
     - String slicing
     - Simple dictionaries
     - Writing and reusing tiny helper functions

2. `02_gc_content_sliding_window.ipynb`
   - GC content for a single sequence and with a **sliding window** across a longer read.
   - You will practice:
     - Counting characters
     - Handling edge cases and Ns
     - Implementing a sliding-window algorithm

3. `03_seq_validation_qc_metrics.ipynb`
   - A small QC pass over a list of sample records.
   - You will practice:
     - Validating DNA sequences
     - Computing GC content and N fraction
     - Returning structured outputs (one record per sample)

## How to use these notebooks

- Open the notebooks in Jupyter, VS Code, or your favorite notebook environment.
- Work **top to bottom**:
  - Start by reading the problem and assumptions.
  - Implement code in the "YOUR CODE HERE" cells.
  - Treat the **Solutions** sections at the bottom as a last resort or a way to compare approaches.
- While you work, try to:
  - Say your assumptions out loud.
  - Decompose the problem into small helpers instead of one big function.
  - Think through edge cases before they bite you.

## Recommended order

If you're not sure where to start, this order will feel the most natural:

1. `01_reverse_complement.ipynb`  
2. `02_gc_content_sliding_window.ipynb`  
3. `03_seq_validation_qc_metrics.ipynb`

Each notebook builds on the previous one, moving from basic string manipulation to simple but realistic QC logic that actually shows up in day‑to‑day pipelines.
