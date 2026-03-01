# Fuzzy Parking Decision System

A fuzzy-logic-based cooperative parking decision system for two cars approaching the same parking area.

## Inputs
- Distance between cars (0–15 m)
- Angle difference between cars (0–90°)
- Priority score (0–10)

## Output
`final_action` in range [-1, 1]:
- -1 → full stop
- ~0 → equal situation / wait
- +1 → start parking / full park

## What’s inside
- Membership functions (visualized)
- Rule base (27 fuzzy rules)
- Defuzzification: centroid
- Multiple test scenarios with interpretation

## How to Run

Install dependencies:
```bash
pip install -r requirements.txt