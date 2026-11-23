# Manual Test Cases
## Anonymous Chadabazi Reporting Platform

| Test ID | Test Scenario | Expected Result | Actual Result | Status |
|---|---|---|---|---|
| TC-01 | Valid user registration with email and OTP | Account should be created successfully | Not Run | Pending |
| TC-02 | Registration using disposable email | Registration should be rejected | Not Run | Pending |
| TC-03 | Enter incorrect OTP five times | Account should be temporarily locked | Not Run | Pending |
| TC-04 | Select division, district, thana and area | Location options should work correctly | Not Run | Pending |
| TC-05 | Upload an image containing GPS metadata | GPS and device metadata should be removed | Not Run | Pending |
| TC-06 | Upload a file exceeding the size limit | File upload should be blocked | Not Run | Pending |
| TC-07 | Submit a fourth report within 24 hours | Submission should be refused | Not Run | Pending |
| TC-08 | Reviewer tries to access victim identity | Access should be denied | Not Run | Pending |
| TC-09 | Reject a complaint without providing a reason | Rejection should not be saved | Not Run | Pending |
| TC-10 | Check urgency-based case ordering | Fast-track and higher urgency cases should appear first | Not Run | Pending |
| TC-11 | Victim views a rejected complaint | Rejection category and reason should appear | Not Run | Pending |
| TC-12 | Case Officer adds a case update | Victim should see the updated status | Not Run | Pending |
| TC-13 | Third suspected false complaint rejection | Permanent block should be applied pending human review | Not Run | Pending |
| TC-14 | Staff login without two-factor authentication | Login should be denied | Not Run | Pending |
| TC-15 | Switch interface language to Bangla | Bangla labels should display correctly | Not Run | Pending |
| TC-16 | Reviewer opens an unassigned case | Access should be denied | Not Run | Pending |
| TC-17 | Receive a complaint status notification | Notification should not reveal case details | Not Run | Pending |
