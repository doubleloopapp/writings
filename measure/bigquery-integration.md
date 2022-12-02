---
description: Learn how to populate metrics in DoubleLoop via BigQuery.
---

# BigQuery integration

DoubleLoop allows you to populate your metrics in DoubleLoop with time-series data from BigQuery. Here's how to do it.

## Part 1: **Create a "Metric source"**

1. Download credentials file from Google. If you're unfamiliar with how to do this, see the "Creating a service account" section in this doc: [https://cloud.google.com/docs/authentication/getting-started](https://cloud.google.com/docs/authentication/getting-started)
2. In DoubleLoop, double-click on a metric on the map.
3. Click the "Source" tab in the right drawer.
4. Choose "Google BigQuery" as the source.
5. Upload the credentials file (see step #1).
6. Input the query into DoubleLoop. The output of the query must contain columns named "date" and "value". We recommend that you test out the query in BigQuery before you input it into DoubleLoop.
7. Click "Save".

If you get stuck, please reach out!

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>
