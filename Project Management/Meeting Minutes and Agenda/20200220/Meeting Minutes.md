# Development Checkpoint

Introduction
------------
To provide overall project status and to have a place to identify all critical issues and identify action, owners and review timelines.

Schedule
--------

Current
Zowe 1.9.0 (January 28, 2020 - February 25, 2020)
- Sprint 1 (Jan 28, 2020 - Feb 10, 2020)
   - Node v12 Support (Nightly build)
   - SMP/E PTF Support (Convenience build upgrade documentation)
- Sprint 2 (Feb 11, 2020 - Feb 24, 2020)
   - Code Complete/RC Candidate Build (Feb 19, 2020)
   - Test RC Candidate (Feb 19, 2020 - Feb 24, 2020) (Approximately 5 days to test and rebuild RC if needed)
   - Playback (February 24, 2020)
- 1.9.0 GA (February 25 2020) (will include LTS and GA of SMP/E PTF Support)

Next
- Zowe 1.10.0 (February 25, 2020 - March 24, 2020)
- Sprint 1 (Feb 25, 2020 - March 9, 2020)
- Sprint 2 (March 10, 2020 - March 23, 2020)
 - Code Complete/RC Candidate Build (March 20, 2020)
 - Playback (March 23, 2020)
- 1.10.0 GA (March 24 2020)

Agenda Items
------------
1. Start Recording
2. ZLC Updates
3. Current Release and Build Status (Jack/Mark)
    - Nightly build is green.
    - Will build v1.9.0-RC1 today.
4. Plan
     - Discuss v1.9.0 Release
     - Squads confirm that the content is confirmed for the v1.9.0 release
     - Playback (February 24). Agenda https://ibm.ent.box.com/notes/284332824321
5. Squad Status:
    - Installation (Joe/Rose)
    - Onboarding (JoeW/Taylor)
    - Core/Web/Editor (JPL/Nolan/James)
        - Allow Symbols in RBAC URLs
        - Zlux server framework logging
        - Node 12 support 
    - API Mediation Layer & Security (Petr G/Michal S/Petr P)
      - Done:
        - Modify Catalog and Gateway to remove old enabler and use only Spring cloud          
      - In progress:
        - Implement support in Gateway’s Tomcat for special characters in a service URIs      
        - Modify enablers to conditionally allow special characters in a service URIs            
    - Foundation (CI/CD) (Mark/Jack/Nick)
      - Preparing for v1.9.0 release.
      - License scan for the latest code and license file will be updated.
      - Working on new solution of zowe-install-test, will merge this repository into zowe-install-packaging soon.
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
