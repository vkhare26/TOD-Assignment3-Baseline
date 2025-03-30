# TOD-Assignment3-Baseline
Reproducing HDC baseline for task-oriented dialogue (MultiWOZ) from Elizabeth et al. (2025).

# TOD Assignment 3 - Part 2
Reproducing the HDC baseline (BERT NLU + HDC + Template NLG) from Elizabeth et al. (2025) on MultiWOZ 2.1.

## Setup
1. Install ConvLab-3: `pip install convlab3`
2. Download MultiWOZ 2.1: [GitHub link](https://github.com/thu-coai/MultiWOZ-2.1) (place in `data/` manually).
3. Run: `python code/hdc_baseline.py`

## Target Metrics
- Success Rate: 83.8%
- Avg Turns: 12
- Inform Rate: 86.2 F1
- Book Rate: 91.5%

## Structure
- `code/`: Scripts (e.g., hdc_baseline.py)
- `data/`: MultiWOZ 2.1 (not uploaded due to size)
- `logs/`: Dialogue logs and metrics
- `docs/`: Report drafts