# Homework 1 - Penguins Dataset Analysis

**Author:** Harsh Mehta  
**Student Number:** 24208383  

## Overview

This project explores the **Palmer Penguins Dataset**, which provides physical and demographic information on three species of penguins: **Adelie**, **Chinstrap**, and **Gentoo** across three islands in the Palmer Archipelago, Antarctica.

## Dataset Description

The dataset contains **344 records** of adult penguins and the following variables:

| Variable      | Description                                 |
|---------------|---------------------------------------------|
| `species`     | Species of the penguin (Adelie, Chinstrap, and Gentoo) |
| `island`      | Island where penguin was found (Biscoe, Dream, and Torgersen) |
| `bill_len`    | Bill length (mm)                            |
| `bill_dep`    | Bill depth (mm)                             |
| `flipper_len` | Flipper length (mm)                         |
| `body_mass`   | Body mass (g)                               |
| `sex`         | Sex of the penguin (male/female)            |
| `year`        | Year of observation (2007, 2008, or 2009)             |

## Visualization

A **bar plot** was created using `ggplot2` to compare the **average bill length by species**.

### Key Findings:
- **Chinstrap** penguins have the **longest** average bill length (under 50 mm).
- **Gentoo** penguins have a **moderate** average.
- **Adelie** penguins have the **shortest** average (around 39 mm).
