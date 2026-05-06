# CI-with-Jenkins

## What was implemented
Jenkins job configured to run only on a dedicated agent (slave node)
Integration with GitHub repository for source code management
Maven build execution with parameters (browser, environment, test suite)
SCM polling trigger configured (checks for changes every 5 minutes)
Scheduled job execution configured (runs daily at midnight)
CI pipeline execution successfully triggers and runs all automated tests
Test execution includes both passing and intentionally failing test cases, demonstrating CI failure detection mechanism
Jenkins correctly marks the build status as FAILURE when at least one test fails, proving proper CI behavior
