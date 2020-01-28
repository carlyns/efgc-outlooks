## Carlyn's Weekly Outlook for 20200203
### Routine Tasks
* Gift Entry
* Monthly reports for finance: Classy & Roundup gifts >> move to first week of Feb
* Letter Generation and Record Updates
* Continue basic SF documentation
* Weekly Data Cleanup
* Verify checks for finance
* Standard Salesforce Administration - adjusting settings, prioritizing requests, monitoring data entry, answering questions about record history, troubleshooting errors, assisting with reports, educating staff on interface
* something else?
* Monthly reconciliation with finance, Sep & Oct?  >> move to second week of Sep

### Major SF Issues to assess/tackle: [potential blocks***]
1. Continue Client Services improvements through UI.  Continue research, design & preparation for structural improvements.  Establish prevention (temp if needed), consolidate sources if data is missing, perform cleanup for each.
2. Troubleshoot, redesign, and rebuild existing hard-coded components and disconnections discovered while executing improvements.
3. With new features capturing new reporting requirements, refine report generation using new features.
4. 
5. Investigate the strange behavior caused when merging Contact records: leftover anonymous empty accounts, leftover addresses.
6. Investigate strange import behavior: a) When Donations’ primary contact is not Account’s primary contact, matching doesn’t happen.  b) When multiple donations are from the same donor, “Insert” throws an error, sometimes “Update” too.  c) Name matching includes middle name but not alternate names.  (>> Understand consequences and limitations of matching by email. )
7. > > Reminder.  Examples of usability/inflexibility built by TEK that have been revealed over time, and if not addressed, had the potential to completely block operations in the future … they had professional duty to take care of this
8. 
9. Design from scratch (I suppose part of job description) custom Profiles for searching, object access, field permissions, etc to bolster better UI.  But I consider this a block because it wasn’t done at all, affects Data Quality bc CMs can’t view context/dups along with no training and no data context. >> to another week
10. Investigate the strange behavior caused when merging Contact records: leftover anonymous empty accounts, leftover addresses.
11. Another stab at the crazy Duplicate rules …

### Assistance
* Support from leadership to verify the main pieces of information required for state reporting.  Once verified, these can influence / set the stage for Operations.  Then database and related reports can be setup accordingly.

- - - -
#### Last Week’s Summary:
1. Prepped and imported online gifts.  Refined import steps to use ClassyID fields for matching contacts.  >> to another week
2. Coordinated gifts with designations to Walk, Marathon, and Third Party events from various sources (Facebook fundraisers, workplaces, mailed-in).
3. Processed gifts in Amply portal awaiting action.  When possible, created a portal account, gathered gift/employer IDs, verified gift was received, updated gift status in portal and Amply.  Compared Amply report with dashboard.
4. Created list for Development: Clients aged 17 and under who did not have open cases for new program potential outreach.  
5. Contacted FormTitan for help with revising email notification settings.  
6. Added custom field “Case Status Notes” for case management team’s internal use.  

7. Imerman discussion >> to another week
8. LA Vacation
9. Studying?
10. Received/processed feedback for first version of Client Services Salesforce manual to leadership for feedback/markup.   Added suggestions to GoogleDoc.  >> to another week
11. Sent some Classy donors their annual giving report summary.  (first 1/28, then postponed to 2/4)

8. 
9. Streamlined main classification fields for gifts.  (Campaign, Appeal, Addl Notes)  Cleaned and moved existing data to new setup.   >> to another week
10. Followed up with Classy support about report templates that returned empty data.  Classy’s response was ?  >> to another week
11. Continued discussing and testing options to handle matching gifts process, workplace giving gifts, and late-designated workplace/matching gifts with late designation requests. >> to another week

12. Any Classy tickets?  >> to another week
13. Follow up w Classy support about discrepancy.w “incomplete” status and they would investigate on their end.   >> to another week
14. **5. Streamlined picklist behavior for “XX” Donation field**
15. Autofy sync status?
16. another way View Donor History in Salesforce for Finance??
17. 

*/// Additional SF/Ops issues addressed: ///*
12. Revised Process to trigger for current quarter and created condition to include the Date of the Intake/Review.  
13. Called SF Support about validation rule on comparing the total units from the Activity’s duration with the total quantity of units inputted.  They couldn’t understand how to write the formula, so they suggested a custom field, which was the original alternative.  
14. Removed old test option from E-Forms dropdown list via the Developer console.  
15. Built new Process to trigger “open” Case Status anytime Consent was re/established.  
16. Monitored lite versions of internal team reports: satisfaction questions, expiring consent, direct referrals, etc.
17. Monitored for issues after rollout of Forms, iPads, Activity Unit Names, Interactions object.  Answered basic questions/clarifications from case management team as they arose.
18. Monitored for issues after rollout of Service File structure and Activity Label.  Answered basic questions/clarifications from case management team as they arose.
19. Refined paper version forms w Valentina. >> to another week.
20. Addressed push/get integration errors between Forms and Case Record as they arose.   >> to another week.  ??any new??
21. Continued to give refreshers to CMs on the initial intake steps. >> to another week.
22. Any decision/plan made to redesign initial intake steps to be less dependent on the Process Builder and Flow Builder variables?  not sure if i could come up with a better solution, esp if some CMs aren’t doing initial intake steps at all.  >> to another week.
23. 
24. Had staff test revised Business Development structure in sandbox.  >> to another week
25. Need to contact SF about displaying child accounts, affiliated contacts, and record type prompt.   >> to another week.
26. Need to contact SF about validation rule for units = duration on Activities
27. 
28. Startup Phase 2 of Status-Service structural redesign: Participation list.  >> to another week
29. 
30. Continued basic UI improvements on Client Services objects: XXX Object.  Reviewing default and required fields, scoping the cleanup necessary, preparing cleanup sheets, hiding/reordering sections and fields, clarifying tasks with case managers and other staff.  >> to another week
31. Rolled out first version of Intake Summary Sheet. >> to another week
32. Researched FormTitan options for in-between status for Intake Summary Sheet involving staffing signatures.  Might need a version 2.
33. 
34. for consistency when creating mailing lists.  revised values to show Do Not Contact / Solicit distinction.  Attempted to build process builder to replicate solicitation values from Contact to Accounts (but realized same issue with batch edit)  Need to research if this is a native SF function, possibly rebuild function.  >> to another week
35. iPad login redirect issue.  Reopen this case with SF Support to see if i can find a competent developer.  To see if there is actual javascript code that can work around the login redirect screen  >> to another week.
36. Reviewed concepts with case management team after observing incoming data patterns.  >> to another week
37. Observed a client intake conducted by case manager. >> to another week

- - - -
### Quarterly Goals
*By midQ3 (feb15):* 3rd round of Client Services solutions complete & 4th round prioritized, Brainstorm registration / letter queue / importing improvements, Report criteria cleanup, Report type research, Certification.
*By endQ3 (mar31):* 4th round of Client Services solutions complete, Brainstorm Donation-Finance flow improvements, Research Classy-Mailchimp sync and Donor-driven info updating, Explore dashboards.
*By endQ3 (may15):* Gifts Documentation complete, Reporting Documentation complete, Admin Documentation complete, Increased support for Finance/Ops.