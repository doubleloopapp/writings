---
description: Learn how to use DoubleLoop's amplitude integration
---

# Amplitude integration

## Overview

DoubleLoop enables teams to align on their metrics-driven strategy. After populating your DoubleLoop map with live data from Amplitude, you can make sense of how your product metrics ladder up to your business objectives to analyze which of your initiatives are driving impact.

To get a general overview of DoubleLoop, see our [demo video](https://www.loom.com/share/395283236e414e89bfd0a5cbef0b51b3).

## Example DoubleLoop map with Amplitude data

<figure><img src="https://lh7-us.googleusercontent.com/YwG1Q65-fESb5WV710nh5KbDYM5WVEYpfAPsLpHe65lfg1VMvt9qA2QUvPVhTJUnJ_3ZzXy7e1FIIVkB9ZAaLilAO-yBHDu0yYSwCvQtoA_Ih4sxjtQTBBP-SmRTBTszQa57MAl-QtL1rK5mITbHvl0" alt=""><figcaption></figcaption></figure>

## Instructions

### 1. Add Amplitude as a data source

1. After logging into your DoubleLoop account, go to the [integrations page](https://app.doubleloop.app/settings/integrations).
2. In the "Metrics" section, click "Add integration."
3. Select "Amplitude"
4. Enter your API key and Secret key. See [here](https://www.docs.developers.amplitude.com/analytics/find-api-credentials/) for where to find this info.
5. Click "Save.

Note: you can create multiple Amplitude sources in DoubleLoop for multiple Amplitude proejcts.

### 2. Populate your DoubleLoop metric with Amplitude data

{% embed url="https://share.cleanshot.com/PTqSZqWX" %}

1. On one of your strategy maps in DoubleLoop, select a metric.
2. In the toolbar, click "Data source"
3. In the source menu in the side drawer, select your Amplitude source.
4. Select a query type of "Event" or "Chart".
   * Note: "Chart" is recommended for more flexibility.
5. Complete the form by either selecting an event of entering a chart URL (like this one:`https://app.amplitude.com/analytics/doubleloop/chart/jkf5qy9b`
   * Note: DoubleLoop is only be able to import charts with time series data; dates and values.
6. Save changes.
7. Go to the "Data" tab in the side drawer for the metric to see the data that was imported from Amplitude.

Moving forward, DoubleLoop will import your metric data daily at a time of your choosing, or you can manually click "run now" to immediately update the data.

## Future vision

The current Amplitude integration makes it easy to pull in Amplitude metrics into DoubleLoop one metric at a time.

Our future vision for the integration is to seamlessly pull in Amplitude metrics en masse into DoubleLoop.

Examples:

* After connecting DoubleLoop to Amplitude, we could automatically populate your metric library in DoubleLoop with all of your charts (limited to charts with time series data).
* We could enable you to select an Amplitude funnel and automatically create a DoubleLoop map for your funnel, populated with data.
* We could enable you to select an Amplitude dashboard or notebook and automatically add all included metrics to your DoubleLoop map.
