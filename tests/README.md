# Test strategy

## Current tests

- Client: semantic accessibility baseline test
- Server: API request contract test

## Recommended next step

Add browser automation with Playwright and an accessibility engine such as axe-core.

Suggested test flow:

1. Start client and server.
2. Open the request page.
3. Run an automated accessibility scan.
4. Tab through the complete form.
5. Submit valid and invalid data.
6. Verify that status/error messages are exposed.
7. Capture evidence for the audit report.
