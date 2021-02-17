# Development Checkpoint

Introduction
------------
To provide overall project status and to have a place to identify all critical issues and identify action, owners and review timelines.

Schedule
--------

Current

Zowe 1.12.0 (April 28, 2020 - May 29, 2020)
- Sprint 1 (April 28, 2020 - May 11, 2020)
- Sprint 2 (May 12, 2020 - May 25, 2020)
- Code Complete/RC Candidate Build (May 25, 2020)
- Start Testing (May 25, 2020 - May 29, 2020)
- System Demo (May 25, 2020)
- 1.12.0 GA (May 29, 2020)

Next

Zowe 1.13.0 (May 26, 2020 - June 26, 2020)
- Sprint 1 (May 26, 2020 - June 8, 2020)
- Sprint 2 (June 9, 2020 - June 22, 2020)
- Code Complete/RC Candidate Build  (June 22, 2020)
- Start Testing (June 22, 2020 - June 26, 2020)
- System Demo (June 22, 2020)
- 1.13.0 GA (June 26, 2020)


Agenda Items
------------
1. Start Recording
2. ZLC Updates
3. Current Release and Build Status (Jack/Mark)
   - We announced v1.12.0-RC1 after fixed the desktop logout issue.
   - v1.12.0-RC1 remains a known issue which only occurs on Top Secret server with PTF installation. Since the issue is limited to one test scenario on a particular server, we want to see how this build works on squads' tests.
   - Nightly build has extra failure on verifying API Catalog which we had fixed the test case in rc build. This is a new change brought in related to SSO, the test case should be adjusted.
4. Plan
     - Discuss 1.12.0 Release
     - Squads to provide list of work items that needs to be identified for PI Planning
     - PI Planning Call on 6/1
5. Squad Status:
    - Onboarding (JoeW/Taylor/Rose)
    - Core/Web/Editor (JPL/Nolan/James)
      - Working on RC and testing
      - Edit zowe install script to skip certain checks
      - Recalling migrated datasets in Editor
    - API Mediation Layer & Security (Elliot/Michal S/Petr P)
         - Working on gathering inputs for PI Planning call June 1
         - @jandadav working with Jack on RC
         - Bringing #422 as agenda item at next Zowe Architect call     
    - Foundation (CI/CD) (Mark/Jack/Nick)
      - Work with other teams to trouble shooting issues we found in Zowe build.
      - Upgrade a pipeline to clean up tmp folders on test server.
    - Documentation (Brandon/Ashley/Jim/Jason)

6. Legal Requirements
    - None

7. Community Backlog
    - TBD
8. Roundtable
    - None

Action Items
------------
- None
