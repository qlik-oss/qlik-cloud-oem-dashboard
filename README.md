> **Warning**
> This application is _community supported_. This means that you should not contact
> Qlik Support for help with this app. See below for additional information
> on how to raise issues on this repository to ask for help.

# Qlik Cloud OEM Dashboard & Console Settings Collector

> **Note**
> This application is one of a set of community built and supported monitoring apps for Qlik Cloud.
> For links to all monitoring apps, visit the [Qlik Cloud Monitoring Apps](https://github.com/qlik-oss/qlik-cloud-monitoring-apps) repository.

The OEM Dashboard is a Qlik Sense application for Qlik Cloud designed for OEM
partners to centrally monitor usage data across their customers’ tenants. It
provides a single pane to review numerous dimensions and measures, compare trends,
and quickly spot issues across many different areas.

Although this dashboard is designed for OEMs, it can also be used by partners and
customers who manage more than one tenant in Qlik Cloud.

![Sheets in the OEM Dashboard](/images/readme_sheets.png)

This application pulls data from the App Analyzer, Entitlement Analyzer, and
the Reload Analyzer, all of which are other monitoring applications for Qlik Cloud.
By bringing this data together, it simplifies and streamlines management of an
OEM environment.

For more information on Qlik’s differentiating multi-tenant approach, please
review [this video](https://www.qlik.com/blog/extending-the-power-of-qlik-sense-saas-for-oem-partners). 

The OEM Dashboard is provided with an optional data source, the Console Settings
Collector application, which collects configuration information from each tenant.

## Installing / Updating

A PDF containing installation instructions is attached to each [release](/../../releases).

## Subscription Compatibility

Some monitoring apps are designed for specific Qlik Cloud subscription types. Refer to the compatibility matrix within the [Qlik Cloud Monitoring Apps](https://github.com/qlik-oss/qlik-cloud-monitoring-apps?tab=readme-ov-file#applications) repository.

## Support policy

This app is provided as-is and is not supported by Qlik. Over time, the APIs and
metrics used by the app may change, so it is advised to monitor this repository
for updates, and to update the app promptly when new versions are available.

If you have issues while using this app, support is provided on a best-efforts
basis by contributors to this project.

If you have an issue:

* Review the FAQ section in this readme to see if your issue is a common one
* Review open and closed [issues](/../../issues)
* Open a [new issue](/../../issues/new), following the issue template

If you are able to resolve the issue, then close your issue with the resolution,
and if you feel inclined, open a PR with your proposed changes so that we can
consider including the improvement in the next release of the app.

Thank you for your support!
