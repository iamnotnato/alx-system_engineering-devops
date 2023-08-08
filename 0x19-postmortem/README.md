The following is the incident report for the Ubuntu container’s Nginx Installation error  that occurred on July 3, 2023. We understand this service issue has impacted our valued developers and users, and we apologize to everyone who was affected.

Issue Summary

From 6:13 AM to 7:28 AM EAT, there were errors displayed that showed Failed to connect to 0 port 80: Connection refused
When users tried to check the NGINX installation. At its peak, the issue affected 100% of users on this server. Users could not access the configuration.The root cause of this outage was an invalid configuration change 

Timeline (all times East African Time)
6:13 AM: Configuration push begins
6:28 AM: Outage begins
6:44 AM: Failed configuration change rollback
7:12 AM: Successful configuration change.
7:18 AM: Server restarts begin
7:58 PM: Server configuration successful.


Root Cause

At 6:13 AM EAT, a configuration change was inadvertently released to the server without first being released to the testing environment. The servers began repeatedly hanging and restarting as they attempted to recover and at 6:28 AM EAT, the service outage began.

Resolution and recovery

At 6:44 AM, we attempted to rollback the problematic configuration change. This rollback failed. These problems were addressed and we successfully rolled back at 7:12 AM.

As a result, we decided to restart servers gradually (at 7:18 AM), to avoid possible cascading failures from a wide scale restart. 


Corrective and Preventative Measures

In the last two days, we’ve conducted an internal review and analysis of the outage. The following are actions we are taking to address the underlying causes of the issue and to help prevent recurrence and improve response times:
Improve process for auditing all high-risk configuration options.
Develop better mechanisms for quickly delivering status notifications during incidents.


We appreciate your patience and again apologize for the impact to you, your users, and your organization. We thank you for your business and continued support.


