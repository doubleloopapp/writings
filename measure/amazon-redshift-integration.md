---
description: Learn how to populate metrics in DoubleLoop via Amazon Redshift.
---

# Amazon Redshift integration

DoubleLoop allows you to populate your metrics in DoubleLoop with time-series data from Redshift. Here's how to do it.

_Note: we recognize there's a lot of potential to simplify this process. Please let us know what problems you run into or any other feedback._

## Part 1: **Create a "Metric source"**

1.  Get your Amazon Redshift Host, Port, Database Name, Username, and Password ready, or ask your IT team for assistance in getting this information for your Amazon Redshift instance.

    <mark style="color:red;">**Important**</mark><mark style="color:red;">: You will need to make sure the Amazon Redshift instance is reachable over the internet.</mark>
2. In DoubleLoop, go to the page for Metric Sources: [https://app.doubleloop.app/metric\_sources](https://app.doubleloop.app/metric\_sources)
3. Click "Add metric" source.
4. Enter a name for the metric source and optionally a description. The metric source name should be specific to a particular metric you want to create. E.g., it should be something like "# of new subscribers" as opposed to something more generic like "Redshift."
5. Choose "Amazon Redshift" as the source.
6. If a metric already exists that you would like to populate with data from this metric source, enter it into the "Target metric" field. Otherwise, you can connect this metric source to a metric later.
7. Fill in your Host with either the domain name or IP address of your Amazon Redshift instance.
8. Fill in the Port with your port, the default for Amazon Redshift is 5439.
9. Fill in your Amazon Redshift database name, username, and password.
10. Input the query into DoubleLoop. The output of the query must contain columns named "date" and "value". We recommend that you test out the query in Redshift before you input it into DoubleLoop.
11. Click "Save".

## Part 2: **Create a "Metric"**

1. You're going to use the "metric source" you created to populate a "metric" in DoubleLoop. If that metric already exists, skip this step. Otherwise, you can add the metric by clicking "Add metric" from one of your strategies or on the metrics listing page. It's expected that the metric could have the same name as the metric source.
2. In the settings for the metric, for "Metric source," select the metric source you previously created.

![](<../.gitbook/assets/CleanShot 2022-03-07 at 14.52.00@2x.png>)

## Part 3: Confirm it worked

Every night, DoubleLoop will populate data for your metric based on the query you specified for the metric source. So you should see your metric data tomorrow. In the meantime, you can click "Run" to test it.

That's it. Please let us know your feedback. If you have any questions, please contact us.
