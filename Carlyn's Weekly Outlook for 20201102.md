## Carlyn's Weekly Outlook for 20201102
### Routine Tasks
* Gift Entry
* Classy payout reports showing any splits
* ROCS report creation with client info overlay for Event Attendance
* Letter Generation and Record Updates
* Continue basic SF documentation
* Data Cleanup - case records, service files, activities, contact info
* Standard Salesforce Administration - adjusting settings, prioritizing requests, monitoring data for system issues, answering questions about record history or reports, troubleshooting errors, educating staff on interface

### Major SF Issues to assess/tackle: [potential blocks***]
1. Many deprecated fields from cleanup/redesign that need to be confirmed and removed. Otherwise editing/creating reports is nearly impossible for ordinary users.
2. More complex changes e.g. Forms revisions and connections, any flows/processes, any automations/validations) need steps/documentation.
3. Existing hard-coded components and disconnections discovered while executing improvements. Troubleshoot, redesign, and rebuild these as they are revealed.

### Assistance
* Support from leadership to verify the main pieces of information required for state reporting.  Once verified, these can influence / set the stage for Operations.  Then database and related reports can be setup accordingly.

- - - -
#### Last Week’s Summary:
1. Coordinated gifts with designations to Walk, Marathon, and Third Party events from various sources (Facebook fundraisers, workplaces, mailed-in).
2. Processed gifts in Amply portal awaiting action.  When possible, created a portal account, gathered gift/employer IDs, verified gift was received, updated gift status in portal and Amply.



*/// Additional SF/Ops issues addressed: ///*
3. Monitored for issues related to Forms changes, iPads, Interactions, Service File structure, Activities, Public Events.  Answered basic questions/clarifications from staff as they arose.
4. Removed Correspondence object, reduced Tribute object usage for tracking sympathy cards only.
5. Continued to manually identify potential duplicates using exported spreadsheet, making use of duplicate record sets.  Finished identifying dups w/ phone.  Continued & finished identifying dups w/ email.  Started identifying dups w/ address. Contact merging.  Confirmed donations were moved correctly during merges. 
6. Removed trailing commas on ~150 addresses. 
7. Communicated with SF Support about new error when moving members between households.  They were able to tell me which apex classes to add to the list of enabled classes, which I repeated for all relevant profiles.
8. Launched new Counseling Form to Clinical Dept staff.
9. Continued Forms changes for Case Management staff.  Analyzed existing data for Background form, prepped for consolidation, and moved old data into relevant fields.  Adjusted/created relevant Case Record fields to accommodate new changes, established relevant access. Revised Goals and Background forms in FormTitan.  Designed and drafted new Goals and Background pdf templates using dynamic feature.  Analyzed and adjusted Goals and Background field mapping from FormTitan to CaseRecord, CaseRecord to FormTitan, and from FormTitan to the pdf.  Added live testing form to E-Forms button.   Tested mappings for all new/revised fields.
10. Adjusted/created relevant Intake fields to accommodate new Background form changes.  Prepped necessary Intake fields for data consolidation and moved old data into relevant fields.  Analyzed and adjusted Background field mapping from Intake into variables (Flow) and from variables into CaseRecord (Process Builder), creating new variables where needed.  Tested mappings for all new/revised fields.
11. Analyzed intake Flows and case record Processes to identify deprecated fields and variables, deleting where possible.
12. Setup a Signed/Unsigned stamp for the existing Consent, Info Release, and Contact pdfs and the revised Goals and Background pdfs.
13. For all forms, setup validation rule to require date with signature.  For all forms, researched and deployed push condition to avoid clearing date values with unsigned forms without signature date.
14. Continued to delete obsolete fields from Account/Contact object, locating hard connections where necessary.   Also started deleting obsolete fields from Intake and CaseRecord objects.
15. Researched and summarized issues/options for requesting client signatures virtually through FormTitan.  Requires setup of a live webpage within FormTitan for each pdf.  These steps are overly complicated for standard users.

- - - -
### Quarterly Goals
*By midQ2 (nov15):* Admin Documentation complete, Make enough progress on Major SF Issues to remove from high risk list, another round of Client Services solutions complete, another round of Client Services solutions prioritized.
*By endQ2 (dec31):* Increased support for Finance/Ops, Research Classy-Mailchimp sync and Donor-driven info updating, Explore dashboards, Supplemental video documentation, current round of Client Services solutions complete.
*By midQ3 (feb15):* Pure administration, another round of Client Services solutions prioritized.