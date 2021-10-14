---
description: Learn how to make public or private release notes or changelogs.
---

# Private & public stakeholder views

## Intro

A big reason to use DoubleLoop is to quickly create views of your release notes, changelogs, or initiatives that you can share with your stakeholders or customers. This doc explains how it works.

## What is a "stakeholder view"?

For every "view" in DoubleLoop, the system automatically creates a stakeholder view. A stakeholder view is a read-only page that can be easily digested by stakeholders or customers. To see an example, check out[ our own changelog for DoubleLoop](https://app.doubleloop.app/p/DoubleLoop/440).

You can quickly navigate to the stakeholder view for any of your views via your dashboard.

![](<.gitbook/assets/image (12).png>)

## Controlling access

By default,  your stakeholder views are private such that login is required to access them. However, you can make them public if you'd like to open access to folks outside your company, like customers.

To go to the settings, click the gear icon for a view.

![](<.gitbook/assets/image (13).png>)

In the settings modal, click "access."

![](<.gitbook/assets/image (14).png>)

Here's how each access option works:

| Access option             | When to use it                                                                                                                                                  | How it works                                                                                                                                                                                                                                                |
| ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Private                   | Use it when your view contains sensitive data that would be dangerous to leak outside your company.                                                             | <p>Only users who are logged into DoubleLoop can access it.</p><p></p><p>The page will not be listed by search engines.</p>                                                                                                                                 |
| Private with token access | Use it when you want to make it easy for a select group of stakeholders or customers to access it without logging in, but you don't want it to be fully public. | <p>To load the page, you need the correct token in the URL. If your URL with the token gets in the wrong hands, let us know and we'll generate a new token for you to expire the old links.</p><p></p><p>The page will not be listed by search engines.</p> |
| Public                    | Use it when you want to make your page accessible without login to your customers or the general public.                                                        | <p>Anyone with the link can access it.<br><br>Search engines can list it.</p>                                                                                                                                                                               |
