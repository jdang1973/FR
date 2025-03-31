
 

| Priority | Test Scenario | Source (HP ALM) | Target (Jira - Xray) | Test Objective |
|----------|----------------|------------------|------------------------|-----------------|
| 1 | Verify successful migration of Test Execution entities | Test Lab (Test Sets) | Test Executions | Ensure each Test Set in HP ALM is migrated as a Test Execution in Xray |
| 2 | Validate correct mapping of Test Case references in Test Executions | Test Lab → Test Instances | Test Execution → Tests | Ensure associated test cases are accurately referenced |
| 3 | Validate execution status migration | Test Run Status | Test Execution Status | Verify execution results (Passed/Failed/Blocked/etc.) are preserved |
| 4 | Validate test step execution result mapping | Run Step Status | Test Step Results | Ensure each test step’s result and status are correctly mapped |
| 5 | Verify attachments in test executions are migrated | Test Run Attachments | Execution Evidence | Confirm all files (e.g., logs, screenshots) are transferred correctly |
| 6 | Validate actual test run date and time is retained | Execution Date/Time | Test Execution Fields | Ensure test run timestamps match |
| 7 | Validate tester name/user who executed the test | Run Owner | Executed By | Maintain test run ownership |
| 8 | Validate linked defects migration from execution | Linked Defects in Runs | Defects in Execution | Verify defect links are preserved |
| 9 | Validate comments/notes in test execution are migrated | Run Comments | Execution Comments | Check that tester notes and comments are moved properly |
| 10 | Ensure Test Execution status is correctly calculated | Run Results | Test Execution Summary | Validate summary result logic in Xray |
| 11 | Verify that all test executions are assigned to correct Test Plan | Test Plan Association | Test Execution → Test Plan | Confirm association with test planning context |
| 12 | Validate field-level mapping for custom fields in Test Executions | Custom Fields in Runs | Custom Fields in Execution | Ensure all custom metadata is correctly migrated |
| 13 | Validate hierarchical mapping (Test Set folders to Jira structure) | Test Lab Folder Hierarchy | Jira Folder/Labels/Components | Preserve organization of test executions |
| 14 | Validate test cycle naming conventions | Test Set Name | Test Execution Name | Ensure consistent naming practices |
| 15 | Verify traceability to Requirements/User Stories | Requirements Coverage | Issue Links (Story/Epic) | Confirm that traceability is intact |
| 16 | Validate execution environment data | Test Configuration | Test Environment Field | Migrate test environment info like OS, browser |
| 17 | Validate multiple test runs for the same test case | Multiple Runs/Iterations | Test Execution History | Ensure each iteration is preserved in audit |
| 18 | Validate execution status summary report post-migration | ALM Report | Xray Report | Confirm reporting consistency pre/post migration |
| 19 | Validate date filters in Jira reflect correct execution dates | Test Lab Dates | Execution Start/End Date | Enable accurate filtering |
| 20 | Validate cross-project Test Execution migration (if applicable) | Test Sets from multiple projects | Test Executions in correct Jira projects | Ensure project integrity |
| 21 | Validate synchronization retries handle partial failures | Tasktop Sync Logs | Jira Execution Logs | Confirm that retries do not duplicate or miss data |
| 22 | Validate Xray permissions and visibility | HP ALM access roles | Jira Permission Schemes | Ensure users see the correct test data |
| 23 | Validate Test Execution association with Test Runs | Test Lab Executions | Test Executions with Run History | Confirm test results can be reviewed |
| 24 | Validate Test Execution status transition logs (if available) | Run Audit Logs | Jira Change Logs | Verify auditability of status changes |
| 25 | Validate performance of bulk migration | Bulk Test Sets | Bulk Test Executions | Ensure migration process is performant and stable |

 
