---
description: Learn about manually recording events in DoubleLoop.
---

# Manually recording events

Some companies choose to import events into DoubleLoop through one of the tool integrations. Others choose to record events manually. Some do a mix of both.

For those who enter events manually, here are some instructions and organizational tips.

## Why record events in DoubleLoop?

This question is largely answered on the [About workstreams](about-workstreams.md) page. TLDR; the reason to record events in DoubleLoop is to:

1. Understand how different events impact metrics.
2. Communicate product releases or other activities to stakeholders.

## What types of events should you record?

It's entirely up to you. If the event could have impacted your business, record it!

The most common type of recorded events are product changes, like feature enhancements, product launches, or bug fixes.

However, many companies record events for all types of work; marketing campaigns, sales, business development, customer success, engineering, etc.

You can record events for things you control and for things that you don't control. For example, if the beginning of Covid or the war in Ukraine impacted your business, record it.

## Adding events

There are two places where you can manually create events.

### Adding events from the "All events" page

1. Go to the [All events](https://app.doubleloop.app/events) page.
2. Click "Create event"

By default, events you add this way will only appear on the "All events" page. If you want the event to appear in a workstream, add a label to the event that corresppnds to that workstream.

### Adding events from the "Workstreams" page

1. Navigate to the workstream page via a strategy map or the [workstream listing](https://app.doubleloop.app/workstreams) page.
2. Click "Create event."

If the workstream has a label assigned to it, the event will automatically have that label applied so that it will appear in the given workstream.

## Event fields

Here's a quick explanation of each event field. All of the fields are optional except for the title, data, and importance.

* **Event title**. The headline that appears wherever the event info is displayed. Example: "Homepage redesign went live."
* **When did the event occur**. The date of the event. Example: the date the product enhancement was released.
* **Importance**. The significance of the event. It determines how prominently the event is displayed in some views.
* **Impact.** When you set the impact for an event, it will appear as an annotation in the timeline on the workstream and all events pages. Positive impact displays in green. Negative impact displays in red.
* **Summary**. A description of the event.
* **Goal / Hypothesis**. When applicable, explain why the change was made. For example: "Our hypothesis is that, by making the button bigger, the conversion rate will increase."
* **Results**. After time passes, you can record the impact of the change. Example: "The conversion rate increased from 2% to 3%.
* **Type**. Record if the change was a fix, enhancement, chore, improvement, etc..
* **URL title.** A call-to-action to learn more about the event. Example: "Watch the demo!"
* **URL.** The URL where you can learn more, corresponding with the URL title.
* **Labels**. Make it easy to find the event later or add the event to a workstream that filters by label.
* **Contributors**. List the people who worked on the change; the PM, engineer, designer, etc. Give props!



## Viewing events

### All events page

The [All events](https://app.doubleloop.app/events) page has every event that has been recorded. You can filter events to drill down as desired. The metric dropdown has your full list of metrics so you can analyze the impact of events on any metric.

### Workstreams

[Workstreams](about-workstreams.md) are filtered views of events that normally correspond to projects, initiatives, or teams; e.g., customer acquisition, UX improvements, and marketing campaigns.

When new workstreams are created, by default they are assigned a label based on the name of the workstream. You can change the workstream filters as desired.

A benefit to using workstreams is that you can share release notes with stakeholders. Check out [our changelog](https://app.doubleloop.app/changelogs/impact-log), as an example.

## Looking record events automatically?

You can record events automatically based on your tool activity. Check out the integrations under "Workstreams" in the left nav. Or you can use the [events endpoint in the DoubleLoop API](https://app.doubleloop.app/apidocs/1.0/zapier/create\_entity.html) to record events.





##
