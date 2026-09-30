# Project Testing – FitBuddy

Test cases for manual and API testing. Fill the **Actual Result / Status** columns while running the app and attach screenshots in this folder.

| ID | Test Case | Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC01 | Home page loads | Open `/` | Input form is shown | | |
| TC02 | Generate plan | Fill form, submit | 7-day plan + nutrition tip displayed | | |
| TC03 | User saved | Submit form, open `/view-all-users` | User and plan appear in table | | |
| TC04 | Existing user update | Submit again with same user ID | User record is updated, not duplicated | | |
| TC05 | Feedback revision | Enter feedback on result page | Updated plan displayed and stored | | |
| TC06 | Admin dashboard | Open `/view-all-users` | All users with original/updated plans | | |
| TC07 | Swagger UI | Open `/docs` | All API routes listed | | |
| TC08 | JSON workout API | POST `/generate-workout/gemini` | Workout text returned | | |
| TC09 | Nutrition tip API | GET `/nutrition-tip` | Tip returned | | |
| TC10 | Missing API key | Remove key from `.env`, generate plan | Error handled, app does not crash | | |
| TC11 | Invalid input | Send wrong data types to JSON API | 422 validation error | | |
