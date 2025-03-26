---
description: Learn how to populate metrics in DoubleLoop via BigQuery.
---

# BigQuery integration

DoubleLoop allows you to populate your metrics in DoubleLoop with time-series data from BigQuery. Here's how to do it.

### BigQuery Permissions

See [Google's documentation](https://cloud.google.com/iam/docs/service-accounts-create) for information on how to setup a service account and download your credentials file.

#### High-level Permissions

Use the following permissions to quickly get started.

_BigQuery Data Viewer, BigQuery Job User_

#### Granular Permissions

If you prefer more granular permissions, these are the specific required permissions.

_bigquery.jobs.create, bigquery.datasets.get, bigquery.tables.getData, bigquery.tables.list_

### Setup in DoubleLoop

1. In DoubleLoop, select on a metric on the map.
2. Click the "Source" option in the toolbar.
3. In the Source menu in the right side drawer, click "Add Source."
4. Select Google Big Query and click Next.
5. Upload the credentials file from above and follow the steps.
6. Input the query into DoubleLoop for the metric. The output of the query must contain columns named "date" and "value". We recommend that you test out the query in BigQuery before you input it into DoubleLoop.
   * To import segmented data, see the data format [here](data-segmentation.md).
7. Click "Save".
8. You can import data immediately by clicking "Run now". Moving forward, the data will import on daily basis.

If you get stuck, please reach out!
