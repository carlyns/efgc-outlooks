## Carlyn's Weekly Outlook for 20191111
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

### Three Big SF Issues to assess/tackle: [potential blocks***]
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
2. Prepped and imported online gifts.  Refined import steps to use ClassyID fields for matching contacts.  >> to another week
3. 
4. Figure out what to do w SQL Penelope data.  >> to another week
5. Wrote sentence for idealist about SQL help. 
6. Coordinated gifts with designations to Walk, Marathon, and Third Party events from various sources (Facebook fundraisers, workplaces, mailed-in). >> to another week
7. 
8. Streamlined main classification fields for gifts.  (Campaign, Appeal, Addl Notes)  Cleaned and moved existing data to new setup.   >> to another week
9. Processed gifts in Amply portal awaiting action.  When possible, created a portal account, gathered gift/employer IDs, verified gift was received, updated gift status in portal and Amply.  Started comparing Amply report with dashboard.  
10. Followed up with Classy support about report templates that returned empty data.  Classy’s response was ?  >> to another week

7. Continued discussing and testing options to handle matching gifts process, workplace giving gifts, and late-designated workplace/matching gifts with late designation requests. >> to another week

12. Any Classy tickets?  >> to another week
13. YES: Contacted Classy support about discrepancy.  A transaction showed on WePay report but no evidence of ever being processed in Classy.  Support verified it had “incomplete” status and they would investigate on their end.  
14. **5. Streamlined picklist behavior for “XX” Donation field**
15. Autofy sync status?
16. another way View Donor History in Salesforce for Finance??
17. 

*/// Additional SF/Ops issues addressed: ///*
22. Built new features to accommodate new reporting fields: satisfaction question on Goals-Plan form and Calendar Activitiy. 
23. Reviewed Direct Referrals, Interactions and Special Notes with Debbie.  
24. 
25. Continued to guide SF support through three conditions necessary to build formula.  
26. Created more lite versions of internal team reports:  satisfaction questions, etc.  
27. Monitored new Interactions object.
28. Monitored for issues after rollout of new Forms.  Answered basic questions/clarifications from case management team as they arose.
29. Refined paper version forms w Valentina. >> to another week.
30. Monitored for issues after rollout of iPads.  (Concluded login redirect issue last week)
31. > > put in keynote >> They used old code that on which I’ve already commented on its behavior in the sandbox.  They gave me links to deploy to production.  Very risky.  Probably won’t do it. It’s a software : software issue - not admin settings.  Probably will let it close and open with another agent.  Got hung up on changing the url in desktop, not mobile and accepted that “it works.”  >> to another week.  Reopened this case with SF Support to see if i can find a competent developer who doesn’t give me the same code as before and assumes it works in production after telling them to change the url in sandbox.  To see if there is actual javascript code that can work around the login redirect screen (and maybe “click” done for the user)
32. Addressed push/get integration errors between Forms and Case Record as they arose.   >> to another week.  ??any new??
33. 
34. Monitored for issues after rollout of streamlined Activity Unit Names.
35. Continued basic UI improvements on Client Services objects: XXX Object.  Reviewing default and required fields, scoping the cleanup necessary, preparing cleanup sheets, hiding/reordering sections and fields, clarifying tasks with case managers and other staff.  >> to another week
36. Gave more character space for a few text fields per VA; coordinated 5+ related connections. >> to another week
37. Added SSI/SSDI eligibility value to three connected locations.  >> to another week
38. Made adjustments to form layout and fields in FormTitan, including connections to/from Salesforce objects, and connections to printable version of forms.  (which fields now?) >> to another week
39. Rolled out first version of Intake Summary Sheet. >> to another week
40. Researched FormTitan options for in-between status for Intake Summary Sheet involving staffing signatures.  Might need a version 2.
41. Revised language in Client Handbook to reflect new Forms/processes. >> to another week
42. 
43. for consistency when creating mailing lists.  revised values to show Do Not Contact / Solicit distinction.  Attempted to build process builder to replicate solicitation values from Contact to Accounts (but realized same issue with batch edit)  Need to research if this is a native SF function, possibly rebuild function.  >> to another week
44. 
45. Streamlined the rest of the 1009 reports (incl/excl support groups).  >> to another week
46. 
47. Continued to build out redesigned Status-Service structure.  Use existing Service Files to label all child activities.  Consolidate existing Service Files to two.  Create Clinic section on Case Record and train/test.  Build Participation List feature from scratch.   >> to another week.
48. EPIPHANY Concluded that time-based participation is critical distinction.   [took critical thinking and observing patterns/characteristics in engagement types, not exercises - WHO would’ve been able to discover that??]

36. Reviewed concepts with case management team after observing incoming data patterns.  >> to another week
37. Observed a client intake conducted by case manager. >> to another week

22. Any new surprises?  There is a definite need for training on Object Structure - but when and who?  and how to cleanup existing?  >> to another week
23. Possibly research parent-child Account structure and Record Types for Biz Dev >> to another week

- - - -
### Quarterly Goals
*By midQ2 (nov15):* Coordinate with Client Services Operations to restructure how reporting requirements are stored and fed into Salesforce, Written documentation two-thirds done, Profile settings plan created.
*By endQ2 (dec31):* State reporting generated from new Status-Service structure, 2nd round of Client Services issues complete & 3rd round prioritized, Donor-driven info updating, Written documentation done, Historical Client Services data plan created, Reassess object structure incl Bus. Development, Profile settings plan underway, Certification exam.
*By midQ3 (feb15):* 3rd round of Client Services solutions complete & 4th round prioritized, Historical Client Services data plan underway, Brainstorm registration improvements, Reporting & dashboards.
*By endQ3 (mar31):* 4th round of Client Services solutions complete.