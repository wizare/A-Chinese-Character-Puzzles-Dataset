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
* As for the stroke.csv, it contains the word-stroke information. We encode the stroke as the number index. Different number represents different stroke.

## References

  @InProceedings{10.1007/978-3-030-32233-5_24,
  author="Ren, Da
  and Cai, Yi
  and Li, Weizhao
  and Xia, Ruihang
  and Li, Zilu
  and Li, Qing",
  editor="Tang, Jie
  and Kan, Min-Yen
  and Zhao, Dongyan
  and Li, Sujian
  and Zan, Hongying",
  title="Solving Chinese Character Puzzles Based on Character Strokes",
  booktitle="Natural Language Processing and Chinese Computing",
  year="2019",
  publisher="Springer International Publishing",
  address="Cham",
  pages="303--313",
  isbn="978-3-030-32233-5"
  }
