---
description: Learn how to add Microsoft Excel data to DoubleLoop via Zapier
---

# Excel (Online) via Zapier

This is not as easy as we want it to be. If you run into bumps, send us an Intercom message or [schedule a time with us](https://calendly.com/doubleloop/metric-service) and we can do it together.&#x20;

## Instructions

With these instructions, you'll setup a new Zap to send new rows in Excel to either a new metric or a new event in DoubleLoop.

**1. Open the template of the zap** by clicking [here for metrics](https://zapier.com/webintent/create-zap?referrer=member-home-make-a-zap\&create=true\&entry-point-location=dashboard\&entry-point-method=make\_a\_zap\_module\&template\_\_0\_\_selected\_api=ExcelAPI\&template\_\_0\_\_type\_of=read\&template\_\_0\_\_action=new\_table\_row\&template\_\_1\_\_selected\_api=DoubleLoopCLIAPI@1.1.0\&template\_\_1\_\_type\_of=write\&template\_\_1\_\_action=add\_analytic\&template\_\_0\_\_title=Add%20analytic%20in%20DoubleLoop%20when%20new%20row%20in%20table%20in%20Microsoft%20Excel) or [here for events](https://zapier.com/webintent/create-zap?referrer=member-home-make-a-zap\&create=true\&entry-point-location=dashboard\&entry-point-method=make\_a\_zap\_module\&template\_\_0\_\_selected\_api=ExcelAPI\&template\_\_0\_\_type\_of=read\&template\_\_0\_\_action=new\_table\_row\&template\_\_1\_\_selected\_api=DoubleLoopCLIAPI@1.1.0\&template\_\_1\_\_type\_of=write\&template\_\_1\_\_action=add\_entity\&template\_\_0\_\_title=Add%20event%20in%20DoubleLoop%20when%20new%20row%20in%20table%20in%20Microsoft%20Excel). ****&#x20;

* The following screenshots show the event template but the steps are the same for metrics.

**2. Connect your Excel account to Zapier**, it should look like this when you are finished:

![Excel Connected](<../.gitbook/assets/Screen Shot 2022-01-31 at 5.06.44 PM.png>)

**3. Select an Excel Spreadsheet** you would like to connect and select a Worksheet.&#x20;

* <mark style="color:red;">Make sure your sheet has column headers.</mark>

![](<../.gitbook/assets/Screen Shot 2022-01-31 at 5.11.00 PM.png>)

**4. Test the trigger** to make sure you've selected the correct Spreadsheet.

![](<../.gitbook/assets/Screen Shot 2022-01-31 at 5.12.57 PM.png>)

**5. Select your DoubleLoop account** or connect a new one if needed.

![](<../.gitbook/assets/Screen Shot 2022-01-31 at 5.17.24 PM.png>)

**6. Map your Excel columns** to the fields listed.

* For events, we recommend you add a value for the "Labels" field so you have a way of filtering for these events in DoubleLoop.



![](<../.gitbook/assets/Screen Shot 2022-01-31 at 5.20.30 PM.png>)

**6. Verify the data** to be sent matches what you expect and run the test.

**7. Turn on the Zap.** When rows are added to the Excel Spreadsheet they will now show up in DoubleLoop.
