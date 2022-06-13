---
description: When a simple average won't suffice.
---

# Weighted averages

For a metric like conversion rate, a simple average over multiple days provides a misleading picture. For example, activity on the weekends is often much different than the weekdays.\
\
Here's how to do weighted averages in DoubleLoop so you can get an accurate sense of metric performance over time.

1. Instead of sending a metric like conversion rate to DoubleLoop, send the numerator and the denominator as separate metrics. For example, create two separate metrics for transactions and sessions.
2. Create a metric source in DoubleLoop I set "Calculated" as the source. This will allow you to select the numerator and denominator.
3. Attach a metric to your calculated metric source.
4. For the roll-up calculation for the metric, choose "Weighted average." When this option is selected, the map stats will divide the sum of the numerator values by the sum of the denominator values.

![Creating a metric source where you can specify the numerator and denominator](<../../.gitbook/assets/CleanShot 2022-06-12 at 22.39.03@2x.png>)
