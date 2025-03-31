 Here is a table listing the **Top 25 Test Scenarios** to validate the successful migration of issue type **"Test"** from **HP ALM to Jira Xray via Tasktop**, prioritized by importance:

| **Priority** | **Test Scenario**                                                     | **Source (HP ALM)**                  | **Target (Jira - Xray)**              | **Test Objective**                                                                 |
|--------------|-----------------------------------------------------------------------|--------------------------------------|----------------------------------------|------------------------------------------------------------------------------------|
| 1            | Migrate manual test cases                                             | Test Plan → Manual Tests             | Issue Type = Test (Manual)             | Ensure all test cases are migrated and visible in Jira Xray                        |
| 2            | Validate test case steps                                              | Design Steps                         | Test Steps                             | Verify step details (action, expected result) are preserved                        |
| 3            | Validate test case descriptions                                       | Test Case Description                | Description Field                      | Confirm rich-text descriptions are intact and complete                             |
| 4            | Validate test case names                                              | Test Name                            | Summary Field                          | Ensure test names are preserved without truncation or corruption                   |
| 5            | Validate folder structure/tag mapping                                 | Test Plan Folder Structure           | Labels / Custom Field / Component      | Ensure test case organization is preserved or appropriately mapped                 |
| 6            | Validate custom fields migration                                      | User-defined fields in Test Plan     | Custom Fields                          | Confirm custom field values are migrated correctly                                |
| 7            | Validate test case priority                                           | Priority Field                       | Priority Field                         | Check that priority is accurately mapped                                           |
| 8            | Validate test case owner/author                                       | Owner                                | Reporter / Custom Field                | Confirm original authorship is retained                                            |
| 9            | Validate test case attachments                                        | Attached to Test or Steps            | Jira Attachments                       | Ensure attachments are migrated and accessible                                     |
| 10           | Validate status field migration                                       | Status (e.g., Ready, Draft)          | Custom Status or Field in Jira         | Confirm test status is accurately reflected                                        |
| 11           | Validate test case creation date                                      | Created Date                         | Created Date                           | Ensure timestamps are consistent with original ALM data                            |
| 12           | Validate last modified date                                           | Last Modified Date                   | Updated Date                           | Validate modification metadata is preserved                                        |
| 13           | Validate automated flag indicators                                    | Field = Automated = Yes/No           | Custom Field in Jira                   | Ensure automation indicator is mapped                                              |
| 14           | Validate original ALM test ID is preserved                            | Test ID                              | Custom Field in Jira                   | Enable traceability from Jira back to ALM                                          |
| 15           | Validate mapping of test folders to Jira components or labels         | Folder Name                          | Component / Label                      | Organize test cases meaningfully in Jira                                           |
| 16           | Validate formatting in test steps (e.g., bullets, bold text)          | Step Description Formatting          | Step Formatting                        | Ensure rich-text is preserved                                                      |
| 17           | Validate version history or revision notes (if required)              | Test Case History                    | Comments / Custom Fields               | Check for migration of version-related information                                 |
| 18           | Validate linked test requirements (coverage mapping)                  | Requirement Coverage                 | Xray Requirement Links                 | Ensure coverage relationships are intact                                           |
| 19           | Validate cross-referenced test case links                             | Linked Test Cases                    | Issue Links                            | Confirm referenced tests remain linked                                             |
| 20           | Validate duplicate handling                                            | Duplicate Tests                      | Jira Dedupe                            | Ensure duplicate records are not created                                           |
| 21           | Validate Tasktop field mappings are respected                         | Tasktop Integration Config           | Jira Fields                            | Ensure field mappings function per configuration                                   |
| 22           | Validate large test cases (>10 steps) migration                       | Test Cases with Many Steps           | Issue Type = Test                      | Confirm that all steps are migrated even in large test cases                       |
| 23           | Validate test case sorting order                                      | Folder/ID-based Sorting              | Jira Test Repository View              | Ensure test organization/order is maintained                                       |
| 24           | Validate handling of empty or partial test cases                      | Test Cases without Steps             | Jira Tests                             | Confirm migration handles partial data gracefully                                  |
| 25           | Perform end-to-end reconciliation report                              | Full Test Plan                       | Jira Project Tests                     | Final validation of test count and data completeness                               |

---

Would you like this in **Excel**, **CSV**, or a **Jira import format**?




