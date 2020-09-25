## Carlyn's Weekly Outlook for 20201005
### Routine Tasks
* Gift Entry
* Classy payout reports showing any splits.
* Reports for finance: Classy & Roundup gifts >> move to first week of month
* ROCS report creation with client info overlay for Event Attendance  >> move to first week of month
* Letter Generation and Record Updates
* Continue basic SF documentation
* Data Cleanup - case records, service files, activities, contact info
* Verify checks for finance >> move til Quar is over
* Standard Salesforce Administration - adjusting settings, prioritizing requests, monitoring data for system issues, answering questions about record history or reports, troubleshooting errors, educating staff on interface
* Something else?
* Monthly reconciliation with finance >> move to first week of month

### Major SF Issues to assess/tackle: [potential blocks***]
1. Many deprecated fields from cleanup/redesign that need to be confirmed and removed.  Otherwise editing/creating reports is nearly impossible for ordinary users.
2. More complex changes e.g. Forms revisions and connections, any flows/processes, any automations/validations) need steps/documentation.
3. Existing hard-coded components and disconnections discovered while executing improvements. Troubleshoot, redesign, and rebuild these as they are revealed.

6. Investigate the strange behavior caused when merging Contact records: leftover anonymous empty accounts, leftover addresses.
7. Investigate strange import behavior: a) When Donations’ primary contact is not Account’s primary contact, matching doesn’t happen.  b) When multiple donations are from the same donor, “Insert” throws an error, sometimes “Update” too.  c) Name matching includes middle name but not alternate names.   (>> Be able to explain the consequences and limitations of matching by email. )
8. > > Reminder.  Examples of usability/inflexibility built by TEK that have been revealed over time, and if not addressed, had the potential to completely block operations in the future … they had professional duty to take care of this
9. 
10. Design from scratch (I suppose part of job description) custom Profiles for searching, object access, field permissions, etc to bolster better UI.  But I consider this a block because it wasn’t done at all, affects Data Quality bc CMs can’t view context/dups along with no training and no data context. >> to another week
11. Another stab at the crazy Duplicate rules …

### Assistance
* Support from leadership to verify the main pieces of information required for state reporting.  Once verified, these can influence / set the stage for Operations.  Then database and related reports can be setup accordingly.

- - - -
#### Last Week’s Summary:
1. Prepped and imported online gifts using 3-step templates.  >> to another week
2. Coordinated gifts with designations to Walk, Marathon, and Third Party events from various sources (Facebook fundraisers, workplaces, mailed-in).
3. Processed gifts in Amply portal awaiting action.  When possible, created a portal account, gathered gift/employer IDs, verified gift was received, updated gift status in portal and Amply.  Gave status and process update to Development Manager.  Compared Amply report with dashboard.
4. address cache org message by testing in sandbox per 5/29 email?
5. Reviewed Classy payouts between Finance and Development for Aug $6K discrepency >> any follow up?
6. Quarterly DHS and DFI reporting.  all of it.  what did i write last time?  


6. Assisted CS staff with custom reports to view/manage caseload.  for debbie?

8. Received/processed feedback for first version of Gifts Salesforce manual to leadership for feedback/markup.   Added suggestions to GoogleDoc.  >> to another week

23. Followed up with Classy support about report templates that returned empty data.  Classy’s response was ?  >> to another week
24. Continued discussing and testing options to handle matching gifts process, workplace giving gifts, and late-designated workplace/matching gifts with late designation requests. >> to another week

13. Follow up w Classy support about discrepancy w “incomplete” status and they would investigate on their end.   >> to another week
14. Autofy sync status?
15. another way View Donor History in Salesforce for Finance??
16. 

*/// Additional SF/Ops issues addressed: ///*
19. Monitored for issues related to Forms changes, iPads, Activity Unit Names, Interactions object, Service File structure, Activity Label, Activity Case Notes Public Events.  Answered basic questions/clarifications from staff as they arose.
20. Gradual cleanup of case records with multiple service files incorrectly connected to other contacts from old system.  >> to another week
21. Continued to design UI for DHS codes for Types of Seizures.  Designing UI for streamlined values and accurate responses, given ~40 values and multiple selection is possible. >> to another week
22. Continued to test draft objects and connections to better handle Correspondence records, Tributes and Notifications from donations.  >> to another week, but doesn’t seem to be worth doing… maybe only to track sympathy cards that go out.
23. Continued to filter through and remove obsolete reports. >> to another week
24. Continued to delete obsolete fields from Contact object, locating hard connections where necessary. >> to another week
25. Added [FIELDS] to [BACKGROUND] Form and all respective layouts (FT, paper, SF).  Reformatted layouts with 2 deleted fields and other revisions.  Waited for an overnight refresh of configuration on FormTitan to establish mapping.
26. Recreated ROCS report that was driven by the past Attendance-Activity disconnection.  but maybe not safe until duplicate record issue is confirmed fixed … >> to another week
27. Started on Participation Lite in UAT ???
28. Discussions about Activities via Programs dept (Leia) and creating Case Records.  ????

31. Addressed push/get integration errors between Forms and Case Record as they arose.   >> to another week.  ??any new??
32. Continued to give refreshers to CMs on the initial intake steps. >> to another week.
33. Any decision/plan made to redesign initial intake steps to be less dependent on the Process Builder and Flow Builder variables?  not sure if i could come up with a better solution, esp if some CMs aren’t doing initial intake steps at all.  >> to another week.
34. Followed up with Business Development staff regarding structure in SF to create sample records for testing and feedback.  No feedback on Account entry; Donation not yet attempted.

35. Assisted some staff members with using filters?
36. Continued basic UI improvements on Client Services objects: XXX Object.  Reviewing default and required fields, scoping the cleanup necessary, preparing cleanup sheets, hiding/reordering sections and fields, clarifying tasks with case managers and other staff.  >> to another week
37. Rolled out first version of Intake Summary Sheet. >> to another week
38. Researched FormTitan options for in-between status for Intake Summary Sheet involving staffing signatures.  Might need a version 2.
39. 
40. iPad login redirect issue.  Reopen this case with SF Support to see if i can find a competent developer.  To see if there is actual javascript code that can work around the login redirect screen  >> to another week.
41. Reviewed concepts with case management team after observing incoming data patterns.  >> to another week
42. Observed a client intake conducted by case manager. >> to another week

- - - -
### Quarterly Goals
*By midQ2 (nov15):* Admin Documentation complete, Make enough progress on Major SF Issues to remove from high risk list, another round of Client Services solutions prioritized.
*By endQ2 (dec31):* Increased support for Finance/Ops, Research Classy-Mailchimp sync and Donor-driven info updating, Explore dashboards, Supplemental video documentation, current round of Client Services solutions complete.
*By midQ3 (feb15):* Pure administration, another round of Client Services solutions prioritized.
