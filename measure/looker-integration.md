---
description: >-
  Import your KPIs or metrics into DoubleLoop to see actions and outcomes in one
  place. It's the best way to align a team around an initiative.
---

# Looker integration

## How to enable Looker integration

**Important note**: to turn on Looker integration, you may need to be a Looker admin.

1. If you haven't already, [create your DoubleLoop account](https://app.doubleloop.app/sign\_up).
2.  In Looker, go to the "Actions" screen in the admin section.

    <img src="https://lh5.googleusercontent.com/WbhzV8d10brLouNCrNZnMh_YNl34wYTSMcyFc6Y0PHTlpWESXrtbfXMiD8w09aSoOPevPsOajhKTo8UAAxX_wCw-Vec59Ej-AH8yX6asVnxhWqMk2yj0DA7GqtqQn115L66uobUX" alt="" data-size="original">
3. Click `Add Action Hub`.
4. Add the Action Hub Url: `https://app.doubleloop.app/looker`
5.  Click the `Enable` button on the Track Metric action. This will bring up the Action configuration. Grab your API key from the DoubleLoop [Integrations](https://app.doubleloop.app/settings/integrations) page or from any newly created Metric Looker Data Source and paste it into the API Key box. Make sure to toggle the `Enabled` slider and click `Save`.

    <img src="https://lh4.googleusercontent.com/puEdxX1fDJRlfZFP_UxkS4gqn3ZagXMCh4Gxy2yEZGLWeoMJEst3JfZ_df-O8v2JkVWnSnECVBWkFvO6bzbDW3WWEmX7eD1XddFScmVvE7afKBB9nsrsJj_mwi2VgfuEQ5jTb3Ch" alt="" data-size="original">

## How to send metrics from Looker to DoubleLoop

1. Create a Metric in DoubleLoop and add a Looker Data Source. This can either be done from the [metrics list](https://app.doubleloop.app/metrics) or via the strategy maps by clicking `+ Metric`, clicking the (i) icon on the newly created metric, and switching to the `Data Source` tab.\
   ![](<../.gitbook/assets/staging.doubleloop.app\_strategy\_885(Desktop) (1).png>)
2. Fill in the Date field and Value field boxes, they should match the **bold** part of the table column name in the Looker Looks data table. In the example below, you would use `date date`  and `created`. \
   \
   _If you have any issues here, continue following the instructions below and let us know when you're finished, we'll be glad to help you figure out what values to use._\
   <img src="../.gitbook/assets/Screen Shot 2022-08-18 at 9.54.16 AM.png" alt="" data-size="original">
3. Find the Looker Look that contains the metrics you’d like to provide to DoubleLoop. \
   <mark style="background-color:yellow;">**The Look must contain at least one date field and one value field.**</mark>
4.  From the Look configuration menu, choose the \`Schedule...\` option.

    <img src="https://lh4.googleusercontent.com/c0vBVEigZRLQ3ld-WJj2ZRL6m0K6zGEiAGrJtkeaoJeGZU08vndfw3pfxyCFA_rq4QDkCd7GSO5mwcpWFXDRDB54Rvc8ZFGN2PXxqWRwI07mQ-QcBTRPKoTDS9daSNDWyUqpTGYL" alt="" data-size="original">
5.  Give your Schedule a memorable name, choose the DoubleLoop metric you'd like to receive data from the `DoubleLoop Metric Source` dropdown, and pick how often you’d like it to send (we suggest daily). Hit `Send Test` followed by `Save All`. \
    \
    _Optionally, if you'd like to control the number of records sent to DoubleLoop, expand the Advanced options section._

    <img src="../.gitbook/assets/Screen Shot 2022-08-18 at 9.23.52 AM.png" alt="" data-size="original">\
    \
    <mark style="background-color:yellow;">**Looker restricts the number of records a Look can send. If you go over the Look limit, you will need to limit the Look itself, outside of the schedule's filter options.**</mark>&#x20;
6. To see your Looker data in DoubleLoop, either visit the [metrics list](https://app.doubleloop.app/metrics) and pick the metric you chose in the Look Schedule window or find it on your strategy map and double-click on the metric or click the (i) icon.\
   ![](../.gitbook/assets/staging.doubleloop.app\_strategy\_885\(Desktop\).png)
7. If you need to update your Looker configuration in DoubleLoop, click on the `Data Source` tab and make any necessary edits.
