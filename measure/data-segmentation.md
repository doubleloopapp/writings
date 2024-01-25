---
description: This page describes how to setup data segmentation in DoubleLoop.
---

# Data segmentation

_Note: The data segmentation feature is available to subscribers of our "Scale" plan. If you'd like access, let us know._

## What is data segmentation in DoubleLoop?

With data segmentation, you can tag the data points you import into DoubleLoop with one or more segments; e.g., geography, new/returning users, pricing plan, etc..

After you've uploaded segmented data, you can then filter a map by one or more segments. When you do so, the stats and correlation scores will update to reflect only data from your selected segments.

<figure><img src="../.gitbook/assets/CleanShot 2024-01-24 at 23.19.04.gif" alt=""><figcaption></figcaption></figure>

## Why is data segmentation useful?

Different user segments behave differently. E.g., your European users might be converting at a higher rate than your North American users. For European users, average order size might be highly correlated with revenue, but not for North American users. These are actionable insights that can influence your product strategy.

## How do you import segmented data?

The format for segmented data looks like the below. In the example, in row 2, the data point has two segments, user\_type:New and geograhy:North America.

You can have as many segments as you'd like.

<figure><img src="../.gitbook/assets/CleanShot 2024-01-24 at 23.28.05@2x.png" alt=""><figcaption></figcaption></figure>

### Import segmented data from your data warehouse

Go to the "Source" tab for a metric and select your source (e.g., Snowflake). Enter a query that returns data structured like above.

### Upload CSV files of segmented data

Go to the "data" tab for a metric and click Upload CSV. Here's en example file:

{% file src="../.gitbook/assets/weekly_segmented_data_revenue_simplified.csv" %}

## How do you know if it worked?

You know that you've successfully uploaded segmented data if you see the option to filter by segment at the bottom of your map.

If you have any questions, let us know.
