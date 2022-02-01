---
description: Learn how to add Google Analytics metrics to DoubleLoop through Zapier
---

# Google Analytics integration via Zapier

If you need metrics from Google Analytics that aren't provided by our Google Analytics integration you can also get metrics into DoubleLoop from Google Analytics through Zapier.

This is not as easy as we want it to be. If you run into bumps, send us an Intercom message or [schedule a time with us](https://calendly.com/doubleloop/metric-service) and we can do it together.

**Note: it requires a paid Zapier account since it's a "multi-step" Zap.**

## Instructions

With these instructions, you will setup a daily job to send a specific metric from Google Analytics to DoubleLoop every day at a time of your choosing.

**1. Open the template of the zap** by clicking [here](https://zapier.com/app/editor/118237268/nodes/118237268/fields).

**2. Set the trigger.** The default is for it to run every day, including weekends, at 4am. There's no need to change this.

![](<../.gitbook/assets/Screen Shot 2022-01-13 at 8.43.40 PM.png>)

**3. Click "Test the trigger" and then "Continue."**

![](<../.gitbook/assets/Screen Shot 2022-01-13 at 8.47.37 PM.png>)

**4. Click "Run Report in Google Analytics."**

![](<../.gitbook/assets/Screen Shot 2022-01-13 at 8.49.05 PM.png>)

**4. Click "Choose account" and connect your Google Analytics account.**

![](<../.gitbook/assets/Screen Shot 2022-01-13 at 8.51.00 PM.png>)

**5. Click "Setup action."**&#x20;

* Configure "Account," "Property," and "View (Profile)" as you see fit.
* <mark style="color:red;">**Don't edit the "Start date" and "End date" fields**</mark>. These fields indicate that the Zap will grab data from the previous day.
* <mark style="color:red;">**Don't edit the Output Format**</mark>. It must be "Individual Data Points."
* Change "Metrics" to the metric that you want to pull in. Unfortunately, <mark style="color:red;">**you can only do one metric per Zap**</mark>. To pull in another metric you'll need to make another Zap following this same process.
* **Leave the rest of the fields in the "Run Report in Google Analytics" section blank**. It might be possible to use them, but we don't have a good understanding of them yet.

![](<../.gitbook/assets/Screen Shot 2022-01-13 at 8.54.38 PM.png>)

**6. Click "Test action."** After you test it, you should see something like this. You can confirm that the data matches what you see in Google Analytics for that metric from the previous day.

![](<../.gitbook/assets/Screen Shot 2022-01-13 at 9.01.08 PM.png>)

**7. Click "Add analytic in DoubleLoop."**

* Follow the instructions to connect to your DoubleLoop account.
* <mark style="color:red;">**Do not change "Action Event" from "Add Analytic."**</mark>

![](<../.gitbook/assets/Screen Shot 2022-01-13 at 9.03.45 PM (2).png>)

**8. Click "Choose account" to set up the action.**

* **Set the "Analytic name" to be how you want it to appear in DoubleLoop**. Or, if you already have created the metric in DoubleLoop, use the exact name from DoubleLoop.
* <mark style="color:red;">Do not edit the "Date."</mark>
* For value, pick the numeric value from Google Analytics.
* For "Data type" you can choose between "Count" or "Percentage." E.g., "Sessions" would be a count and "Conversion rate" would be a percentage.

![](<../.gitbook/assets/Screen Shot 2022-01-13 at 9.20.02 PM.png>)

**9. Test the action and turn on the Zap.**

**10. Login into DoubleLoop and go to the** [**metrics page**](https://app.doubleloop.app/metrics)**.** You should see a metric with the name you specified in Zapier. If you click on the metric, you should see the data point from your Zapier test.

****![](<../.gitbook/assets/Screen Shot 2022-01-13 at 9.26.45 PM.png>)****

**11. To add the metric to your strategy map,** open the "Settings" for the metric. Toggle the "Show on strategy map" setting to on.

![](<../.gitbook/assets/Screen Shot 2022-01-13 at 9.29.15 PM.png>)

Phew, you're done! Moving forward, every night a data point will be added to DoubleLoop for the Google Analytics metric you chose.

Your historical metric data won't be there yet, unfortunately. However, we can help you with a [CSV upload](upload-metrics-via-a-csv-file.md) to get your historical data in there.
