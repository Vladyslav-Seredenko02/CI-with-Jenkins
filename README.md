# CI-with-Jenkins

## What was implemented
1. Jenkins job configured to run only on a dedicated agent (slave node)
2. Maven build execution with parameters (browser, environment, test suite)
3. SCM polling trigger configured (checks for changes every 5 minutes)
4. Scheduled job execution configured (runs daily at midnight)
5. CI pipeline execution successfully triggers and runs all automated tests
6. Test execution includes both passing and intentionally failing test cases, demonstrating CI failure detection mechanism
