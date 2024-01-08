---
description: >-
  Import your KPIs or metrics into DoubleLoop to see actions and outcomes in one
  place. It's the best way to align a team around an initiative.
---

# Looker API integration

## How to setup the Looker API Key

**Important note**: to setup the Looker integration, you may need to be a Looker admin.

1. If you haven't already, [create your DoubleLoop account](https://app.doubleloop.app/sign\_up).
2.  In Looker, go to the "Users" screen in the admin section.

    ![](<../.gitbook/assets/doubleloop.cloud.looker.com\_admin\_next\_users (1).png>)
3. Choose or create a User that you'd like to give API access. We recommend creating a user specifically for DoubleLoop. Once you've chosen, click on that User.
4. On the User page, click the `Edit Keys` button next to the API Keys label which will open the users API Key manager.\
   ![](../.gitbook/assets/doubleloop.cloud.looker.com\_admin\_users\_api3\_key\_4.png)
5. Add a new API Key and make note of the Client ID and Client Secret as we will need those to configure the Integration in DoubleLoop.
6. This is also a great time to grab the Looker API Host URL we'll need as well if you don't know if already. It can be find in the Looker Admin area under `Platform -> API`.\
   ![](<../.gitbook/assets/doubleloop.cloud.looker.com\_admin\_api (1).png>)

## Setting up the DoubleLoop Integration

1. Go to the [DoubleLoop Integrations Page](https://app.doubleloop.app/settings/integrations) and click `+ Add Integration`.\
   ![](../.gitbook/assets/app.doubleloop.app\_settings\_integrations.png)
2. In the popover choose Looker API and hit \`Next\`.&#x20;
3. Fill in the details in the popover, we suggest giving your integration an easy to remember name to help keep track of the integration.
4. In the API endpoint field, use the Looker API Host URL mentioned above making sure to add `/api/4.0` on the end to match the placeholder text.
5. Finally, use the `Test credentials` button to test that it's all setup correctly and hit `Save` to finish setting up the integration.

## How to configure a metric with the Looker API Integration

1. Create a Metric in DoubleLoop and click on the `Source` tab.
2. Click on the Source dropdown and choose the Integration we created above.![](<../.gitbook/assets/app.doubleloop.app\_settings\_integrations (1).png>)\

3. Select your Look, which will then fetch the fields from that Look and show a list of available fields for the Date and Value for DoubleLoop to parse. Optionally, pick an Import time if the default does not work for you. \
   ![](<../.gitbook/assets/app.doubleloop.app\_settings\_integrations (2).png>)
4. Finally, save the changes. An automatic historical import will be started and new daily metric data should begin to flow into DoubleLoop.&#x20;
5. If you need to update your Looker configuration in DoubleLoop, click on the `Source` tab, then the `Edit` button, and finally make any necessary edits.
