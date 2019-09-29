# A Chinese Character Puzzles Dataset (CCPD)

---

## Overview
This repo contains the data of the following paper:
>Solving Chinese Character Puzzles Based on Character. *Da Ren, Yi Cai, et.al*. NLPCC 2019. 

This paper proposes a Stroke Sensitive Character Guessing (SSCG) Model which can solve Chinese character puzzles.We collect Chinese character puzzles from [Baidu Hanyu](https://hanyu.baidu.com) and [Hydcd](http://www.hydcd.com/baike/zimi.htm). Each character puzzle has a corresponding answer. The strokes of each word is collected from [Httpcn](http://hy.httpcn.com). 

## Statistics
  |                      | Train         | Valid        | Test
  ------------                        | ----           | ----          | ---
  Total puzzle-answer pair            | 9354           | 500           | 450
 Avg.# characters per puzzle         | 6.44           | 5.75          | 5.86
   Avg.# strokes per word              | 9.30           | 8.27          | 8.14
  Different characters in puzzle      | 2662           | 879           | 821

## Description
* The train/valid/test.csv contain the Chinese puzzle-answer pairs. For each row, a puzzle description corresponds to a correct answer.
* As for the stroke.csv, it contains the word-stroke information. We encode the stroke each stroke as the number index.

## References
