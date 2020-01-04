## Carlyn's Weekly Outlook for 20200113
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
2. Coordinated gifts with designations to Walk, Marathon, and Third Party events from various sources (Facebook fundraisers, workplaces, mailed-in). 
3. Processed gifts in Amply portal awaiting action.  When possible, created a portal account, gathered gift/employer IDs, verified gift was received, updated gift status in portal and Amply.  Compared Amply report with dashboard.
4. Rolled out Label and Envelope templates for Client Services team.
5. 

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
7. Continued to build out redesigned Status-Service structure.  isn’t this done?
8. Sent official first version of Client Services Salesforce manual to leadership for feedback/markup.  (Sent samples of text 11/18/2019 for pre-approval)
9. Prepped State of Database presentation.   >> to another week
10. More discussion on blaming leaders for not doing their to-dos.  And request that I write up the cheat sheet for them.  >> did it ever get brought up again
11. (12/16 report of week before) 1 hour meeting about “inefficiency” and “ineffectiveness” of database all bc reports aren’t tailored - yet data is there.  and can’t do their job.  CMs can; she can’t bc can’t comprehend?  specifically expiring consent with all info to act on, yet never reviewed / understood or used.   just the fact that it’s not automated to CMs to bypass her so she doesn’t have to manage.  and the batch of internal team reports are still being done; sure after Status-Service Redesign, but didn’t i say i was 90% done?  also they are pretty much done and one-click.  setup was never done right, but it doesn’t mean i can’t now produce reports that are not actionable.  structure makes other things about admin, collection, viewing, more complex, yes reports might need to be combined but still very rich in info.
12. Receive weekly report about Client Services (Operations) perspective on Salesforce issues.  So she can talk more about nothing?  >> to another week
13. Addressed Client Services’ concerns about Salesforce reports, including reminders of already-created reports containing information requested.   again??
14. Monitored lite versions of internal team reports: satisfaction questions, expiring consent, direct referrals, etc.
15. Monitored for issues after rollout of Forms, iPads, Activity Unit Names, Interactions object.  Answered basic questions/clarifications from case management team as they arose.
16. Monitored for issues after rollout of new Service File structure and Activity Label.  Answered basic questions/clarifications from case management team as they arose.
17. Refined paper version forms w Valentina. >> to another week.
18. Addressed push/get integration errors between Forms and Case Record as they arose.   >> to another week.  ??any new??  
19. Continued to give refreshers to CMs on the initial intake steps. >> to another week.
20. Any decision/plan made to redesign initial intake steps to be less dependent on the Process Builder and Flow Builder variables?  not sure if i could come up with a better solution, esp if some CMs aren’t doing initial intake steps at all.  >> to another week.
21. 
22. Had staff test Business Development structure in sandbox.  >> to another week
23. Need to contact SF about displaying child accounts, affiliated contacts, and record type prompt.   >> to another week.  

26. Continued basic UI improvements on Client Services objects: XXX Object.  Reviewing default and required fields, scoping the cleanup necessary, preparing cleanup sheets, hiding/reordering sections and fields, clarifying tasks with case managers and other staff.  >> to another week
27. Rolled out first version of Intake Summary Sheet. >> to another week
28. Researched FormTitan options for in-between status for Intake Summary Sheet involving staffing signatures.  Might need a version 2.
29. 
30. for consistency when creating mailing lists.  revised values to show Do Not Contact / Solicit distinction.  Attempted to build process builder to replicate solicitation values from Contact to Accounts (but realized same issue with batch edit)  Need to research if this is a native SF function, possibly rebuild function.  >> to another week
31. 
32. Streamlined the rest of the 1009 reports (incl/excl support groups).  >> to another week

27. iPad login redirect issue.  Reopen this case with SF Support to see if i can find a competent developer.  To see if there is actual javascript code that can work around the login redirect screen  >> to another week.
28. Reviewed concepts with case management team after observing incoming data patterns.  >> to another week
29. Observed a client intake conducted by case manager. >> to another week


- - - -
### Quarterly Goals
*By midQ3 (feb15):* 3rd round of Client Services solutions complete & 4th round prioritized, Brainstorm registration / letter queue / importing improvements, Report criteria cleanup, Report type research, Certification.
*By endQ3 (mar31):* 4th round of Client Services solutions complete, Brainstorm Donation-Finance flow improvements, Research Classy-Mailchimp sync and Donor-driven info updating, Explore dashboards.
*By endQ3 (may15):* Gifts Documentation complete, Reporting Documentation complete, Admin Documentation complete, Increased support for Finance/Ops.