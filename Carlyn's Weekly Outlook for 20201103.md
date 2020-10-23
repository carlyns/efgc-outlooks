## Carlyn's Weekly Outlook for 20201103
### Routine Tasks
* Gift Entry
* Classy payout reports showing any splits. >> move to first week of month
* ROCS report creation with client info overlay for Event Attendance  >> move to first week of month
* Letter Generation and Record Updates
* Continue basic SF documentation
* Data Cleanup - case records, service files, activities, contact info
* Standard Salesforce Administration - adjusting settings, prioritizing requests, monitoring data for system issues, answering questions about record history or reports, troubleshooting errors, educating staff on interface
* Monthly reconciliation with finance >> move to first week of month

### Major SF Issues to assess/tackle: [potential blocks***]
1. Many deprecated fields from cleanup/redesign that need to be confirmed and removed.  Otherwise editing/creating reports is nearly impossible for ordinary users.
2. More complex changes e.g. Forms revisions and connections, any flows/processes, any automations/validations) need steps/documentation.
3. Existing hard-coded components and disconnections discovered while executing improvements. Troubleshoot, redesign, and rebuild these as they are revealed.
4. Investigating the strange behavior caused when merging Contact records: leftover anonymous empty accounts
5. 
6. Investigating strange import behavior: When Donations’ primary contact is not Account’s primary contact, matching doesn’t happen.
7. > > Reminder.  Examples of usability/inflexibility built by TEK that have been revealed over time, and if not addressed, had the potential to completely block operations in the future … they had professional duty to take care of this
8. Design from scratch (I suppose part of job description) custom Profiles for searching, object access, field permissions, etc to bolster better UI.  But I consider this a block because it wasn’t done at all, affects Data Quality bc CMs can’t view context/dups along with no training and no data context. >> to another week

### Assistance
* Support from leadership to verify the main pieces of information required for state reporting.  Once verified, these can influence / set the stage for Operations.  Then database and related reports can be setup accordingly.

- - - -
#### Last Week’s Summary:
1. Prepped and imported online gifts using 3-step templates.  >> to another week
2. Coordinated gifts with designations to Walk, Marathon, and Third Party events from various sources (Facebook fundraisers, workplaces, mailed-in).
3. Processed gifts in Amply portal awaiting action.  When possible, created a portal account, gathered gift/employer IDs, verified gift was received, updated gift status in portal and Amply.  Gave status and process update to Development Manager.  Compared Amply report with dashboard.
4. address cache org message by testing in sandbox per 5/29 email?
5. [week of 10/26] Confirmed no significant discrepancy between Classy payouts and Classy dashboard using spreadsheet analysis.  FOR DEVELOPMENT MANAGER >> any follow up?
6. Continued to filter through and remove obsolete reports and report types. >> to another week

6. Assisted CS staff with custom reports to view/manage caseload.  for debbie?

8. Received/processed feedback for first version of Gifts Salesforce manual to leadership for feedback/markup.   Added suggestions to GoogleDoc.  >> to another week
9. 

23. Followed up with Classy support about report templates that returned empty data.  Classy’s response was ?  >> to another week
24. Continued discussing and testing options to handle matching gifts process, workplace giving gifts, and late-designated workplace/matching gifts with late designation requests. >> to another week

13. Follow up w Classy support about discrepancy w “incomplete” status and they would investigate on their end.   >> to another week
14. Autofy sync status?
15. another way View Donor History in Salesforce for Finance??
16. 

*/// Additional SF/Ops issues addressed: ///*
1. Monitored for issues related to Forms changes, iPads, Interactions, Service File structure, Activities, Public Events.  Answered basic questions/clarifications from staff as they arose.
2. Gradual cleanup of case records with multiple service files incorrectly connected to other contacts from old system.  >> to another week
3. Continued to design UI for DHS codes for Types of Seizures.  Designing UI for streamlined values and accurate responses, given ~40 values and multiple selection is possible. >> to another week
4. Removed Correspondence object, reduced Tribute object usage for tracking sympathy cards only.  >> to another week
5. Continued to delete obsolete fields from Account/Contact object, locating hard connections where necessary. >> to another week
6. Continued to manually identify potential duplicates using exported spreadsheet, making use of duplicate record sets.  >> to another week
7. Monitored errors when moving members between households.  And anonymous account creation  >> to another week
8. Contacted SF Support about new error when moving members between households.  No contacts are populating in searchbox.  
9. Continued Client Forms changes.  Analyzed existing data for Background form and prepped for consolidation.  Adjusted/created relevant Case Record fields to accommodate new changes, established relevant access.  [Waited for an overnight refresh of configuration on FormTitan to establish mapping.]  Revised Goals and Background forms in FormTitan.  Designed and drafted new Goals and Background pdf templates using dynamic feature.  Analyzed and adjusted Goals and Background field mapping from FormTitan to CaseRecord, CaseRecord to FormTitan, and from FormTitan to the static pdf.  Added live testing form to E-Forms button.  Setup a Signed/Unsigned stamp for the static Goals and Background pdfs.  
10. Rolled out new Counseling Form to Clinical Dept staff?  
11. Setup a Signed/Unsigned stamp for the existing Consent, Info Release, and Contact pdfs.  Rolled these smaller changes out to Client Services staff?  
12. Analyzed intake Flows and case record Processes to identify deprecated fields.  
13. Continued to research options for requesting client signatures virtually through FormTitan.  Live form too risky and pdf templates too complex to handle unique case records.  

27. Recreated ROCS report that was driven by the past Attendance-Activity disconnection.  but maybe not safe until duplicate record issue is confirmed fixed … >> to another week
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
*By midQ2 (nov15):* Admin Documentation complete, Make enough progress on Major SF Issues to remove from high risk list, another round of Client Services solutions complete, another round of Client Services solutions prioritized.
*By endQ2 (dec31):* Increased support for Finance/Ops, Research Classy-Mailchimp sync and Donor-driven info updating, Explore dashboards, Supplemental video documentation, current round of Client Services solutions complete.
*By midQ3 (feb15):* Pure administration, another round of Client Services solutions prioritized.