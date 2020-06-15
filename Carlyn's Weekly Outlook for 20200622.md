## Carlyn's Weekly Outlook for 20200622
### Routine Tasks
* Gift Entry
* Monthly reports for finance: Classy & Roundup gifts >> move to first week of July
* Letter Generation and Record Updates
* Continue basic SF documentation
* Weekly Data Cleanup - case records, service files, activities, contact info
* Verify checks for finance >> move til Quar is over
* Standard Salesforce Administration - adjusting settings, prioritizing requests, monitoring data entry, answering questions about record history, troubleshooting errors, assisting with reports, educating staff on interface
* Something else?
* Monthly reconciliation with finance >> move to another week

### Major SF Issues to assess/tackle: [potential blocks***]
1. Redundancies for reporting still connected to structural flaws i.e. disconnect between Activities and Public Events.  Redesign and rebuild needs to be planned at time of least disruption.
2. Many deprecated fields from cleanup/redesign that need to be confirmed and removed.  Otherwise editing/creating reports is nearly impossible for ordinary users.
3. More complex changes e.g. Forms revisions and connections, any flows/processes, any automations/validations) need steps/documentation.
4. Existing hard-coded components and disconnections discovered while executing improvements. Troubleshoot, redesign, and rebuild these as they are revealed.

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
3. Processed gifts in Amply portal awaiting action.  When possible, created a portal account, gathered gift/employer IDs, verified gift was received, updated gift status in portal and Amply.  Compared Amply report with dashboard.
4. address cache org message by testing in sandbox per 5/29 email?
5. Spanish Conference mailing list?  
6. 
7. Streamlined classification fields for Marathon donations to allow for filter of registrations.  Cleaned and moved existing data to new setup.
8. 
9. Considered adding more Salesforce licenses.  any more comments on this??  >> to another week
10. Being the authority on explaining the DHS/DFI Quarterly reports to Stacy as ordered by BJ that “we’re” walking her through it.  >> to another week

7. Imerman discussion >> to another week
8. Received/processed feedback for first version of Client Services Salesforce manual to leadership for feedback/markup.   Added suggestions to GoogleDoc.  >> to another week

23. Followed up with Classy support about report templates that returned empty data.  Classy’s response was ?  >> to another week
24. Continued discussing and testing options to handle matching gifts process, workplace giving gifts, and late-designated workplace/matching gifts with late designation requests. >> to another week

12. Any Classy tickets?  >> to another week
13. Follow up w Classy support about discrepancy.w “incomplete” status and they would investigate on their end.   >> to another week
14. Autofy sync status?
15. another way View Donor History in Salesforce for Finance??
16. 

*/// Additional SF/Ops issues addressed: ///*
18. Monitored lite versions of internal team reports: satisfaction questions, expiring consent, direct referrals, etc.
19. Monitored for issues related to Forms changes, iPads, Activity Unit Names, Interactions object, Service File structure and Activity Label.  Answered basic questions/clarifications from staff as they arose.
20. Communicated with SF Support regarding where/how to control mapping of new fields on Cal Activity that get duplicated when assigned to multiple staff members.  After following instructions, they suggested doing a change set from sandbox but couldn’t give direct assistance.  Failed tests led to a failed deployment so they may offer an alternative way to deploy apex class change.
21. Prioritized project: Wrapped up steps to archive Case Notes and solely use Activities.  Made the new structure visible on all relevant screens and hid the Case Notes on all relevant screens.  Checked for any last direct referrals.  Reset the DHS reports and leadership reports that are affected to ensure they are still pulling the same info.  Worked with Stacy on rollout and outlined points for 6/19 presentation.  Monitored use/issues after rollout.

23. Continued to design UI for DHS codes for Types of Seizures.  Designing UI for streamlined values and accurate responses, given ~40 values and multiple selection is possible. >> to another week
24. Continued to test draft objects and connections to better handle Correspondence records, Tributes and Notifications from donations.  >> to another week, but doesn’t seem to be worth doing.
25. Continued to filter through and remove obsolete reports. >> to another week

27. Addressed push/get integration errors between Forms and Case Record as they arose.   >> to another week.  ??any new??
28. Continued to give refreshers to CMs on the initial intake steps. >> to another week.
29. Any decision/plan made to redesign initial intake steps to be less dependent on the Process Builder and Flow Builder variables?  not sure if i could come up with a better solution, esp if some CMs aren’t doing initial intake steps at all.  >> to another week.
30. Continued to refine draft of Business Development structure in sandbox to get it ready for testing.  Had staff test revised Business Development structure in sandbox.  >> to another week

34. Startup Phase 2 of Status-Service structural redesign: Participation list.  >> to another week
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
*By endQ4 (jun30):* Gifts Documentation complete, Admin Documentation complete, 4th round of Client Services solutions complete, another round of Client Services solutions prioritized.
*By midQ1 (aug15):* Increased support for Finance/Ops, Research Classy-Mailchimp sync and Donor-driven info updating, Explore dashboards
*By endQ1 (sep30):* Supplemental video documentation, Advanced Admin Certification.