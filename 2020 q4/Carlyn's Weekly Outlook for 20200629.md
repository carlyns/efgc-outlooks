## Carlyn's Weekly Outlook for 20200629
### Routine Tasks
* Gift Entry
* Letter Generation and Record Updates
* Continue basic SF documentation
* Weekly Data Cleanup - case records, service files, activities, contact info
* Standard Salesforce Administration - adjusting settings, prioritizing requests, monitoring data entry, answering questions about record history, troubleshooting errors, assisting with reports, educating staff on interface

### Major SF Issues to assess/tackle: [potential blocks***]
1. Redundancies for reporting still connected to structural flaws i.e. disconnect between Activities and Public Events.  Redesign and rebuild needs to be planned at time of least disruption.
2. Many deprecated fields from cleanup/redesign that need to be confirmed and removed.  Otherwise editing/creating reports is nearly impossible for ordinary users.
3. More complex changes e.g. Forms revisions and connections, any flows/processes, any automations/validations) need steps/documentation.
4. Existing hard-coded components and disconnections discovered while executing improvements. Troubleshoot, redesign, and rebuild these as they are revealed.

### Assistance
* Support from leadership to verify the main pieces of information required for state reporting.  Once verified, these can influence / set the stage for Operations.  Then database and related reports can be setup accordingly.

- - - -
#### Week Before Last Summary:
1. Generated first draft of Spanish Conference mailing list.  
2. Coordinated gifts with designations to Walk, Marathon, and Third Party events from various sources (Facebook fundraisers, workplaces, mailed-in).
3. Processed gifts in Amply portal awaiting action.  When possible, created a portal account, gathered gift/employer IDs, verified gift was received, updated gift status in portal and Amply.  Compared Amply report with dashboard.
4. Started guidance to SF-tracked DHS reporting requirements. 
5. Assisted with setup of purchasing more Salesforce licenses for contract renewal.  

*/// Additional SF/Ops issues addressed: ///*
6. Monitored lite versions of internal team reports: satisfaction questions, expiring consent, direct referrals, etc.
7. Monitored for issues related to Forms changes, iPads, Activity Unit Names, Interactions object, Service File structure and Activity Label.  Answered basic questions/clarifications from staff as they arose.
8. Brainstormed ideas for categorizing Activities to allow for more client types. 
9. Brainstormed ideas for lite version of Participation label structure.  
10. Communicated with SF Support regarding where/how to control mapping of new fields on Cal Activity that get duplicated when assigned to multiple staff members.  After following instructions, they suggested doing a change set from sandbox.  After tests failed tests, running specific tests led to successful deployment of apex class change to production.  
11. Prioritized project: Wrapped up steps to archive Case Notes and solely use Activities.  Made the new structure visible and hid the Case Notes on all relevant screens (incl moving CaseRec field up to the CompactLayout).  Researched how to hide Case notes from search results and navigation bar selections.  Toggled tabs and object access for standard and custom objects across 5 profiles.  Checked for any last direct referrals. Reviewed training points with Stacy and coordinated rollout with staff leading up to 6/18 presentation.  Updated the Manual.  
12. Researched and added filter to Activity’s Service File lookup field to ensure the correct client is connected even if first and last names are exactly the same.  
13. Updated the DHS reports and leadership reports that are affected by Case Notes project to ensure they are still pulling the same info.  
14. Updated RelatedTo field for functional reporting of Activities.  Created Process Builder to auto-populate RelatedTo field with Case Record.  Mass update of Activities that were missing values.  

- - - -
### Quarterly Goals
*By midQ1 (aug15):* Gifts Documentation complete, Admin Documentation complete, 5th round of Client Services solutions complete, another round of Client Services solutions prioritized.
*By endQ1 (sep30):* Increased support for Finance/Ops, Research Classy-Mailchimp sync and Donor-driven info updating, Explore dashboards
*By midQ2 (nov15):* Supplemental video documentation, pure administration.