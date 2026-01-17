# yml-canvas-28

A small Python tool that computes text statistics for canvas.

## Goal
- Provide quick text metrics for canvas documents.
- Report top word frequencies for fast inspection.

## Usage
python textstats.py data/sample.txt --top 5

## Output
- lines: total line count
- words: total word count
- chars: total character count
- top words: most frequent tokens (case-insensitive)

## Notes
- Only ASCII letters and digits are treated as word characters.
