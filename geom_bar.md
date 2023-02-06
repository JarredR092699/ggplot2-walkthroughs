Bar Charts (geom_bar)
================
Jarred Robidoux
2023-02-06

# **Bar Charts**

There are two types of bar charts: geom_bar() and geom_col(). geom_bar()
makes the heigh of the bar proportional to the number of cases in each
group (or if the weight aesthetic is supplied, the sum of the weights).
If you want the heights of the bars to represent values in the data, use
geom_col() instead. geom_bar() uses stat_count() by default: it counts
the number of cases at each x position. geom_col() uses stat_identity():
it leaves the data as is.
