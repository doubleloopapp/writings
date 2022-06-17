---
description: Learn how to populate metrics in DoubleLoop via BigQuery.
---

# BigQuery integration

DoubleLoop allows you to populate your metrics in DoubleLoop with time-series data from BigQuery. Here's how to do it.

_Note: we recognize there's a lot of potential to simplify this process. Please let us know what problems you run into or any other feedback._

## Part 1: **Create a "Metric source"**

1. Download credentials file from Google. If you're unfamiliar with how to do this, see the "Creating a service account" section in this doc: [https://cloud.google.com/docs/authentication/getting-started](https://cloud.google.com/docs/authentication/getting-started)
2. In DoubleLoop, go to the page for Metric Sources: [https://app.doubleloop.app/metric\_sources](https://app.doubleloop.app/metric\_sources)
3. Click "Add metric" source.
4. Enter a name for the metric source and optionally a description. The metric source name should be specific to a particular metric you want to create. E.g., it should be something like "# of new subscribers" as opposed to something more generic like "BigQuery."
5. Choose "Google BigQuery" as the source.
6. Upload the credentials file (see step #1).
7. Input the query into DoubleLoop. The output of the query must contain columns named "date" and "value". We recommend that you test out the query in BigQuery before you input it into DoubleLoop.
8. Click "Save".

## Part 2: **Create a "Metric"**

1. You're going to use the "metric source" you created to populate a "metric" in DoubleLoop. If that metric already exists, skip this step. Otherwise, you can add the metric by clicking "Add metric" from one of your strategies or on the metrics listing page. It's expected that the metric could have the same name as the metric source.
2. In the settings for the metric, for "Metric source," select the metric source you previously created.

![](<../.gitbook/assets/CleanShot 2022-03-07 at 14.52.00@2x.png>)

## Part 3: Confirm it worked

Every night, DoubleLoop will populate data for your metric based on the query you specified for the metric source. So you should see your metric data tomorrow.

Unfortunately, at this point in time, there's no way to see the data the nightly job runs. For this reason, as we recommended above, we suggest verifying the query in BigQuery first.

That's it. Please let us know your feedback. If you have any questions, please contact us.
