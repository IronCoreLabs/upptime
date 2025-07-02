---
name: Scheduled Downtime Template
about: Add issue to suppress outage reporting during scheduled maintenance.
title: Scheduled Maintenance <DATE>
labels: maintenance
assignees: ''

---

System maintenance is scheduled for <Add date and start time, specifying timezone>.
The following services will be unavailable during maintenance: <list services affected>
We anticipate the service unavailability to last approximately <add expected duration>.

<Explain how this will affect customers - for example:
During that time, admins won't be able to access the Config Broker UI, and new TSPs won't be able to start up while the Config Broker is not available. Currently operating TSPs will continue to function normally. The identity service will not be available to handle DCP requests.
>

<!--
start: <specify start time - for example 2025-04-06T18:00:00+00:00>
end: <specify end time - for example 2025-04-06T18:30:00+00:00>
expectedDown: <specify service names - for example admin-console,cloaked-search-demo,cloaked-search-demo-backend-search-service,config-broker,config-broker-static-content,iron-core-identity-service,saa-s-shield-for-s3-demo>
-->
