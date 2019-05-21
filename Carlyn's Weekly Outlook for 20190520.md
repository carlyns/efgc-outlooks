## Carlyn's Weekly Outlook for 20190520
### Routine Tasks
* Gift Entry
* Letter Generation and Record Updates
* Continue basic SF documentation - videos
* Weekly Data Cleanup
* Verify checks for finance

### Three Big SF Issues to assess/tackle: [potential blocks***]
1. Continue Client Services improvements through UI.  Continue deeper object/flow research & design for structural issues.  Establish prevention (temp if needed), consolidate sources if data is missing, perform cleanup for each.
2. Understand reporting requirements and criteria to include in current batch of improvements.
3. Investigate the strange behavior caused when merging Contact records: leftover anonymous empty accounts, leftover addresses.

- - - -
#### Last Week’s Summary:
1. Prepped and imported online gifts; separate process for Walk registrations.
2. Designed and tested a new workflow to accommodate manual matching gifts process and workplace giving gifts, given predicted influx once Amply is turned on.
3. Extra recognition report for development.

*/// Additional SF issues addressed: ///*
4. Continued basic UI improvements on Client Services objects: Activity; default and required fields, scoping the cleanup necessary, preparing cleanup sheets, hiding/reordering sections and fields, importing updates to records, clarifying tasks with case managers and other staff.
5. Major inventory assessment of ReferralForm, Contact, IntakeForm, CaseRecord.  Tested and created holding sections to better understand all fields in sandbox.  Identified fields on paper forms missing from intake screens.  Ultimately decided to bypass the ReferralForm, design screens such that all client information lives on CaseRecord as central hub, and treat the IntakeForm as a snapshot of information at the time of initial intake.
6. Got feedback from Valentina about drafted intake steps and new structural concept for CaseRecord as a central hub for information.
7. Communicated with SF support: UI tabbing behavior is not supported in Lightning despite settings available to control it
8. Communicated SF support: creating variables that can be used to feed data from one object to another (e.g. birthdate from IntakeForm to CaseRecord).  Learned about ProcessBuilder and FlowBuilder steps needed.
9. Researched FormTitan build process.  Watched tutorials and reference materials.  Created test form to try “get” actions (pulling data in from CaseRecord and IntakeForm).  Found and studied TEK’s versions of forms and lightning components using apex code.  Successfully created test button for new form but still unable to “get” values.  Contacted FormTitan support.
10. Learned more about required reporting fields from ROCS entry process and unclear definition of DFI/DHS-funded cases.
11. Monitored status of Salesforce global outage on May 17.

- - - -
### Quarterly Goals
*By endQ4:* Basic Client Services issues identified including reporting gaps and initial round of corresponding solutions, Refined volunteer system
*By midQ1:* Next batch of Client Services issues prioritized, Start Written Documentation, Plan for Profile Settings, Refined Gift Processing,
*By endQ1:* Donor-Driven Info Updating, Object Structure, Brainstorm Registration Improvements, Reporting and Dashboards