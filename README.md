# FUTURE_CS_03-
API Security Risk Analysis – Future Interns Task 3
API Security Assessment Notes

1. Project Information
- Project Name: API Security Risk Analysis
- Organization: Future Interns
- Candidate Name: Bhavya Nagooru
- Assessment Date: 26-11-2026

2. Target Information
- API Name: JSONPlaceholder
- Base URL: https://jsonplaceholder.typicode.com
- Environment: Public Testing API
- Testing Scope: Authorized API testing

3. Tools Used
- Postman
- Web Browser
- Developer Tools

4. API Endpoints Tested

| HTTP Method | Endpoint | Purpose |
|---|---|---|
| GET | /posts/1 | Retrieve a post |
| GET | /users/1 | Retrieve user details |
| GET | /comments | Retrieve comments |

5. Assessment Observations

GET Request
- Endpoint: /posts/1
- Response Status: 200 OK
- Response Format: JSON
- Response included userId, id, title and body fields.

Security Header Observation
- Strict-Transport-Security header was not observed.
- Content-Security-Policy header was not observed.
- These observations require configuration review and are not automatically confirmed vulnerabilities.

6. Risk Assessment
Security risks and severity levels will be assigned only after verifying the test evidence.

7. Recommendations
- Review security header configuration.
- Implement appropriate authentication and authorization where required.
- Validate API inputs.
- Apply suitable access controls.
- Avoid exposing sensitive information in API responses.

8. Evidence
Postman screenshots and API response screenshots will be included in the project repository.

9. Conclusion
The assessment involved testing API endpoints and reviewing HTTP responses and security-related headers using Postman.

Further security observations will be documented based on verified testing evidence.
