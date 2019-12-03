## Carlyn's Weekly Outlook for 20191209
### Routine Tasks
* Gift Entry
* Monthly reports for finance: Classy & Roundup gifts >> move to first week of Dec
* Letter Generation and Record Updates
* Continue basic SF documentation
* Weekly Data Cleanup
* Verify checks for finance
* Standard Salesforce Administration - adjusting settings, prioritizing requests, monitoring data entry, answering questions about record history, troubleshooting errors, assisting with reports, educating staff on interface
* something else?
* Monthly reconciliation with finance  >> move to second week of Sep

### Major SF Issues to assess/tackle: [potential blocks***]
1. Continue Client Services improvements through UI.  Continue research, design & preparation for structural improvements.  Establish prevention (temp if needed), consolidate sources if data is missing, perform cleanup for each.
2. Troubleshoot, redesign, and rebuild existing hard-coded components and disconnections discovered while executing improvements.
3. Design how new reporting requirements can be captured in database based on Operations adjustments.  Build, test, and roll-out these new features.  Test report generation using new features.
4. Incorporate new structural design changes into quarterly and year-end state reports and coordinate with Client Services operations.
5. 
6. Investigate the strange behavior caused when merging Contact records: leftover anonymous empty accounts, leftover addresses.
7. Investigate strange import behavior: a) When Donations’ primary contact is not Account’s primary contact, matching doesn’t happen.  b) When multiple donations are from the same donor, “Insert” throws an error, sometimes “Update” too.  c) Name matching includes middle name but not alternate names.  (>> Understand consequences and limitations of matching by email. )
8. > > Reminder.  Examples of usability/inflexibility built by TEK that have been revealed over time, and if not addressed, had the potential to completely block operations in the future … they had professional duty to take care of this
9. 
10. Design from scratch (I suppose part of job description) custom Profiles for searching, object access, field permissions, etc to bolster better UI.  But I consider this a block because it wasn’t done at all, affects Data Quality bc CMs can’t view context/dups along with no training and no data context. >> to another week
11. Investigate the strange behavior caused when merging Contact records: leftover anonymous empty accounts, leftover addresses.
12. Another stab at the crazy Duplicate rules …

### Assistance
* Support from leadership to verify the main pieces of information required for state reporting.  Once verified, these can influence / set the stage for Operations.  Then database and related reports can be setup accordingly.

- - - -
#### Last Week’s Summary:
1. Prepped and imported online gifts.  Refined import steps to use ClassyID fields for matching contacts.  >> to another week
2. Parsed through a Classy report discrepancy this month $8.31 between what hit account and what totaled on report.  Likely a fee refund delay, but submitted Classy ticket to inquire.  
3. 
4. Created EOY Appeal mailing list in a day.  
5. 
6. Coordinated gifts with designations to Walk, Marathon, and Third Party events from various sources (Facebook fundraisers, workplaces, mailed-in). >> to another week
7. 
8. Streamlined main classification fields for gifts.  (Campaign, Appeal, Addl Notes)  Cleaned and moved existing data to new setup.   >> to another week
9. Processed gifts in Amply portal awaiting action.  When possible, created a portal account, gathered gift/employer IDs, verified gift was received, updated gift status in portal and Amply.  Compared Amply report with dashboard.
10. Followed up with Classy support about report templates that returned empty data.  Classy’s response was ?  >> to another week
11. Continued discussing and testing options to handle matching gifts process, workplace giving gifts, and late-designated workplace/matching gifts with late designation requests. >> to another week

12. Any Classy tickets?  >> to another week
13. Follow up w Classy support about discrepancy.w “incomplete” status and they would investigate on their end.   >> to another week
14. **5. Streamlined picklist behavior for “XX” Donation field**
15. Autofy sync status?
16. another way View Donor History in Salesforce for Finance??
17. 

*/// Additional SF/Ops issues addressed: ///*
22. More discussion on blaming leaders for not doing their to-dos.  And request that I write up the cheat sheet for them.  >> did it ever get brought up again
23. Monitored lite versions of internal team reports: satisfaction questions, expiring consent, direct referrals, etc.
24. Monitored for issues after rollout of Forms, iPads, Activity Unit Names, Interactions object.  Answered basic questions/clarifications from case management team as they arose.
25. Monitored for issues after rollout of new Service File structure and Activity Label.  Answered basic questions/clarifications from case management team as they arose.
26. Continued to build out redesigned Status-Service structure.  Continued steps to ensure all Service Files, Activities, and Case Records were transitioned over to the newly consolidated service file structure.  Included checking Case Records without any Activity (still need to do), finding Activities unconnected to any Client/Case Record/ServFile, preparing data files, and importing new values.  
27. Continued to build out redesigned Status-Service structure.  Create Clinic section on Case Record and train/test.  Build Participation List feature from scratch.   >> to another week.
28. EPIPHANY Concluded that time-based participation is critical distinction.   [took critical thinking and observing patterns/characteristics in engagement types, not exercises - WHO would’ve been able to discover that??]


26. Refined paper version forms w Valentina. >> to another week.
27. Addressed push/get integration errors between Forms and Case Record as they arose.   >> to another week.  ??any new??  MORE CHARACTER SPACE
28. Troubleshooted a Forms integration error.
29. Contacted SF Support about Flows interface - need to delete old referenced to fields before i can change field type to allow for longer character length. >> to another week.  
30. Gave more character space for a few text fields per VA; coordinated 5+ related connections. >> to another week
31. 
32. Continued basic UI improvements on Client Services objects: XXX Object.  Reviewing default and required fields, scoping the cleanup necessary, preparing cleanup sheets, hiding/reordering sections and fields, clarifying tasks with case managers and other staff.  >> to another week
33. Added SSI/SSDI eligibility value to three connected locations.  >> to another week
34. Made adjustments to form layout and fields in FormTitan, including connections to/from Salesforce objects, and connections to printable version of forms.  (which fields now?) >> to another week
35. Rolled out first version of Intake Summary Sheet. >> to another week
36. Researched FormTitan options for in-between status for Intake Summary Sheet involving staffing signatures.  Might need a version 2.
37. Revised language in Client Handbook to reflect new Forms/processes. >> to another week
38. 
39. for consistency when creating mailing lists.  revised values to show Do Not Contact / Solicit distinction.  Attempted to build process builder to replicate solicitation values from Contact to Accounts (but realized same issue with batch edit)  Need to research if this is a native SF function, possibly rebuild function.  >> to another week
40. 
41. Streamlined the rest of the 1009 reports (incl/excl support groups).  >> to another week

27. iPad login redirect issue.  Reopen this case with SF Support to see if i can find a competent developer.  To see if there is actual javascript code that can work around the login redirect screen  >> to another week.  
28. Reviewed concepts with case management team after observing incoming data patterns.  >> to another week
29. Observed a client intake conducted by case manager. >> to another week

22. Any new surprises?  There is a definite need for training on Object Structure - but when and who?  and how to cleanup existing?  >> to another week
23. Possibly research parent-child Account structure and Record Types for Biz Dev >> to another week

- - - -
### Quarterly Goals
*By endQ2 (dec31):* State reporting generated from new Status-Service structure, 2nd round of Client Services issues complete & 3rd round prioritized, Donor-driven info updating, Written documentation done, Historical Client Services data plan created, Reassess object structure incl Bus. Development, Profile settings plan underway, Certification exam.
*By midQ3 (feb15):* 3rd round of Client Services solutions complete & 4th round prioritized, Historical Client Services data plan underway, Brainstorm registration improvements, Reporting & dashboards.
*By endQ3 (mar31):* 4th round of Client Services solutions complete.