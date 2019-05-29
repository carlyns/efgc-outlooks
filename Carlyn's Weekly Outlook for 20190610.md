## Carlyn's Weekly Outlook for 20190610
### Routine Tasks
* Gift Entry
* Monthly report for finance: Classy gifts >> move to first week of June
* Letter Generation and Record Updates
* Continue basic SF documentation - videos
* Weekly Data Cleanup
* Verify checks for finance
* something else?
* Monthly reconciliation for finance  >> move to second week of June

### Three Big SF Issues to assess/tackle: [potential blocks***]
1. Continue Client Services improvements through UI.  Continue deeper object/flow research & design for structural issues.  Establish prevention (temp if needed), consolidate sources if data is missing, perform cleanup for each.
2. Understand reporting requirements and criteria to include in current batch of improvements.
3. Investigate the strange behavior caused when merging Contact records: leftover anonymous empty accounts, leftover addresses.
4. 
5. Investigate strange import behavior: a) When Donations’ primary contact is not Account’s primary contact, matching doesn’t happen.  b) When multiple donations are from the same donor, “Insert” throws an error, sometimes “Update” too.  c) Name matching includes middle name but not alternate names.  (>> Understand consequences and limitations of matching by email. )
6. > > Reminder.  Examples of usability/inflexibility built by TEK that have been revealed over time, and if not addressed, had the potential to completely block operations in the future … they had professional duty to take care of this
7. Design from scratch (I suppose part of job description) custom Profiles for searching, object access, field permissions, etc to bolster better UI.  But I consider this a block because it wasn’t done at all, affects Data Quality bc CMs can’t view context/dups along with no training and no data context. >> to another week
8. Investigate the strange behavior caused when merging Contact records: leftover anonymous empty accounts, leftover addresses.
9. Another stab at the crazy Duplicate rules …

- - - -
#### Last Week’s Summary:
1. Prepped and imported online gifts; separate process for Walk registrations.  >> to another week
2. Continued testing new workflow to accommodate manual matching gifts process and workplace giving gifts, given predicted influx once Amply is turned on.  Native functionality of soft-crediting donors is not triggered by this import process - need to rework.  
3. Recorded Walk & Golf mailings to Campaign History in Salesforce.
4. Extra recognition report for development.
5. 
6. Any Classy tickets?  >> to another week
**5. Streamlined picklist behavior for “XX” Donation field**
7. Autofy sync status?
8. another Viewing Donor History in Salesforce for Finance??
9. Analyzed reports for Giving Data in Giftworks and Salesforce to test data integrity between systems.  >> to another week
10. Discussed Golf income discrepancy between Special Events and Finance. 
11. 

*/// Additional SF issues addressed: ///*
14. Continued basic UI improvements on Client Services objects: Activity, CaseRecord, ContactRecord.  Default and required fields, scoping the cleanup necessary, preparing cleanup sheets, hiding/reordering sections and fields, importing updates to records, clarifying tasks with case managers and other staff.  Minor changes to Event Site/Location and In/Direct Time.  
15. Gained understanding of structural difference between CM Activities and Events, which are both subtypes of Activities.  Discovered differences between labels for default, custom, and reporting fields (e.g. Full Comments for Activity Description) and the 
16. Created new fields on CaseRecord and IntakeFrom based off of sandbox draft. 
17. Prepared CaseRecord to current and future improvements to IntakeForm fields and auto-population.  Adjusted fields and sections to allow for daily used by team. 
18. Created variables, mapping values from IntakeForm and to CaseRecord using Flows and ProcessBuilder. Tested connections between the two objects.  Minimized amount of selectable values while maintaining reporting requirements.  Scoped and prepared data in existing fields and moved moved to new objects via imports.  
19. Discussion about internal QB Accounts and Campaigns categorization. 
20. Explored settings for profiles and page layouts specific to client information.  
21. Conducted initial observational session to understand Education department tasks and Salesforce needs. 

21. Communicated with SF support: ?? 
22. DHS application  status?
23. Any new surprises?  There is a definite need for training on Object Structure - but when and who?  and how to cleanup existing?  >> to another week
24. Contacted SF support regarding XX issues?   >> to another week

- - - -
### Quarterly Goals
*By endQ4:* Basic Client Services issues identified including reporting gaps and initial round of corresponding solutions, Refined volunteer system
*By midQ1:* Next batch of Client Services issues prioritized, Start Written Documentation, Plan for Profile Settings, Refined Gift Processing,
*By endQ1:* Donor-Driven Info Updating, Object Structure, Brainstorm Registration Improvements, Reporting and Dashboards