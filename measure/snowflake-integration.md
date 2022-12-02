---
description: Learn how to populate metrics in DoubleLoop via Snowflake.
---

# Snowflake integration

DoubleLoop allows you to populate your metrics in DoubleLoop with time-series data from Snowflake. Here's how to do it.

1.  Get your Snowflake **Host**, **Port**, **Warehouse name**, **Database name**, **Schema name**, **Username**, and **Password** ready, or ask your IT team for assistance in getting this information for your Snowflake instance. If your connection requires Snowflake roles, you'll need that as well.

    <mark style="color:red;">**Important**</mark><mark style="color:red;">: If your Snowflake instance is configured for IP based security, our outbound IP addresses are 35.160.120.126, 44.233.151.27, and 34.211.200.85.</mark>
2. In DoubleLoop, double-click on a metric on the map.
3. Click the "Source" tab in the right drawer.
4. Fill in your Host with either the domain name or IP address of your Snowflake instance **without the https:// or the trailing slash**.
5. Fill in the Port with your port, the default for Snowflake is 443.
6. Fill in your Snowflake warehouse name, database name, schema name, username, and password.
7. Input the query into DoubleLoop. The output of the query must contain columns named "date" and "value". We recommend that you test out the query in Snowflake before you input it into DoubleLoop.
8. Click "Save".

If you get stuck, please reach out!

![](<../.gitbook/assets/image (1).png>)
