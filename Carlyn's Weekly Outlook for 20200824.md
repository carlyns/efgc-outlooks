## Carlyn's Weekly Outlook for 20200824
### Routine Tasks
* Gift Entry
* Letter Generation and Record Updates
* Continue basic SF documentation
* Data Cleanup - case records, service files, activities, contact info
* Standard Salesforce Administration - adjusting settings, prioritizing requests, monitoring data entry, answering questions about record history, troubleshooting errors, assisting with reports, educating staff on interface

### Major SF Issues to assess/tackle: [potential blocks***]
1. Redundancies for reporting still connected to structural flaws i.e. disconnect between Activities and Public Events.  Redesign and rebuild needs to be planned at time of least disruption.
2. Many deprecated fields from cleanup/redesign that need to be confirmed and removed.  Otherwise editing/creating reports is nearly impossible for ordinary users.
3. More complex changes e.g. Forms revisions and connections, any flows/processes, any automations/validations) need steps/documentation.
4. Existing hard-coded components and disconnections discovered while executing improvements. Troubleshoot, redesign, and rebuild these as they are revealed.

### Assistance
* Support from leadership to verify the main pieces of information required for state reporting.  Once verified, these can influence / set the stage for Operations.  Then database and related reports can be setup accordingly.

- - - -
#### Last Week’s Summary:
1. Reconciled Golf gifts with payments, keeping track of outstanding payments before preparing and importing gift data.  
2. Revised entries for in-kind golf gifts for letters.  Generated letters and emailed.  
3. Worked on golf gift data to calculate true gift totals for each unique donor (different from payment data) in order to generate custom thank you letters for multiple gifts and update acknowledgement values.  
4. Coordinated gifts with designations to Walk, Marathon, and Third Party events from various sources (Facebook fundraisers, workplaces, mailed-in).
5. Processed gifts in Amply portal awaiting action.  When possible, created a portal account, gathered gift/employer IDs, verified gift was received, updated gift status in portal and Amply.  Gave status and process update to Development Manager.  Compared Amply report with dashboard.

*/// Additional SF/Ops issues addressed: ///*
6. Monitored for issues related to Forms changes, iPads, Activity Unit Names, Interactions object, Service File structure, Activity Label, Activity Case Notes Public Events.  Answered basic questions/clarifications from staff as they arose.
7. Discussed locations of intake data and potential custom report rather than custom form involving mapping, layout, and field analysis/coordination.  
8. Continued testing draft design on Attendance-Activity disconnect in sandbox.  Confirmed no existing process/flow ever built to create this connection.  Analyzed existing processes and flows for possible limitations.   Discovered Service Units are non-functional and should not be included in design.  Analyzed use cases and designed ProcessBuilder with criteria that checks for relevant Attendance criteria before creating an Activity.  Synced values in Service Group Case Service field with Activity Label field.  Setup all mapping across Attendance record to Activity record.  Still need to figure out “if changed” condition.  

- - - -
### Quarterly Goals
*By endQ1 (sep30):* Gifts Documentation complete, Admin Documentation complete, Make enough progress on Major SF Issues to remove from high risk list, another round of Client Services solutions prioritized.
*By midQ2 (nov15):* Increased support for Finance/Ops, Research Classy-Mailchimp sync and Donor-driven info updating, Explore dashboards
*By endQ2 (dec31):* Supplemental video documentation, pure administration.