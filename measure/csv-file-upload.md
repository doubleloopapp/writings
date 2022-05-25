---
description: Learn how to upload metric data into DoubleLoop with CSV files.
---

# CSV file upload

Our CSV upload tool is a great way to get a lot of metric data into DoubleLoop without integrating your tools or using our API.

There are two ways to use CSV upload in DoubleLoop:

* Upload data points for an individual metric.
* Upload data points for many metrics at once.

## Upload data points for an individual metric

#### **1. Prepare your CSV file.**

Download an example file here:

{% file src="../.gitbook/assets/Example.csv" %}

The file looks like this:

![](<../.gitbook/assets/CleanShot 2022-03-25 at 17.15.05@2x.png>)

Or like this if you open it in Excel:

![](<../.gitbook/assets/CleanShot 2022-03-25 at 17.09.55@2x.png>)

Replace the dates and values with the data you'd like to upload and save the file.

<mark style="color:green;">**Some important notes:**</mark>

1. <mark style="color:green;">**Use the date format yyyy-mm-dd**</mark>
2. <mark style="color:green;">**Make sure you leave "date" and "value" as the headers.**</mark>

**2. Go to the metric in DoubleLoop.**

You can navigate to the metric either from your strategy map or the metric listings page.

#### 3. Click "Upload CSV."

![](<../.gitbook/assets/CleanShot 2022-03-25 at 17.20.40@2x.png>)

#### 4. Upload the file.

After you update the file, you'll need to refresh the page to see the data you uploaded.

## Upload data points for many metrics at once

#### **1. Prepare your CSV file.**

Download an example file here:

{% file src="../.gitbook/assets/batch_upload.csv" %}

The file looks like this:

![](<../.gitbook/assets/CleanShot 2022-05-25 at 15.56.58@2x.png>)

Or like this if you open it in Excel:

![](<../.gitbook/assets/CleanShot 2022-05-25 at 16.00.02@2x.png>)

Each row contains a metric id, date, and value. You can find the metric id&#x20;

![](<../.gitbook/assets/CleanShot 2022-05-25 at 16.02.34@2x.png>)
