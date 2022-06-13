---
description: Learn how to control what stats appear on your strategy map
---

# Control the stats on your strategy map

In this doc, you'll learn how to control the stats that appear on your strategy map. You can control the time intervals, the roll-up calculations, and the format.

![](<../.gitbook/assets/CleanShot 2022-06-12 at 20.20.57@2x.png>)

## Control the time intervals

By default, stats on your strategy map will display with the time intervals Past 7 days, Past 6 weeks, and past 12 months. You can change these intervals to whatever is right for your business.

To change the time intervals, go to the full metric settings page and adjust these settings:

![](<../.gitbook/assets/CleanShot 2022-06-12 at 20.27.50@2x.png>)

## Control the roll-up calculations

![](<../.gitbook/assets/CleanShot 2022-06-12 at 20.32.54@2x.png>)

Choosing the right roll-up calculation depends on the nature of the metric. Here's how each roll-up calculation works, and when to use it.

| Roll-up calculation | How it works                                                                                                                                     | When to use it                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| Sum                 | Sums the metric values for each time interval.                                                                                                   | Good for metrics that capture the amount of something on each day or month.                                  |
| Average             | Averages the metric values for each time interval.                                                                                               | Good for metrics that can't be summed, like "Daily active users" or percentages.                             |
| Amount increased    | Subtracts the value at the beginning of the interval from the value at the end of the interval.                                                  | Good for metrics that represent a cumulative total, like the total number of total subscribers on each day.  |
| Weighted average    | <p>Only works for metrics with a source of "calcuations."<br><br>Divides the sum of the numerator values by the sum of the dominator values.</p> | Good for metrics like conversion rates when a simple average is misleading.                                  |

## Change percentages

![](<../.gitbook/assets/CleanShot 2022-06-12 at 20.59.51@2x.png>)

The percentages that appear beneath each metric stat show how the metric performed compared to the previous period of the same length.

For example, if the roll-up value for the metric is 5 in the last seven days and was 4 in the seven days prior, the change percentage would be 25%.

Here's how the percent change calculation always works:

**(current period - previous period) / (previous period)**

## Format

![](<../.gitbook/assets/CleanShot 2022-06-12 at 20.56.29@2x.png>)

The format only controls what symbol appears along with the metric value. E.g., for a metric like "Revenue," use one of the currency formats.
