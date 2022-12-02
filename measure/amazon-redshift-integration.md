---
description: Learn how to populate metrics in DoubleLoop via Amazon Redshift.
---

# Amazon Redshift integration

DoubleLoop allows you to populate your metrics in DoubleLoop with time-series data from Redshift. Here's how to do it.

1.  Get your Amazon Redshift Host, Port, Database Name, Username, and Password ready, or ask your IT team for assistance in getting this information for your Amazon Redshift instance.

    <mark style="color:red;">**Important**</mark><mark style="color:red;">: You will need to make sure the Amazon Redshift instance is reachable over the internet.</mark>
2. In DoubleLoop, double-click on a metric on the map.
3. Click the "Source" tab in the right drawer.
4. Choose "Amazon Redshift" as the source.
5. Fill in your Host with either the domain name or IP address of your Amazon Redshift instance.
6. Fill in the Port with your port, the default for Amazon Redshift is 5439.
7. Fill in your Amazon Redshift database name, username, and password.
8. Input the query into DoubleLoop. The output of the query must contain columns named "date" and "value". We recommend that you test out the query in Redshift before you input it into DoubleLoop.
9. Click "Save".

If you get stuck, please reach out!

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>
