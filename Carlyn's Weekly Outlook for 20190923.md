## Carlyn's Weekly Outlook for 20190923
### Routine Tasks
* Gift Entry
* Monthly reports for finance: Classy & Roundup gifts >> move to first week of Oct
* Letter Generation and Record Updates
* Continue basic SF documentation - videos
* Weekly Data Cleanup
* Verify checks for finance
* Standard Salesforce Administration - adjusting settings, prioritizing requests, monitoring data entry, answering questions about record history, troubleshooting errors, assisting with reports, educating staff on interface
* something else?
* Monthly reconciliation with finance  >> move to second week of Sep

### Three Big SF Issues to assess/tackle: [potential blocks***]
1. Continue Client Services improvements through UI.  Continue research & preparation for structural redesigns.  Establish prevention (temp if needed), consolidate sources if data is missing, perform cleanup for each.
2. Incorporate new structural design changes into quarterly and end of year state reports.
3. Investigate the strange behavior caused when merging Contact records: leftover anonymous empty accounts, leftover addresses.
4. 
5. Investigate strange import behavior: a) When Donations’ primary contact is not Account’s primary contact, matching doesn’t happen.  b) When multiple donations are from the same donor, “Insert” throws an error, sometimes “Update” too.  c) Name matching includes middle name but not alternate names.  (>> Understand consequences and limitations of matching by email. )
6. > > Reminder.  Examples of usability/inflexibility built by TEK that have been revealed over time, and if not addressed, had the potential to completely block operations in the future … they had professional duty to take care of this
7. 
8. Design from scratch (I suppose part of job description) custom Profiles for searching, object access, field permissions, etc to bolster better UI.  But I consider this a block because it wasn’t done at all, affects Data Quality bc CMs can’t view context/dups along with no training and no data context. >> to another week
9. Investigate the strange behavior caused when merging Contact records: leftover anonymous empty accounts, leftover addresses.
10. Another stab at the crazy Duplicate rules …

- - - -
#### Last Week’s Summary:
11. Prepped and imported online gifts; separate process for Walk registrations.  Refined import steps to use ClassyID fields for matching contacts.  >> to another week

12. Figure out what to do w SQL Penelope data.  >> to another week
13. Coordinated gifts with designations to Walk, Marathon, and Third Party events from various sources (Facebook fundraisers, workplaces, mailed-in). >> to another week
14. 
15. Streamlined main classification fields for gifts.  (Campaign, Appeal, Addl Notes)  Cleaned and moved existing data to new setup.   >> to another week
16. Processed gifts in Amply portal awaiting action.  When possible, created a portal account, gathered gift/employer IDs, verified gift was received, updated gift status in portal and Amply. 
17. Recorded Picnic Mailing to Clients’ Case Records >> to another week
18. Discovered Do Not Solicit does not auto-mark when contact is marked deceased.  Researched this native SF function, troubleshooted, and rebuilt function.  >> to another week
19. Followed up with Classy support about report templates that returned empty data.  Classy’s response was ?  >> to another week

7. Continued discussing and testing options to handle matching gifts process, workplace giving gifts, and late-designated workplace/matching gifts with late designation requests. >> to another week
8. Cleaned up empty workplace values.  Created Workplace FY19 first report for Fundraisers to analyze >> to another week

12. Any Classy tickets?  >> to another week
13. **5. Streamlined picklist behavior for “XX” Donation field**
14. Autofy sync status?
15. another way View Donor History in Salesforce for Finance??
16. 

*/// Additional SF/Ops issues addressed: ///*
19. Confirmed Notes can be pulled from Contact object and filtered by author for state reporting.  ??? 
20. Monitored for issues after rollout of new Forms.  Answered basic questions/clarifications from case management team as they arose.
21. Refined paper version forms w Valentina. >> to another week.
22. Monitored for issues after rollout of iPads.  ??any new?? >> to another week.  Continued to troubleshoot session timeouts with research on FormTitan redirects and possibly Preferred support.  
23. Addressed push/get integration errors between Forms and Case Record as they arose.   >> to another week.  ??any new??  
24. 
25. Monitored for issues after rollout of streamlined Activity Unit Names.
26. Continued basic UI improvements on Client Services objects: XXX Object.  Reviewing default and required fields, scoping the cleanup necessary, preparing cleanup sheets, hiding/reordering sections and fields, clarifying tasks with case managers and other staff.  >> to another week
27. Gave more character space for a few text fields per VA; coordinated 5+ related connections. >> to another week
28. Made adjustments to form layout and fields in FormTitan, including connections to/from Salesforce objects, and connections to printable version of forms.  (which fields now?) >> to another week
29. Rolled out first version of Intake Summary Sheet. >> to another week
30. Researched FormTitan options for in-between status for Intake Summary Sheet involving staffing signatures.  Might need a version 2.
31. Revised language in Client Handbook to reflect new Forms/processes. >> to another week
32. 
33. 
34. Streamlined the rest of the 1009 reports (incl/excl support groups).  >> to another week

32. Started to build out redesigned Status-Service structure.  Stop Services: clean open/pending/closed status.  Consent In/Active: use date to auto-fill.   Use existing Service Files to label all child activities.  Consolidate existing Service Files to two.  Create Clinic section on Case Record and train/test.  Build Participation List feature from scratch.   >> to another week.
33. EPIPHANY Concluded that time-based participation is critical distinction.   [took critical thinking and observing patterns/characteristics in engagement types, not exercises - WHO would’ve been able to discover that??]

36. Reviewed concepts with case management team after observing incoming data patterns.  >> to another week
37. Observed a client intake conducted by case manager. >> to another week

22. Any new surprises?  There is a definite need for training on Object Structure - but when and who?  and how to cleanup existing?  >> to another week
23. Possibly research parent-child Account structure and Record Types for Biz Dev >> to another week

- - - -
### Quarterly Goals
*By endQ1 (sep30):* 2nd round of Client Services issues complete & 3rd round prioritized, Written documentation one-third done, Historical Client Services data plan created, State reporting generated from new Status-Service structure.
*By midQ2 (nov15):* 3rd round of Client Services solutions done, Reassess object structure incl Bus. Development, Donor-driven info updating, Written documentation two-thirds done, Certification exam, Brainstorm registration improvements, Profile settings plan created.
*By endQ2 (dec31):*  Donor-driven info updating, Written documentation done, Historical Client Services data plan underway, Profile settings plan underway, Reporting & dashboards.