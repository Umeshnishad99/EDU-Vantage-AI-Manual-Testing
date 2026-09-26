# EDU-Vantage-AI Test Cases

| ID | Module | Scenario | Expected Result | Status |
|---|---|---|---|---|
| AUTH-01 | Authentication | Register valid student | Account created and email verification prompt displayed | PASS |
| AUTH-02 | Authentication | Register duplicate email | Duplicate account prevented with error | PASS |
| AUTH-03 | Authentication | Login before email verification | Login blocked with verification message | PASS |
| AUTH-04 | Authentication | Verify email | Account becomes verified | PASS |
| AUTH-05 | Authentication | Valid student login | Student redirected to student dashboard | PASS |
| AUTH-06 | Authentication | Valid teacher login | Teacher redirected to teacher dashboard | PASS |
| PERF-01 | Performance | Submit valid academic profile | Data saved and prediction workflow completes | PASS |
| PERF-02 | Performance | Validate attendance normalization | Correct attendance representation sent to ML service | PASS |
| PERF-03 | Performance | Enter marks below 0 or above 100 | Invalid values rejected | PASS |
| PRED-01 | Prediction | Run standalone GPA prediction | Prediction, category and AI note displayed | PASS |
| PRED-02 | Prediction | Test High/Medium/Low thresholds | Correct category assigned | PASS |
| STUD-01 | Dashboard | Verify KPI calculation | GPA, efficiency and category render correctly | PASS |
| STUD-02 | Dashboard | Low subject/attendance weakness | Relevant weakness alerts displayed | PASS |
| STUD-03 | Dashboard | Open recommendations | Matching CGPA recommendations displayed | PASS |
| STUD-04 | Dashboard | Open career roadmap | Matching roadmap displayed | PASS |
| ADM-01 | Admin | View overview statistics | Aggregated student metrics displayed | PASS |
| ADM-02 | Admin | Check risk alerts | Attendance/GPA risk alerts displayed | PASS |
| ADM-03 | Admin | Filter students | Correct category records displayed | PASS |
| REC-01 | Admin CRUD | Create CGPA recommendation | Recommendation saved and available | PASS |
| ROAD-01 | Admin CRUD | Create CGPA roadmap | Roadmap saved and displayed | PASS |
| CHAT-01 | Chatbot | Send academic query | AI response returned and history persisted | PASS |
| CHAT-02 | Chatbot | Missing AI configuration | Graceful fallback shown without crash | PASS |
| SEC-01 | Security/RBAC | Student opens teacher dashboard | Access blocked and redirected | PASS |
| SEC-02 | Security/RBAC | Logged-out user opens protected page | Redirected to login | PASS |
| UI-01 | UI | Toggle dark/light theme | Theme changes without layout break | PASS |
| UI-02 | UI | Test mobile viewport | Responsive layout works without horizontal overflow | PASS |
| AUTH-07 | Authentication | Empty registration fields | Required validation displayed | PASS |
| AUTH-08 | Authentication | Invalid email format | Email validation displayed | PASS |
| AUTH-09 | Authentication | Incorrect password | Login rejected with error | PASS |
| PERF-04 | Performance | Empty required performance fields | Submission blocked | PASS |
| PERF-05 | Performance | Attendance boundary values | Valid boundary accepted and invalid range rejected | PASS |
| PRED-03 | Prediction | Missing predictor input | Validation/error displayed | PASS |
| STUD-05 | Dashboard | Dashboard with no prediction | Appropriate empty state displayed | PASS |
| ADM-04 | Admin | Unauthorized CRUD attempt | Action blocked | PASS |
| CHAT-03 | Chatbot | Empty chatbot message | Empty message not submitted | PASS |
| UI-03 | UI | Resize desktop/tablet/mobile | Layout remains usable | PASS |
| UI-04 | UI | Broken/slow asset observation | User receives usable page state | PASS |
