## Carlyn's Weekly Outlook for 20191028
### Routine Tasks
* Gift Entry
* Letter Generation and Record Updates
* Continue basic SF documentation
* Weekly Data Cleanup
* Verify checks for finance
* Standard Salesforce Administration - adjusting settings, prioritizing requests, monitoring data entry, answering questions about record history, troubleshooting errors, assisting with reports, educating staff on interface

### Three Big SF Issues to assess/tackle: [potential blocks***]
1. Continue Client Services improvements through UI.  Continue research, design & preparation for structural improvements.  Establish prevention (temp if needed), consolidate sources if data is missing, perform cleanup for each.
2. Troubleshoot, redesign, and rebuild existing hard-coded components and disconnections discovered while executing improvements.
3. Design how new reporting requirements can be captured in database based on Operations adjustments.  Build, test, and roll-out these new features.  Test report generation using new features.
4. Incorporate new structural design changes into quarterly and year-end state reports and coordinate with Client Services operations.

- - - -
#### Last Week’s Summary:
1. Updated mailing list for Holiday Cards.  Added Marathon participants.  Made corrections to contact records.  
2. Generated mailing list for Client Holiday Party based on Activity in the last year.  
3. Coordinated gifts with designations to Walk, Marathon, and Third Party events from various sources (Facebook fundraisers, workplaces, mailed-in). 
4. Processed gifts in Amply portal awaiting action.  When possible, created a portal account, gathered gift/employer IDs, verified gift was received, updated gift status in portal and Amply.

*/// Additional SF/Ops issues addressed: ///*
5. Adjusted Salesforce system to accommodate new reporting fields: Support Group Leader names.  While awaiting finalized text, prepped Case Record and Activity objects for satisfaction questions using dropdown scale.  
6. Clarified workload and provided progress report.  Facilitated discussion around “new” client definition.  Outlined rollout of operational needs.  Participated in general discussion of the impact of reporting changes on application and award of grant.
7. Refined the Incident Report in FormTitan to be dynamic.  
8. Corrected the Authorization Form to show full last name length. 
9. Reviewed recently completed tasks and upcoming changes with case management team, e.g. iPad login redirect workaround, direct referrals on case note, concept around Interactions, forthcoming satisfaction questions.  
10. Designed programming rules for Consent labels to work with auto-triggers, identify “new” clients, and populate expiring consent reports.  
11. Continued to build out redesigned Status-Service structure.  Investigated historical form data and discovered no consent forms were imported and therefore no consent dates to use.  
12. Built two processes (in Process Builder) to auto-label consent and to generate an expiration date.  Investigating how to update values with a batch refresh (SF Support) and because of this, whether using Formula field is an option.  
13. Communicated with SF Support regarding validation rules: two fields - if one has a value, the other value should be filled; if both are empty, save is ok; if both are filled then save is ok.  
14. Setup lite versions of internal team reports: all Quarter’s Activities (DHS/DFI), Expiring Consent, Consent Unknown.  
15. Monitored new Interactions object.  
16. Monitored for issues after rollout of new Forms.  Answered basic questions/clarifications from case management team as they arose.
17. Monitored for issues after rollout of iPads.  Continued to troubleshoot login redirects with Salesforce Support.  They had me test old code, of which I already knew the behavior, in the sandbox.  They assumed it would work in production and suggested I deploy the code myself to production, which is risky.  Conclusion: it is an iOS software glitch (the connection to third party apps when going from browser back to the app was not seamlessly built), beyond user/admin settings.  May reopen in the future with another support agent, but for now the workaround is only one click.  
18. Monitored for issues after rollout of streamlined Activity Unit Names.
19. Discovered Do Not Solicit does not auto-mark when contact is marked deceased.  Need to research if this is a native SF function.  For short-term, transferred solicitation values from Contacts to Accounts for consistency when creating mailing lists.   

- - - -
### Quarterly Goals
*By midQ2 (nov15):* Coordinate with Client Services Operations to restructure how reporting requirements are stored and fed into Salesforce, Written documentation two-thirds done, Reassess object structure incl Bus. Development, Profile settings plan created.
*By endQ2 (dec31):* State reporting generated from new Status-Service structure, 2nd round of Client Services issues complete & 3rd round prioritized, Donor-driven info updating, Written documentation done, Historical Client Services data plan created, Profile settings plan underway, Certification exam.
*By midQ3 (feb15):* 3rd round of Client Services solutions complete & 4th round prioritized, Historical Client Services data plan underway, Brainstorm registration improvements, Reporting & dashboards.
*By endQ3 (mar31):* 4th round of Client Services solutions complete.