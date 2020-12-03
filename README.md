This is commit Clean up needless variables, leverage threshold

- Now using a min threshold of 50 (ratio is from 0 to 100)
- From tests, the lowest ratio I found for a good match was 57
- If neither search through total_stat_map or adv_stat_map are
- Over 50, return None