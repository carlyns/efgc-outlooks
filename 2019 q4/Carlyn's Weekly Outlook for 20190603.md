## Carlyn's Weekly Outlook for 20190603
### Routine Tasks
* Gift Entry
* Monthly report for finance: Classy gifts
* Letter Generation and Record Updates
* Continue basic SF documentation - videos
* Weekly Data Cleanup
* Verify checks for finance

### Three Big SF Issues to assess/tackle: [potential blocks***]
1. Continue Client Services improvements through UI.  Continue deeper object/flow research & design for structural issues.  Establish prevention (temp if needed), consolidate sources if data is missing, perform cleanup for each.
2. Understand reporting requirements and criteria to include in current batch of improvements.
3. Investigate the strange behavior caused when merging Contact records: leftover anonymous empty accounts, leftover addresses.

- - - -
#### Last Two Weeks’ Summary:
1. Completed Golf Outing mailing list.
2. Discussed Golf income discrepancy between Special Events and Finance.
3. Created report showing Case Notes for Dr. Rossi’s clinic clients.
4. Continued testing new workflow to accommodate manual matching gifts process and workplace giving gifts, given predicted influx once Amply is turned on.  Native functionality of soft-crediting donors is not triggered by this import process - need to rework.
5. Created development report showing PAB Giving.
6. Prepped and imported online gifts; separate process for Walk registrations. 
7. Recorded two mailings (golf and walk) in Salesforce. 
8. Assisted at Spanish Conference on Saturday, June 1. 
9. Created mailing list for Camp Appeal by combining donor-based and donation-based report. 

*/// Additional SF issues addressed: ///*
10. Continued basic UI improvements on Client Services objects: Activity, CaseRecord, ContactRecord.  Default and required fields, scoping the cleanup necessary, preparing cleanup sheets, hiding/reordering sections and fields, importing updates to records, clarifying tasks with case managers and other staff.  Minor changes to Event Site/Location and In/Direct Time.
11. Gained understanding of structural difference between CM Activities and Events, which are both subtypes of Activities.  Discovered differences between labels for default, custom, and reporting fields (e.g. Full Comments for Activity Description) and the
12. Created new fields on CaseRecord and IntakeFrom based off of sandbox draft.
13. Prepared CaseRecord to current and future improvements to IntakeForm fields and auto-population.  Adjusted fields and sections to allow for daily use by team.
14. Created variables, mapping values from IntakeForm and to CaseRecord using Flows and ProcessBuilder. Tested connections between the two objects.  Minimized amount of selectable values while maintaining reporting requirements.  Scoped and prepared data in existing fields and moved moved to new objects via imports.
15. Checked which fields were pushing to FormTitan forms and remapped them to new CaseRecord fields (SSN and birthdate).
16. Switched FormTitan authentication from SPalani to EAlvarez.   Turned off email notifications. 
17. Discussion about internal QB Accounts and Campaigns categorization.
18. Explored settings for profiles and page layouts specific to client information.
19. Conducted initial observational session to understand Education department tasks and Salesforce needs.
20. Reviewed original internal staff and activity reports from Penelope to scope/ plan how to build the Salesforce version. 
21. Discussed DHS activity categories briefly - what falls under “case management” and “assistance/counseling/meeting”. 
22. Communicated with SF support regarding mapping referral fields from Contact to CaseRecord.  They could not figure map from more than one object and said we’d have to use coding or hire a developer. 
23. Attempted to setup Classy custom field for importing online gifts.  Called SF Support. Still need to setup the workflow. 
24. Small adjustments to initial intake screens as they are being tested by Valentina and Debbie.

- - - -
### Quarterly Goals
*By endQ4:* Basic Client Services issues identified including reporting gaps and initial round of corresponding solutions, Refined volunteer system
*By midQ1:* Next batch of Client Services issues prioritized, Start Written Documentation, Plan for Profile Settings, Refined Gift Processing,
*By endQ1:* Donor-Driven Info Updating, Object Structure, Brainstorm Registration Improvements, Reporting and Dashboards