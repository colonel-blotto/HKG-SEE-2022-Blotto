# HKG SEE - Blotto Challenge!

In light of the 2023 HKG SEE Challenge appearing surprisingly similar, I have decided to repost for any interested candidates. Enjoy!

## Puzzle Description

Here are 10 castles, numbered 1, 2, 3, ... , 10, and worth 1, 2, 3, ... , 10 points respectively. You have 100 soldiers, which you can allocate between the castles however you wish. Your opponent also (independently) does the same. The number of soldiers on each castle is then compared, and for each castle, whoever has the most soldiers on that castle wins its points. In addition, you win 2p points where p is the longest consecutive winning streak, but get deducted q point where q is the longest losing streak. In the case of a tie, no one gets points for that castle. 

| Castle   | C1 | C2 | C3 | C4 | C5 | C6 | C7 | C8 | C9 | C10 |
|----------|----|----|----|----|----|----|----|----|----|-----|
| Alice    | 10 | 10 | 10 | 10 | 10 | 10 | 10 | 10 | 10 | 10  |
| Carol    | 15 | 5  | 30 | 5  | 10 | 5  | 0  | 10 | 0  | 20  |

## Objective

We're going to play a tournament. You get one entry and your final score is the average (mean) of your scores against all the other entries from applicants.

## Past Data

This directory contains the data behind the submissions for the 2022 HKG SEE - Blotto Challenge. The data includes all valid submissions, with solvers’ identifying information removed.

`2022-solutions.csv` contains the submissions for [HKG SEE - 2022](2022-solutions.csv).

## Improved Submission

As the top five entrants from last year were:

| Castle   | C1 | C2 | C3 | C4 | C5 | C6 | C7 | C8 | C9 | C10 |
|----------|----|----|----|----|----|----|----|----|----|-----|
| #1       | 1  | 1  | 2  | 3  | 4  | 21 | 27 | 28 | 6  | 7   |
| #2       | 1  | 2  | 2  | 4  | 4  | 25 | 26 | 26 | 5  | 5   |
| #3       | 0  | 3  | 6  | 1  | 12 | 20 | 24 | 23 | 6  | 5   |
| #4       | 0  | 2  | 3  | 3  | 16 | 20 | 22 | 26 | 4  | 4   |
| #5       | 0  | 3  | 3  | 5  | 10 | 21 | 21 | 21 | 10 | 6   |

My suggested modified entry is as such.

| Castle   | C1 | C2 | C3 | C4 | C5 | C6 | C7 | C8 | C9 | C10 |
|----------|----|----|----|----|----|----|----|----|----|-----|
| My Entry | 1  | 3  | 3  | 2  | 1  | 23 | 27 | 28 | 6  | 6   |

My general approach was to simulate a number of tournaments consisting of some of the 2022 submissions, some strategies which would outperform the top candidates of the 2022 submissions, and some cleverly chosen deterministic strategies. I chose the strategy that performed the best on average in my simulations.

google-site-verification: googlee4591125e7f34210.html
