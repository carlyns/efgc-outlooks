## Carlyn's Weekly Outlook for 20201005
### Routine Tasks
* Gift Entry
* Letter Generation and Record Updates
* Continue basic SF documentation
* Data Cleanup - case records, service files, activities, contact info
* Standard Salesforce Administration - adjusting settings, prioritizing requests, monitoring data for system issues, answering questions about record history or reports, troubleshooting errors, educating staff on interface
* Monthly reconciliation with finance

### Major SF Issues to assess/tackle: [potential blocks***]
1. Many deprecated fields from cleanup/redesign that need to be confirmed and removed.  Otherwise editing/creating reports is nearly impossible for ordinary users.
2. More complex changes e.g. Forms revisions and connections, any flows/processes, any automations/validations) need steps/documentation.
3. Existing hard-coded components and disconnections discovered while executing improvements. Troubleshoot, redesign, and rebuild these as they are revealed.
4. Merging Contact records leaves leftover empty address records.  Likely caused by process builder attempted by tek to sync affiliate addresses, but instead it was creating several copies of the same address record and no way to delete them when Contact records were deleted.  Turned off and drafting revision, see Addresses issues for progress. 
5. Matching rules and duplicate rules, which help identify duplicate records, have not been working properly since launch.  Currently manually identifying duplicates as they are discovered.  

### Assistance
* Support from leadership to verify the main pieces of information required for state reporting.  Once verified, these can influence / set the stage for Operations.  Then database and related reports can be setup accordingly.

- - - -
#### Last Week’s Summary:
1. Prepped and imported online gifts using 3-step templates.  
2. Coordinated gifts with designations to Walk, Marathon, and Third Party events from various sources (Facebook fundraisers, workplaces, mailed-in).
3. Identified the redundant creation of some service files and removed this option from screens and profiles.  
4. Processed gifts in Amply portal awaiting action.  When possible, created a portal account, gathered gift/employer IDs, verified gift was received, updated gift status in portal and Amply.  Gave status and process update to Development Manager.  Compared Amply report with dashboard.
5. Updated process builder for new Q2 clients. 
6. Investigated and tested import issue where basic contact information was not being updated.  Called SF Support.  Last import seemed successful but will continue to monitor. 

*/// Additional SF/Ops issues addressed: ///*
7. Monitored for issues related to Forms changes, iPads, Activity Unit Names, Interactions object, Service File structure, Activity Label, Activity Case Notes Public Events.  Answered basic questions/clarifications from staff as they arose.
8. Designed and added EFGC Honoree dropdown value to internally track participation/honors that are not directly linked to Activities (eg TSU, gala guests of honor, scholarship winners, etc). 
9. Analyzed existing process builder from launch for syncing affiliation Addresses.  Deactivated after discovering records were being created redundantly and that default SF address features handled the addresses reasonably well.  Creating drafts to use Affiliation object in a useful way.  
10. Analyzed existing matching & duplicate rules from launch.  Discovered they didn’t trigger because a combination of wrong/inactive fields were being used in the conditions, including non-default custom name fields.  Stripped down to simplest and triggered correctly.  Called SF Support.  Also investigating duplicate record sets for future duplicate identification.  
11. Started to compile data for DFI and DHS Quarterly Reporting.
- - - -
### Quarterly Goals
*By midQ2 (nov15):* Admin Documentation complete, Make enough progress on Major SF Issues to remove from high risk list, another round of Client Services solutions prioritized.
*By endQ2 (dec31):* Increased support for Finance/Ops, Research Classy-Mailchimp sync and Donor-driven info updating, Explore dashboards, Supplemental video documentation, current round of Client Services solutions complete.
*By midQ3 (feb15):* Pure administration, another round of Client Services solutions prioritized.