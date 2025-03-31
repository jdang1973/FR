
Priority	Test Scenario	Source (HP ALM)	Target (Jira - Xray)	Test Objective
1	Validate that all Test Sets are migrated without data loss	Test Set	Test Set (Xray Test Set)	Ensure the total number of test sets matches between ALM and Jira
2	Validate the unique ID/reference of Test Sets	Test Set ID	Test Set Key	Confirm that references to Test Sets are preserved or properly mapped
3	Validate Test Set names/titles are accurately migrated	Test Set Name	Test Set Summary	Ensure the name/title is correctly reflected post-migration
4	Validate the association of Test Cases within a Test Set	Test Cases in Test Set	Tests in Test Set	Ensure Test Sets contain the correct associated test cases
5	Validate test execution ordering in Test Sets	Test Order in Test Set	Test Execution Order	Ensure test execution order is preserved if applicable
6	Validate description and long text fields of Test Set	Test Set Description	Test Set Description	Confirm long text fields migrate without truncation
7	Validate custom fields specific to Test Sets	Custom Fields	Custom Fields	Ensure all custom fields are transferred accurately
8	Validate status/state of Test Sets	Status	Status	Check that test set statuses are mapped correctly
9	Validate test folder hierarchy (if applicable)	Folder Path/Structure	Xray Test Repository Path	Ensure that Test Set folders and structure are preserved
10	Validate migration of attachments within Test Sets	Attachments	Attachments	Confirm all files are transferred and accessible
11	Validate comments and history within Test Sets	Comments/History	Comments/Activity Log	Check that notes, audit trails, and discussions are retained
12	Validate links to Test Cases	Test Case Link	Test Issue Link	Ensure relationships to tests are maintained
13	Validate migration timestamp fields	Created/Modified Date	Created/Updated Timestamp	Ensure original timestamps are migrated
14	Validate Test Set ownership/assigned users	Owner/Assigned To	Reporter/Assignee	Ensure user mappings are accurate and respected
15	Validate migrated Test Set is searchable	Test Set Name or ID	Xray Search (JQL)	Confirm search and filtering capabilities work post-migration
16	Validate linked defects associated with Test Sets	Defects Linked	Defect Issues	Confirm traceability and linkage is preserved
17	Validate test set tags or labels	Tags/Labels	Labels	Ensure labeling conventions are maintained
18	Validate user permissions on Test Sets	User Roles/Permissions	Project Permissions	Ensure users retain correct permissions to view/edit Test Sets
19	Validate test cycle association (if Test Set is part of a cycle)	Test Set to Cycle Mapping	Xray Test Plan/Test Exec	Ensure cycle-level context is migrated properly
20	Validate audit trail or change history	Audit Logs	History Tab	Confirm audit compliance by reviewing changes
21	Validate Test Set links to Requirements (traceability)	Requirements Traceability	Requirement Links	Ensure requirement coverage is retained
22	Validate folder or module-based grouping of Test Sets	Folder Module Grouping	Test Repository Folder	Check organizational structure
23	Validate test set priority or importance field	Priority Field	Priority Field	Ensure importance or priority metadata is migrated
24	Validate bi-directional sync (if enabled) via Tasktop	ALM ↔ Tasktop	Tasktop ↔ Jira	Ensure changes in ALM are reflected in Jira and vice versa if two-way sync is set up
25	Validate error handling and exception logging during migration	Migration Logs	Jira Logs	Ensure migration errors are logged and testable
Would you like a downloadable version of this (CSV, Excel, or PDF)? Or need help customizing this for your organization’s specific workflow or tool versions?









