---
description: Learn how to add Google Sheets data to DoubleLoop via Zapier
---

# Google Sheets via Zapier

This is not as easy as we want it to be. If you run into bumps, send us an Intercom message or [schedule a time with us](https://calendly.com/doubleloop/metric-service) and we can do it together.&#x20;

## Instructions

With these instructions, you'll setup a Zap to send new rows in Google Sheets to either a new metric or new event in DoubleLoop.

**1. Open the template of the zap** by clicking [here for metrics](https://zapier.com/webintent/create-zap?referrer=member-home-make-a-zap\&create=true\&entry-point-location=dashboard\&entry-point-method=make\_a\_zap\_module\&template\_\_0\_\_selected\_api=GoogleSheetsV2API\&template\_\_0\_\_type\_of=read\&template\_\_0\_\_action=new\_row\_notify\_hook\&template\_\_1\_\_selected\_api=DoubleLoopCLIAPI@1.1.0\&template\_\_1\_\_type\_of=write\&template\_\_1\_\_action=add\_analytic\&template\_\_0\_\_title=Add%20analytic%20in%20DoubleLoop%20when%20new%20spreadsheet%20row%20in%20Google%20Sheets) or [here for events](https://zapier.com/webintent/create-zap?referrer=member-home-make-a-zap\&create=true\&entry-point-location=dashboard\&entry-point-method=make\_a\_zap\_module\&template\_\_0\_\_selected\_api=GoogleSheetsV2API\&template\_\_0\_\_type\_of=read\&template\_\_0\_\_action=new\_row\_notify\_hook\&template\_\_1\_\_selected\_api=DoubleLoopCLIAPI@1.1.0\&template\_\_1\_\_type\_of=write\&template\_\_1\_\_action=add\_entity\&template\_\_0\_\_title=Add%20event%20in%20DoubleLoop%20when%20new%20spreadsheet%20row%20in%20Google%20Sheets). ****&#x20;

* The following screenshots show the event template but the steps are the same for metrics.

**2. Connect your Google account to Zapier**, it should look like this when you are finished:

![](<../.gitbook/assets/Screen Shot 2022-01-31 at 4.39.08 PM.png>)

**3. Pick a Google Sheet** you would like to connect and select a Worksheet.&#x20;

* <mark style="color:red;">Make sure your sheet has column headers.</mark>

**4. Choose which fields you want to map.** For events title, importance, and date are required. For metrics, date and value are required however they do not need to be named this in Google Sheets.

![Event example](<../.gitbook/assets/Screen Shot 2022-01-31 at 4.46.17 PM.png>)

**5. Map your fields.** Click into each field and select the appropriate row from your spreadsheet. They will show up with the headers from your Google Sheet.

* <mark style="color:red;">Pay close attention to the</mark> <mark style="color:red;"></mark><mark style="color:red;">`When did the event occur`</mark> <mark style="color:red;"></mark><mark style="color:red;">field as the default is today.</mark>
* We recommend you add a value for the "Labels" field so you have a way of filtering for these events in DoubleLoop.

![Event fields mapped to Google Sheets Columns](<../.gitbook/assets/Screen Shot 2022-01-31 at 4.48.42 PM.png>)

**6. Verify the data** to be sent matches what you expect and run the test.

**7. Turn on the Zap.** When rows are added to the Google Sheet they will now show up in DoubleLoop.
