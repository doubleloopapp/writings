---
description: Learn the mechanics of workstreams.
---

# How to setup workstreams

To learn more about why workstreams are useful, go [here](about-workstreams.md). This page describes the mechanics of using workstreams.

## Overview

**Key concept: workstreams are filtered views of events. An event appears in a workstream if it matches the criteria of the workstream filter.**

We built workstreams to use filters so that you can send noisy hire hoses of information to DoubleLoop from other tools (like Jira) and use filters to separate the signal from the noise.

By default, all workstreams are created with a _label_ filter based on the name of the workstream. Any event with that label will appear in the workstream.

For example, if you create an event manually in DoubleLoop, you can add a label to it. That event will appear in workstreams with that label filter. If you are in a workstream and click "Add event", by default it will have the label to make it appear in that workstream.

If you connect your building tools like Jira, Linear, Shortcut, or GitHub to DoubleLoop, DoubleLoop will import events from those tools including their labels and other metadata. Therefore, you could create a workstream in DoubleLoop for "Marketing" and have it filter for events with the label "Marketing." If you label issues in Jira with the label "Marketing," those events will appear in that workstream in DoubleLoop.

You can also filter by other classifications that come from your source tools, like epic, project, status, etc..

### Demo of setting up workstreams

{% embed url="https://www.loom.com/share/3caab790ee214518b0cae5e3664d07db" %}







