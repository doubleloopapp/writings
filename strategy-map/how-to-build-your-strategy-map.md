---
description: Learn how to use DoubleLoop's interface for building a strategy map.
---

# How to build your strategy map

After you understand the [concepts of the strategy map](strategy-map-concepts.md), you can build your map in DoubleLoop. Your strategy map is a graph of relationships between workstreams and metrics.

## Adding metrics

Click the "Add metric" button to add a metric to your map. Here are the fields for metrics:

### Name

This is the primary name that appears on the map. You can use a pithy name and add more detail in the description fields.

### Type

There are two possible values:

* **Counts**. E.g., unique users.
* **Percentages**. E.g., conversion rate. Displays with a percentage sign.

### Plain language description

Help others understand what the metric is.

### Technical description

Explain in detail how to calculate the metric. It's a good way to communicate requirements to the person instrumenting the metric.

### URL

Do you have a report or dashboard where you can view this metric? Add the URL here. You can then open the URL by clicking the below icon on the metric node.

![Open the URL for a metric.](<../.gitbook/assets/Screen Shot 2021-12-29 at 2.10.57 PM.png>)

### Show on strategy map

When toggled "on," the node appears on the strategy map. If you toggle it off, you can still access it in your metrics list via the left nav.

### Workstreams impacting this metric

The specified workstreams will have arrows that **point to the metric** you're editing.

### Metrics impacting this metric

The specified metrics will have arrows that **point to the metric** you're editing.

### Metrics impacted by this metric

The metric your editing will have arrows that **point to the specified metrics**.

### Strategy Type

There are three possible values:

1. **Input**
2. **North Star**
3. **KPI**

To understand the purpose of each type, check out the [strategy map concepts](strategy-map-concepts.md#metrics-types) page.

## Adding workstreams

Click the "Add workstream" button to add a metric to your map. Here are the fields for metrics:

### Name

The name of a workstream might correspond to a project, initiative, team, or epics; e.g., "Optimize the checkout flow" or "Marketing."

### Description

Provide some context about the workstream and why it's important.

### URL

Is there a place where you can learn more about this workstream or see the activity? Enter the URL. It could be a link to a tool or wiki page. You can then open the URL by clicking the below icon on the metric node.

![Open the URL for a workstream.](<../.gitbook/assets/image (16).png>)

### Workstream type

There are four possible values:

* Product
* Engineering
* Marketing
* Sales

To understand the purpose of each type, check out the [strategy map concepts](strategy-map-concepts.md#workstream-types) page.

### Show on strategy map

When toggled "on," the node appears on the strategy map. If you toggle it off, you can still access it in your workstreams list via the left nav.

### Metrics impacted by this workstream

The workstream your editing will have arrows that **point to the specified metrics**.

_Note: The tool doesn't allow you to have workstreams influenced by metrics or other workstreams. If you think this should change, let us know via Intercom below._

## Editing

To edit any of the fields described above for metrics or workstreams, click the pencil icon on the node:

![](<../.gitbook/assets/image (15).png>)

## Deleting

To permanently delete a node, edit the node and then click the delete button in the bottom left of the modal. Alternatively, you can merely hide the node in the strategy map without deleting it by toggling "Show on strategy map"  off.

