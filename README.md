This is the second year I complete the Advent Of Code challenge. I tried to go as fast as possible, using Python 3.6 and JupyterNotebook.

This let me keep track of ideas, experiments and visualizations.

Here's the list of timings and rank day by day. Having in mind that 00:00 is 06:00 in Italy, and I woke up at 08:00, this could give an idea of relative timing (i.e. 02:46 means that I solved the exercise in ~46 minutes).

Best result was on second part of 23 December, I was 278th world-wide. Probably because I was lucky enough to have an approximate result which was actually accepted.

A few sparse notes:

- 9: I was not able to simplify the algorithm enough to run in a couple of minutes. It runs in a couple of hours, during night, which is not good but fair. I collected the results the morning after.
- 15: this one was dull. I was able to write most of the code and couldn't find the bug. I tried everything, added test cases. Then I asked [reddit](https://www.reddit.com/r/adventofcode/comments/a6o03g/day_15_double_check_on_a_piece_of_logic/) and I found out that my code was correct for a number of different inputs, but wrong for mine. Well, I was able to find the bug and submit the correct solution the day after.
- 17: This was fun, but I got so many bugs here and there. At last I was able to finish part 1, while for part 2 I had a brilliant idea involving regexes :)

```
      -------Part 1--------   -------Part 2--------
Day       Time  Rank  Score       Time  Rank  Score
 25   01:59:55   806      0   02:00:01   542      0
 24   05:44:26   751      0   05:51:48   669      0
 23   02:38:03  1154      0   03:17:00   278      0
 22   03:34:48  1137      0   10:14:19  1016      0
 21   10:29:53  1728      0   18:39:33  1944      0
 20   18:33:52  1972      0   18:38:02  1839      0
 19   14:46:09  2968      0   16:14:24  2210      0
 18   02:10:46  1395      0   02:40:20  1260      0
 17       >24h  2891      0       >24h  2868      0
 16   04:06:02  1390      0   04:19:11  1178      0
 15       >24h  2363      0       >24h  2178      0
 14   02:19:51  2024      0   11:18:46  3900      0
 13   10:41:59  3417      0   10:51:14  2871      0
 12   02:32:39  2159      0   16:42:05  5295      0
 11   02:48:10  3191      0   02:53:49  2375      0
 10   02:40:09  2307      0   02:43:30  2308      0
  9   03:58:50  2680      0       >24h  7230      0
  8   04:06:15  3085      0   04:50:15  3069      0
  7   02:40:24  2863      0   05:36:56  2785      0
  6   02:17:10  2292      0   02:33:04  2130      0
  5   02:11:54  4135      0   02:15:17  3629      0
  4   02:46:16  3114      0   02:48:26  2860      0
  3   02:12:36  3866      0   02:17:45  3414      0
  2   03:22:20  5434      0   03:27:56  4500      0
  1   02:55:51  4023      0   03:01:21  3050      0
```