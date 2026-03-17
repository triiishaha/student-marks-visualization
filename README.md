# Student Marks Visualization

A tour of common matplotlib chart types applied to a small toy dataset of 5 students' marks and attendance — pie, bar, scatter, histogram, line, box, and area charts.

## Overview

This notebook builds one small `pandas` DataFrame (5 students, their marks out of 100, and their attendance percentage) and visualizes it seven different ways to compare what each chart type communicates:

1. **Pie chart** — each student's share of the total marks.
2. **Bar chart** — marks by student, side by side.
3. **Scatter chart** — attendance vs. marks, to eyeball any correlation.
4. **Histogram** — the distribution/frequency of mark values.
5. **Line chart** — marks by student as a trend line.
6. **Box plot** — spread and median of the marks (median line sits close to 85, since most students scored near there).
7. **Area chart** — marks by student, filled.

## Data

A small hardcoded dataset (no external file needed):

| Student | Marks | Attendance |
|---|---|---|
| A | 85 | 90 |
| B | 78 | 85 |
| C | 92 | 95 |
| D | 70 | 80 |
| E | 88 | 92 |

## Repository structure

```
student-marks-visualization/
├── charts.ipynb       # data -> pie / bar / scatter / histogram / line / box / area charts
├── requirements.txt   # Python dependencies
├── README.md
└── LICENSE
```

## Setup

```bash
git clone https://github.com/triiishaha/student-marks-visualization.git
cd student-marks-visualization
pip install -r requirements.txt
```

## Usage

```bash
jupyter notebook charts.ipynb
```

Run the cells top to bottom — no dataset download needed, the data is defined inline.

## Tech stack

pandas · matplotlib · seaborn

## License

Released under the [MIT License](LICENSE).
