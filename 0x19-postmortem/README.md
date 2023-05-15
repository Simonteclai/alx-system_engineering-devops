# Issue Summary

Duration: The user account data outage occurred on the 10th of May 2023, at approximately 9:45 PM EST and lasted for 3 hours until it was resolved at 12:45 AM EST on the 11th.

Impact: The outage impacted our member's access their accounts,access the history list of the members previous purchase, complete orders, and use our digital banking servieces. From the estimated 60,000 daily users, about 40% were affected by the outage, and they were unable to perform any transactions during the three-hour period.

Root Cause: The root cause of the outage was an introduction to the changed application that was introduced during a software update the previous evening, which had issues in accessing the userdata  and other  critical service done by our users and stored the data history  when it was restarted.

## Timeline

- 9:45 PM EST: The issue was detected when our monitoring systems alerted our technical teams of a service failure.
- 9:50 PM EST: Our technical teams began investigating the issue and determined that the service failure was due to a configuration change that was introduced during a software update.
- 10:00 PM EST: The team attempted to roll back the configuration change.
- 10:45 AM EST: The team began investigating other potential root causes and conducted a series of tests to identify the issue.
- 11:15 AM EST: The team escalated the issue to the development team to assist in identifying and resolving the root cause.
- 12:15 PM EST: The issue was identified and resolved resulting in the normal operations desired.

## Root Cause and Resolution

The root cause of the user data outage was a configuration change that was introduced during a software update, which the new update was momentarily unable to access the users data from our servers and caused a critical error in user accoutn access, purchase history,our digital banking system and  failed when it was installed after restart. The team identified the issue by conducting a series of tests and working with the development team to analyze the code.

To resolve the issue, the team rolled back the software update and restored the service to its previous configuration. From there, the identified the issue and added the missing features that allowed the new update to connect and access the user data. Lastly,  conducted a series of tests to ensure that the service was functional also that the issue had been fully resolved.

## Corrective and Preventative Measures

To prevent similar incidents from occurring in the future, we have implemented the following corrective and preventative measures:

- We have improved our change management process to prevent configuration changes from causing outages in the future. Changes will now be more rigorously tested and validated before they are introduced into our production environment.
- We have increased our customer service sector to receive  early warning of potential issues and allow for quicker response times with added suggestions to improve our services.
- We will have a small test demo test users to identifiy additional unnoticed errors.
- We have enhanced our communication channels toalert and notify our users of new feauters and updates to fix previuosly detected errors.
- We will be having continouse training for our technical teams to improve their ability to identify and respond to incidents much faster and more effectively.

## Tasks to Address the Issue

To address the issue, we have identified the following specific tasks:

- Perform a full review of our software deployment processes to identify potential areas for improvement.
- Develop and implement a testing framework to ensure that all configuration changes are thoroughly tested before they are introduced into our production environment.
- Implement additional monitoring and alerting capabilities to provide early warning of potential issues and allow for quicker response times.
- Have a small Demo test group of users to identif additional unnoticed issues.
- Conduct regular training for our technical teams to ensure that they are up-to-date with the latest incident response procedures and best practices.

In conclusion, the online shopping system user data access outage that occurred on May 10th, 2023, was an event that marked the issiues that could occurr when introducing a new update to  customers and our operations. However, we were able to quickly identify the root cause of the issue, restore normal operations, and take steps to prevent similar incidents from occurring in the future. For the satisfaction of our users and our company success, we remain committed to growing our teams skillsso to provid our customers reliable shopping outlet and with a secure banking services . We aim to continue growing in all aspects of our business for the comfort and trust of our customers.



![The life of a SE engineer ->] (https://images.app.goo.gl/XDrNeMkxK9DraTok8)
