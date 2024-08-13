---
description: Learn how to populate metrics in DoubleLoop via Mixpanel
---

# Mixpanel integration

## Overview

DoubleLoop enables teams to align on their metrics-driven strategy. After populating your DoubleLoop map with live data from Mixpanel, you can make sense of how your product metrics ladder up to your business objectives to analyze which of your initiatives are driving impact.

To get a general overview of DoubleLoop, see our [demo video](https://www.loom.com/share/395283236e414e89bfd0a5cbef0b51b3).

## Instructions

### 1. Add Mixpanel as a metric source

1. After logging into your DoubleLoop account, go to the [integrations page](https://app.doubleloop.app/settings/integrations).
2. In the "Metrics" section, click "Add integration".
3. Select "Mixpanel"
4. Enter your project id and the username/password for your Mixpanel service account. See [here](https://docs.mixpanel.com/docs/orgs-and-projects/managing-projects#viewing-project-information) for information regarding your project id. See [here](https://developer.mixpanel.com/reference/service-accounts) for instructions on how to create a service account, make sure to grab the password as it's only available during creation.
5. Click Save

Note: you can create multiple Mixpanel sources in DoubleLoop for multiple Mixpanel projects.

### 2. Populate your DoubleLoop metric with Mixpanel data

1. On one of your strategy maps in DoubleLoop, select a metric.
2. In the toolbar, click "Data Source".
3. In the source menu in the side drawer, select your Mixpanel source.
4. Select an event type of "Event Data" or "Insights Report".
5. Complete the form by either filling in the event name or the URL of the insights report.
6. Make sure the region matches where your Mixpanel data is stored, US or EU.
7. Save changes.
8. Go to the "Data" tab in the side drawer for the metric to see the data that was imported from Mixpanel. Note: this might take a few minutes for larger data sets.

Moving forward, DoubleLoop will import your metric data daily at the time of your choosing, or you can manually click "run now" to kick off the data import process.
