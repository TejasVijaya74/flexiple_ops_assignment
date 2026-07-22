# Operations Manager Assignment

## Overview

This repository contains my solution for the Operations Manager Assignment. The assignment focuses on data cleaning, interview scheduling, and professional business communication using Python and spreadsheet automation.

---

## Project Structure

```
.
├── task1.csv          # Cleaned candidate database
├── task2.csv          # Interview schedule
├── task3a.txt         # Candidate confirmation email
├── task3b.txt         # Escalation message
├── tools.txt          # Tools used
├── task1.ipynb        # Google Colab notebook for Task 1
├── task2.ipynb        # Google Colab notebook for Task 2
└── README.md
```

---

# Task 1 – Candidate Database Cleaning

### Objective

Transform the raw candidate dataset into a clean, deduplicated database suitable for an interview drive.

### Implemented Features

- Normalized phone numbers
- Standardized email addresses
- Converted names and cities to Title Case
- Converted experience into years
- Normalized date formats
- Duplicate detection using Phone OR Email
- Merged duplicate records while preserving the most complete information
- Assigned eligibility status and reason codes
- Generated Candidate IDs (C001, C002, ...)
- Exported final dataset as `task1.csv`

### Summary

| Metric | Value |
|--------|------:|
| Original Records | 40 |
| Records After Deduplication | 37 |
| Eligible Candidates | 29 |
| Ineligible Candidates | 8 |

---

# Task 2 – Interview Scheduling

### Objective

Schedule interviews while respecting interviewer availability and candidate constraints.

### Scheduling Constraints

- Interview duration: 30 minutes
- Fixed interview slots
- No overlapping interviews
- Candidate-specific availability respected
- Rahul assigned one mandatory 30-minute break
- Maximum number of candidates scheduled

### Summary

| Metric | Value |
|--------|------:|
| Total Candidates | 14 |
| Scheduled | 12 |
| Unscheduled | 2 |

---

# Task 3 – Communication Templates

Prepared two communication templates:

- Candidate Interview Confirmation Email
- Escalation Message to Client TA Lead

Both messages satisfy the assignment's word limits and required placeholders.

---

# Technologies Used

- Python 3
- Google Colab
- Pandas
- NumPy
- Dateutil
- Regular Expressions (re)

---

# AI Usage

Google Gemini was used to assist with notebook structure and code generation.

All generated code and outputs were manually reviewed, tested, and validated against the assignment requirements before submission.

---

# Output Files

| File | Description |
|------|-------------|
| task1.csv | Cleaned candidate database |
| task2.csv | Interview schedule |
| task3a.txt | Candidate confirmation email |
| task3b.txt | Escalation message |
| tools.txt | Tools used during completion |

---

# Notes

- All outputs follow the column formats specified in the assignment.
- Duplicate records were merged using normalized phone numbers and email addresses.
- Interview scheduling prioritizes constraint satisfaction while maximizing scheduled candidates.
- Outputs were verified manually before submission.

---
