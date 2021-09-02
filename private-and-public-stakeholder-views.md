---
description: Learn how to make public or private release notes or changelogs.
---

# Private & public stakeholder views

## Intro

A big reason to use DoubleLoop is to quickly create views of your release notes, changelogs, or initiatives that you can share with your stakeholders or customers. This doc explains how it works.

## What is a "stakeholder view"?

For every "view" in DoubleLoop, the system automatically creates a stakeholder view. A stakeholder view is a read-only page that can be easily digested by stakeholders or customers. To see an example, check out[ our own changelog for DoubleLoop](https://app.doubleloop.app/p/DoubleLoop/440).

You can quickly navigate to the stakeholder view for any of your views via your dashboard.

![](.gitbook/assets/image%20%2812%29.png)

## Controlling access

By default,  your stakeholder views are private such that login is required to access them. However, you can make them public if you'd like to open access to folks outside your company, like customers.

To go to the settings, click the gear icon for a view.

![](.gitbook/assets/image%20%2813%29.png)

In the settings modal, click "access."

![](.gitbook/assets/image%20%2814%29.png)

Here's how each access option works:

<table>
  <thead>
    <tr>
      <th style="text-align:left">Access option</th>
      <th style="text-align:left">When to use it</th>
      <th style="text-align:left">How it works</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Private</td>
      <td style="text-align:left">Use it when your view contains sensitive data that would be dangerous
        to leak outside your company.</td>
      <td style="text-align:left">
        <p>Only users who are logged into DoubleLoop can access it.</p>
        <p></p>
        <p>The page will not be listed by search engines.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Private with token access</td>
      <td style="text-align:left">Use it when you want to make it easy for a select group of stakeholders
        or customers to access it without logging in, but you don&apos;t want it
        to be fully public.</td>
      <td style="text-align:left">
        <p>To load the page, you need the correct token in the URL. If your URL with
          the token gets in the wrong hands, let us know and we&apos;ll generate
          a new token for you to expire the old links.</p>
        <p></p>
        <p>The page will not be listed by search engines.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Public</td>
      <td style="text-align:left">Use it when you want to make your page accessible without login to your
        customers or the general public.</td>
      <td style="text-align:left">Anyone with the link can access it.
        <br />
        <br />Search engines can list it.</td>
    </tr>
  </tbody>
</table>

