## Carlyn's Weekly Outlook for 20191209
### Routine Tasks
* Gift Entry
* Letter Generation and Record Updates
* Continue basic SF documentation
* Weekly Data Cleanup
* Verify checks for finance
* Standard Salesforce Administration - adjusting settings, prioritizing requests, monitoring data entry, answering questions about record history, troubleshooting errors, assisting with reports, educating staff on interface
* Monthly reconciliation with finance, July & August

### Major SF Issues to assess/tackle: [potential blocks***]
1. Continue Client Services improvements through UI.  Continue research, design & preparation for structural improvements.  Establish prevention (temp if needed), consolidate sources if data is missing, perform cleanup for each.
2. Troubleshoot, redesign, and rebuild existing hard-coded components and disconnections discovered while executing improvements.
3. Design how new reporting requirements can be captured in database based on Operations adjustments.  Build, test, and roll-out these new features.  Test report generation using new features.
4. Incorporate new structural design changes into quarterly and year-end state reports and coordinate with Client Services operations.

### Assistance
* Support from leadership to verify the main pieces of information required for state reporting.  Once verified, these can influence / set the stage for Operations.  Then database and related reports can be setup accordingly.

- - - -
#### Last Week’s Summary:
1. Prepped and imported online gifts.  Refined import steps to use ClassyID fields for matching contacts.  
2. Created End-of-Year Appeal mailing list.  Revised some criteria a few times and combined 2 SF reports each time.  
3. Parsed through a Classy report discrepancy this month $8.31 between what hit account and what totaled on report.  Classy support mediated communication with WePay.  They were not able to give insight and attached an unhelpful transactions export (all-time).   Mentioned the possibility of a fee refund delay, and they both agreed.  Response: fee displayed on report was incorrect.  
4. Coordinated gifts with designations to Walk, Marathon, and Third Party events from various sources (Facebook fundraisers, workplaces, mailed-in). 
5. Processed gifts in Amply portal awaiting action.  When possible, created a portal account, gathered gift/employer IDs, verified gift was received, updated gift status in portal and Amply.  Compared Amply report with dashboard.

*/// Additional SF/Ops issues addressed: ///*
6. Discussed reporting criteria to create an email list for Support Groups. 
7. Discussed how to identify clients at events (such as Holiday Party) that need to establish consent; whether to do this task before, during, or after event.  
8. Monitored lite versions of internal team reports: satisfaction questions, expiring consent, direct referrals, etc.
9. Monitored for issues after rollout of Forms, iPads, Activity Unit Names, Interactions object.  Answered basic questions/clarifications from case management team as they arose.
10. Discovered that case managers will be performing initial intakes.  With more users, need to rethink intake steps as collecting information at this stage might happen after CaseRecord is created and after IntakeForm is saved for the first time (instead of all in one session).  
11. Presented the new Service File consolidation and Activity label to the CM team during their weekly meeting.  Gave a refresher on the initial intake steps.  
12. Monitored for issues after rollout of new Service File structure and Activity Label.  Answered basic questions/clarifications from case management team as they arose.
13. Continued to build out redesigned Status-Service structure.  Continued steps to ensure all Service Files, Activities, and Case Records were transitioned over to the newly consolidated service file structure.  Included finding Activities unconnected to any Client/Case Record/ServFile, preparing data files, and importing new values.  
14. Designed way to identify “new” clients based on consent renewal field (step 1) and hopefully later “new” clients for each quarter (step 2).  Reworked fields on FormTitan forms to gather CM input on “annual review, new client, former client establishing new consent.”  Programmed using Process Builder: a consent renewal field to auto-populate based on date consent was established and new field on Consent Form.  
15. Communicated with SF Support about delay on time-triggered Process.  No resolution - their response was “it just happens sometimes.”
16. Discovered through research and SF Support calls that printing case notes in batches is not possible (only individually).  In fact, individual printing of any record is a new feature as of Spring ’19.  
17. Contacted SF Support about deleting older versions of flows to remove field references to change their data type for character lengths.  Guided through new Flows interface by SF Support - new location for deletion.  

- - - -
### Quarterly Goals
*By endQ2 (dec31):* State reporting generated from new Status-Service structure, 2nd round of Client Services issues complete & 3rd round prioritized, Written documentation done, Reassess object structure incl Bus. Development, Profile settings plan underway, Certification exam.
*By midQ3 (feb15):* 3rd round of Client Services solutions complete & 4th round prioritized, Brainstorm registration / letter queue / importing improvements, Report criteria cleanup, Report type research.  
*By endQ3 (mar31):* 4th round of Client Services solutions complete, Brainstorm Donation-Finance flow improvements, Research Classy-Mailchimp sync and Donor-driven info updating, Explore dashboards. 