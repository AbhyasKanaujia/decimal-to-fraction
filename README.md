# Decimal to Fraction Converter

A web-based tool that converts decimal numbers into their closest fractional representations. The converter finds multiple fraction approximations and displays them in order of accuracy.

## Goal

The goal of this project is to create a solution so that users can find the closest and alternative fractional representation for a given number in the most efficient way with as much control over the generation process as possible. 

## Milestones

1. 🌼 At least one fractional representation is generated regardless of if it's the most accurate. 
2. 🌱 The generation process is highly optimized.
3. 🌱 The output is sorted by closeness to the target decimal.
4. 🌱 The user can control the maximum number of fractional representations to generate.
5. 🌱 The user can control the maximum denominator.
6. 🌱 The generation shows some kind of appropriate visualization.

## Features

- Convert any decimal number between 0 and 100 into fractions
- Real-time conversion display
- Display of multiple fraction approximations

## Implementation Details

- Maximum denominator: 100
- Results are limited to 10 closest fractions
- Input debounce delay: 500ms
- Results sorted by proximity to target decimal

## Usage

1. Open index.html file in a web browser
2. Enter a decimal number in the input field

## Technical Notes

The converter uses a brute-force algorithm that:

1. Tests denominators from 1 to 100
2. Calculates the closest numerator for each denominator
3. Sorts results by difference from target decimal
4. Returns the top 10 closest matches
