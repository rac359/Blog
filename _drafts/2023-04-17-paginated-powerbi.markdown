---
layout: post
tag: "Power BI"
title: "Paginated Power BI - Greasing the Groove"
---

Traditional reports, in my experience, have always been delivered via PDF. Larger corporations or companies with more sophisticated reporting operations may use something like SSRS or another reporting server, but many companies simply design their reports in Excel or Word and export to PDF. Senior folks like being able to print something out, carry it around, reference it, and eventually store it. However technology stops for nobody, and there are more modern ways of generating
reports.

Tools like Salesforce's Tableau and Microsoft's Power BI have entered the market, and allow users to basically have any report that they want, simply by manipulating slicers on the report. The advantages of this are obvious, but adopting it isn't. Folks who are used to receiving one or many reports via PDF suddenly now need to go to a website and click around to get the information they want or need. And what's worse, is that the data on the report may not natively print, which
makes sharing the data more difficult.

Microsoft's Paginated reports through Power BI is a product that can help ease the transition from legacy report servers to dynamic reporting dashboards. Paginated reports are effectively SSRS reports, but have the added advantage of utilizing Power BI datasets and they can be embedded in traditional Power BI reports. As users receive scheduled paginated reports through the web service, they can click through and interact with them in a way not dissimilar from how SSRS functions
via browser.

I encourage readers that use Power BI to try paginated reports with their users. This product may be especially useful for those that are struggling to gain traction with adoption for other Power BI reports that have already been deployed.
