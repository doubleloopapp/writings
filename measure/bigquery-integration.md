---
description: Learn how to populate metrics in DoubleLoop via BigQuery.
---

# BigQuery integration

DoubleLoop allows you to populate your metrics in DoubleLoop with time-series data from BigQuery. Here's how to do it.

1. Download credentials file from Google. If you're unfamiliar with how to do this, see the "Creating a service account" section in this doc: [https://cloud.google.com/docs/authentication/getting-started](https://cloud.google.com/docs/authentication/getting-started)
2. In DoubleLoop, select on a metric on the map.
3. Click the "Source" option in the toolbar.
4. In the Source menu in the right side drawer, click "Add Source."
5. Select Google Big Query and click Next.
6. Upload the credentials file (see step #1) and follow the steps.
7. Input the query into DoubleLoop for the metric. The output of the query must contain columns named "date" and "value". We recommend that you test out the query in BigQuery before you input it into DoubleLoop.
   * To import segmented data, see the data format [here](data-segmentation.md).
8. Click "Save".
9. You can import data immediately by clicking "Run now". Moving forward, the data will import on daily basis.

If you get stuck, please reach out!
