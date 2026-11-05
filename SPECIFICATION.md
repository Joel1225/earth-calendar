# Earth Calendar Specification

## Date format

YEAR\DDD

DDD represents the day of the year, using three digits.

Examples:
11726\001
11726\318
11727\001

## Year boundaries

Each year begins at 00:00 UTC on the first midnight following the December solstice.

## Year length

A year can contain 365 or 366 days.

## Months

There are no months.

## Year numbering

Astronomical year numbering is used, including year 0 and negative years.

## Calibration

The existing conversion is authoritative:

2025-12-22 = 11726\001

2026-11-04 = 11726\318

2026-12-22 = 11727\001
