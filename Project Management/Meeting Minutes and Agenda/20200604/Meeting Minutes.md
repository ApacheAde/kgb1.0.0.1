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
   - RC2 announced but we found same regression on PTF+TopSecret. This was verified ok with https://github.com/zowe/api-layer/pull/678, but seems not stable as expected.
     Open Question: should we accept this as a known issue and continue release v1.12.0?
   - Nightly build has similar issue (we need to update manifest.json on staging to pick most latest APIML build.)
4. Plan
     - Discuss 1.12.0 Release.
     - PI Planning Call on 6/8. Discuss [Survey](https://ibm.ent.box.com/notes/672825455060)
5. Squad Status:
    - Onboarding (JoeW/Taylor/Rose)
    - Core/Web/Editor (JPL/Nolan/James)
      - More UI improvment research
      - RC testing
    - API Mediation Layer & Security (Elliot/Michal S/Petr P)
      - RC testing
      - API ML support for keyrings (ZAAS client ready; preparing for tests on Marist)
    - Foundation (CI/CD) (Mark/Jack/Nick)
      - Working with different parties on RC build issues, build and test v1.12.0 RC.
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
