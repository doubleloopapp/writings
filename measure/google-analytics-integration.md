---
description: Learn how to populate metrics in DoubleLoop from Google Analytics.
---

# Google Analytics integration

DoubleLoop allows you to populate your metrics in DoubleLoop with time-series data from Google Analytics. Here's how to do it.

_Note: we recognize there's a lot of potential to simplify this process. Please let us know what problems you run into or any other feedback._

1. Go to the [integrations page](https://app.doubleloop.app/settings/integrations) and walk through the quick steps to connect Google Analytics.
2. Go to the [Metric Sources](https://app.doubleloop.app/metric\_sources) page.
3. Click "Add metric source."
4. Enter a name for the metric source and optionally a description. The metric source name should be specific to a particular metric you want to create. E.g., it should be something like "New users" as opposed to something more generic like "Google Analytics."
5. Choose "Google Analytics" as the source.
6. Specify the property, metric, and segment you'd like to import into DoubleLoop.
7. Click "save."

## Part 2: **Create a "Metric"**

1. You're going to use the "metric source" you created to populate a "metric" in DoubleLoop. If that metric already exists, skip this step. Otherwise, you can add the metric by clicking "Add metric" from one of your strategies or on the metrics listing page. It's expected that the metric could have the same name as the metric source.
2. In the settings for the metric, for "Metric source," select the metric source you previously created.

![](<../.gitbook/assets/CleanShot 2022-03-07 at 14.52.00@2x.png>)

## Part 3: Confirm it worked

As soon as you connect your metric source to a metric, DoubleLoop will pull in historical data for that metric. Moving forward, DoubleLoop will pull in new values for the metric each night.
